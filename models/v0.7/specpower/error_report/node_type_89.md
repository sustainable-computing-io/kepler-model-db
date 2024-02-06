# Validation results on node type 89

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| Ampere_Altra_Max_M128_30 | 256.0 | 2.0 | 256.0 | 3000.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_89 | 36.92 | 12.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/LogarithmicRegressionTrainer_89.json |
### acpi DynPower model

No model available

### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | KNeighborsRegressorTrainer_89 | 28.17 | 13.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/KNeighborsRegressorTrainer_89.zip |
### acpi DynPower model

No model available

### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

