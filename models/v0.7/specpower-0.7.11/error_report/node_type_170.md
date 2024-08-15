# Validation results on node type 170

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_x5650 | 12.0 | 2.0 | 24.0 | 2700.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_170 | 4.25 | 2.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/SGDRegressorTrainer_170.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_170 | 2.77 | 2.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/LogarithmicRegressionTrainer_170.json |
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
| BPFOnly | LinearRegressionTrainer_170 | 1.91 | 0.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/LinearRegressionTrainer_170.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_170 | 2.77 | 2.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/LogarithmicRegressionTrainer_170.zip |
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

