# Validation results on node type 308

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8280 | 28.0 | 1.0 | 48.0 | 2700.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_308 | 7.03 | 3.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/ExponentialRegressionTrainer_308.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_308 | 3.32 | 6.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LogarithmicRegressionTrainer_308.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LinearRegressionTrainer_308 | 4.82 | 7.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LinearRegressionTrainer_308.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_308 | 3.32 | 6.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LogarithmicRegressionTrainer_308.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

