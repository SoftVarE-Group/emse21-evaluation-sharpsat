# Empirical Evaluation for `Evaluating #SAT Solvers on Industrial Feature Models` (EMSE'21)

This repository provides a benchmark framework and experiments to evaluate #SAT solvers and different knowledge compilers. The experiment design implied by the run configurations can be used to repeat the experiments for our submission to EMSE'21 `Evaluating #SAT Solvers on Industrial Feature Models`.


## How to build

The python benchmark script can be used as it comes.
However prior to executing the benchmark several solvers need to be built. Furthermore, some solvers are not included in this repository due to licensing issues. 
In `solvers/` the solvers are provided either as built binaries, source code, or links to respective repositories.

## How to run

### Run benchmark
In general, an experiment specified by a .json file can be executed with

```
python3 run.py run_configurations/experiment.json
```

## Resources

[Solvers](https://github.com/SoftVarE-Group/emse21-evaluation-sharpsat/tree/master/solvers)

[Subject Systems](https://github.com/SoftVarE-Group/emse21-evaluation-sharpsat/tree/master/cnf)

