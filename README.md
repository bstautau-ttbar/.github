# Bs → ττ in ttbar (Run 2 + Run 3)

Analysis of the Bs → ττ decay in ttbar events, using Run 2 and Run 3 data. This organization collects every stage of the pipeline, from ntuple production through final performance evaluation.

## Pipeline

| Stage | Repository | Description |
|---|---|---|
| 1 | [part-ntuplizer](https://github.com/bstautau-ttbar/part-ntuplizer) | Ntuplizer producing training samples for the Particle Transformer |
| 2 | [part-training](https://github.com/bstautau-ttbar/part-training) | Training framework for the Particle Transformer |
| 3.1 | [nano-ntuplizer-ml](https://github.com/bstautau-ttbar/nano-ntuplizer-ml) | miniAOD → nanoAOD ntuplizer with embedded ML model inference |
| 3.2 | [nano-skimmer](https://github.com/bstautau-ttbar/nano-skimmer) | Custom nanoAOD skimmer |
| 4 | [analyzer](https://github.com/bstautau-ttbar/analyzer) | Main analysis code |
| 5 | [combine-performance](https://github.com/bstautau-ttbar/combine-performance) | Combine-based framework for performance evaluation |

## Data

Run 2 + Run 3, ttbar processes.
