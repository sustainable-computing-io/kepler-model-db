# Validation results on node type 239

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8176 | 224.0 | 8.0 | 768.0 | 2100.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_239 | 13.88 | 1.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/ExponentialRegressionTrainer_239.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_239 | 62.57 | 13.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_239.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_239 | 13.88 | 1.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/ExponentialRegressionTrainer_239.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LinearRegressionTrainer_239 | 23.35 | 3.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LinearRegressionTrainer_239.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

