# `<theorem name>` — proof package

<one sentence: what is proved, and that this package records the computer-assisted proof as statement + inputs + checker; see statement.md>

<if some frozen files are not in this copy: "Fetch the frozen inputs first: `julia --project=checker tools/fetch_data.jl` (or download them from the URLs in `data/hashes.json`).">

Check the proof:

```
<run command>
```

<if the proof is made of independent cases, declared in `cases` of entry.json
(e.g. `"run": "julia --project=checker checker/verify.jl {n}"`,
`"cases": {"n": "1:18"}`): "The checker is run once per case,
`<run command with {name}>`; it exits 0 iff the conditions of that case hold,
and the theorem needs every case." See the specification, §4–§5.>

<citation of the paper, with DOI or arXiv id>
