# Validation results on node type 230

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8276l | 56.0 | 2.0 | 192.0 | 2200.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_230 | 9.36 | 5.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_230.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_230 | 13.82 | 7.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_230.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | GradientBoostingRegressorTrainer_230 | 6.28 | 7.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_230.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | XgboostFitTrainer_230 | 8.92 | 13.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/XgboostFitTrainer_230.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

