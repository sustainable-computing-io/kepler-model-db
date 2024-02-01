# Validation results on node type 146

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| Intel_Xeon_Platinum_8280 | 112.0 | 4.0 | 192.0 | 2700.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

No model available

### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_146 | 19.47 | 3.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/SGDRegressorTrainer_146.json |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | KNeighborsRegressorTrainer_146 | 16.89 | 4.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/AbsPower/BPFOnly/KNeighborsRegressorTrainer_146.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_146 | 19.47 | 3.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower/acpi/DynPower/BPFOnly/SGDRegressorTrainer_146.zip |
### intel_rapl AbsPower model

No model available

### intel_rapl DynPower model

No model available

