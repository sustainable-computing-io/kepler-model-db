# Validation results on node type 128

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_x5670 | 12.0 | 2.0 | 24.0 | 2900.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_128 | 3.44 | 1.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/ExponentialRegressionTrainer_128.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_128 | 1.05 | 1.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LogisticRegressionTrainer_128.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_128 | 3.44 | 1.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/ExponentialRegressionTrainer_128.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_128 | 1.05 | 1.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LogisticRegressionTrainer_128.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

