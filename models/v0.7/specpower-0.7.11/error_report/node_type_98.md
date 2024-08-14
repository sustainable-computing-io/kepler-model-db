# Validation results on node type 98

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_x3480 | 4.0 | 1.0 | 8.0 | 3100.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_98 | 4.73 | 6.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/SGDRegressorTrainer_98.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_98 | 2.97 | 19.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_98.json |
### hmc AbsPower model

No model available

### hmc DynPower model

No model available

### rapl-msr AbsPower model

No model available

### rapl-msr DynPower model

No model available

### rapl-sysfs AbsPower model

No model available

### rapl-sysfs DynPower model

No model available

### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | KNeighborsRegressorTrainer_98 | 4.12 | 6.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/KNeighborsRegressorTrainer_98.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | ExponentialRegressionTrainer_98 | 2.97 | 19.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/ExponentialRegressionTrainer_98.zip |
### hmc AbsPower model

No model available

### hmc DynPower model

No model available

### rapl-msr AbsPower model

No model available

### rapl-msr DynPower model

No model available

### rapl-sysfs AbsPower model

No model available

### rapl-sysfs DynPower model

No model available

### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

