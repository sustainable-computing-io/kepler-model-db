# Validation results on node type 280

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_e3_1270 | 4.0 | 1.0 | 8.0 | 3400.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_280 | 1.69 | 2.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/ExponentialRegressionTrainer_280.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_280 | 1.82 | 5.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/SGDRegressorTrainer_280.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | GradientBoostingRegressorTrainer_280 | 0.27 | 0.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_280.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | GradientBoostingRegressorTrainer_280 | 0.27 | 0.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/GradientBoostingRegressorTrainer_280.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

