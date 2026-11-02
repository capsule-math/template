# `<theorem name>` — proof package

<one sentence: what is proved, and that this package records the computer-assisted proof as statement + inputs + checker; see statement.md>

<if some frozen files are not in this copy: "Fetch the frozen inputs first: `julia --project=checker tools/fetch_data.jl` (or download them from the URLs in `data/hashes.json`).">

Check the proof:

```
<run command>
```

<if the proof is made of independent cases, declared in `cases` of entry.json (e.g. `"run": "julia --project=checker checker/verify.jl {n}"`, `"cases": {"n": "1:18"}`): "The checker is run per case, `<run command with {name}>`; it exits 0 iff the conditions of that case hold, and the theorem needs every case." See [capsule-math/spec](https://github.com/capsule-math/spec), §4–§5.>

The workflows in `.github/workflows/` run the checker on every push and pull request through the CI of [capsule-math/index](https://github.com/capsule-math/index) (`check.yml`; with `cases`, on the case `test_case` of entry.json, or the first declared value when there is none) and open a pull request when a dependency moves out of `[compat]` (`CompatHelper.yml`).

<citation of the paper, with DOI or arXiv id>
