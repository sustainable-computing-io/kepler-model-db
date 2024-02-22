# Validation results on node type 199

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_8592+ | 128.0 | 2.0 | 512.0 | 1900.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_199 | 40.84 | 8.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_199.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_199 | 23.52 | 6.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_199.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | PolynomialRegressionTrainer_199 | 20.37 | 5.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/PolynomialRegressionTrainer_199.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_199 | 23.52 | 6.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_199.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

