# Bs → ττ in ttbar (Run 2 + Run 3)

Analysis of the Bs → ττ decay in ttbar events, using Run 2 and Run 3 data. This organization collects every stage of the pipeline, from ntuple production through final performance evaluation.

## Pipeline

| Stage | Repository | Description |
|---|---|---|
| 1 | [deep-ntuplizer](https://github.com/bstautau-ttbar/DeepNTuplesCharged) | miniAOD → jet-based ntuples : training samples for the Particle Transformer |
| 2 | [UParT-training](https://gitlab.cern.ch/cbasile/b-hive/-/tree/bstautau_edge_features?ref_type=heads) | CMS training framework for Particle Transformer used as jet-tagger and mass regressor |
| 3 | [BsTauTau_ntuplizer](https://github.com/bstautau-ttbar/BsTauTau_ntuplizer) | miniAOD → nanoAOD ntuplizer UParT models inference and nanoAOD skimmer with (lose) ttbar preselection |
| 4 | [bstautau-analyzer](https://github.com/bstautau-ttbar/bstautau-analyzer) | Main analysis code on skimmed nanoAOD|
| 5 | [combine-analysis](https://github.com/bstautau-ttbar/combine-analysis) | Statistical analysis based on COMBINE framework|

## Data

Run 2 + Run 3, ttbar processes.
