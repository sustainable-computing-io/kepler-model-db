# Validation results on node type 295

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8180 | 112.0 | 4.0 | 192.0 | 2500.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_295 | 27.04 | 4.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_295.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_295 | 23.83 | 9.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LogisticRegressionTrainer_295.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | GradientBoostingRegressorTrainer_295 | 17.80 | 4.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_295.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | GradientBoostingRegressorTrainer_295 | 12.86 | 4.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/GradientBoostingRegressorTrainer_295.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

