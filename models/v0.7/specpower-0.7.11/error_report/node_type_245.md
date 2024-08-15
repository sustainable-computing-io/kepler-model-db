# Validation results on node type 245

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| amd_epyc_7601_dell_sku | 64.0 | 2.0 | 128.0 | 2200.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_245 | 2.58 | 1.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/LogarithmicRegressionTrainer_245.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogarithmicRegressionTrainer_245 | 2.09 | 2.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/LogarithmicRegressionTrainer_245.json |
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
| BPFOnly | LogarithmicRegressionTrainer_245 | 2.58 | 1.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/LogarithmicRegressionTrainer_245.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LinearRegressionTrainer_245 | 1.85 | 1.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/LinearRegressionTrainer_245.zip |
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

