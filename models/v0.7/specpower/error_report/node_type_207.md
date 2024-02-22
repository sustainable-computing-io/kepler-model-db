# Validation results on node type 207

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| amd_epyc_8124p | 16.0 | 1.0 | 96.0 | 2400.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_207 | 0.54 | 0.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_207.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_207 | 0.33 | 0.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/LogisticRegressionTrainer_207.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_207 | 0.54 | 0.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_207.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | PolynomialRegressionTrainer_207 | 0.29 | 0.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/PolynomialRegressionTrainer_207.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

