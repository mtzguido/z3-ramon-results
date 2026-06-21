# .

* SAT 1
* UNSAT 4
* TIMEOUT 2
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_LIRA.tar.zst?download=1 | Source list: benchmarks-canary.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_LIRA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: c0ec4259e56b1fbd2cf2ecbd00a60bedb56ce0ff
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_LIRA.tar.zst?download=1
Z3 commit message: Regenerate issue-backlog workflow lock to remove stale gh-aw helper call (#9917)

The `Issue Backlog Processor` workflow’s `agent` job was failing at
runtime because the generated lock workflow referenced a non-existent
gh-aw helper (`merge_awf_model_multipliers.cjs`). This PR updates the
lock file to align with current gh-aw output and eliminate that stale
invocation.

- **Root cause addressed**
- `issue-backlog-processor.lock.yml` contained an outdated step that
executed:
- `node "${RUNNER_TEMP}/gh-aw/actions/merge_awf_model_multipliers.cjs"`
- That module is not present in the runner-provisioned gh-aw action set,
causing `MODULE_NOT_FOUND` and failing the `agent` job.

- **Change made**
- Recompiled the source workflow (`issue-backlog-processor.md`) and
committed the regenerated lock file:
    - `.github/workflows/issue-backlog-processor.lock.yml`
- The regenerated lock no longer includes the stale
`merge_awf_model_multipliers.cjs` call and updates associated gh-aw
metadata/version pins accordingly.

- **Illustrative diff (relevant line)**
```yaml
- GH_AW_MODEL_MULTIPLIERS_PATH="/tmp/gh-aw/model_multipliers.json" node "${RUNNER_TEMP}/gh-aw/actions/merge_awf_model_multipliers.cjs"
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_LIRA/LCTES/cruise-control.smt2            |    0.049s | 22.36MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/cruise-control.nosummaries.smt2 |    0.096s | 22.188MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/smtopt.smt2                    |    0.800s | 232.0MiB| sat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/tdf.locals.smt2                |    1.088s | 232.0MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/fly-by-wire.locals.smt2        |    2.764s | 71.436MiB| unsat | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/tdf.locals.nosummaries.smt2    |   20.037s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/QF_LIRA/LCTES/fly-by-wire.locals.nosummaries.smt2 |   20.042s | 453.0MiB| timeout | 0 |  |  |
