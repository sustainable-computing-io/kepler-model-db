# Validation results on node type 206

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| amd_epyc_8534p | 64.0 | 1.0 | 96.0 | 2300.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_206 | 8.78 | 6.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogarithmicRegressionTrainer_206.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_206 | 5.19 | 7.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_206.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_206 | 8.78 | 6.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogarithmicRegressionTrainer_206.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | GradientBoostingRegressorTrainer_206 | 0.97 | 1.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/GradientBoostingRegressorTrainer_206.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

