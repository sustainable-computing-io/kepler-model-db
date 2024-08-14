# Validation results on node type 311

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| amd_epyc_7773x | 64.0 | 1.0 | 128.0 | 2200.0 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_311 | 7.19 | 3.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_311.json |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_311 | 3.08 | 3.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/LogisticRegressionTrainer_311.json |
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
| BPFOnly | LogisticRegressionTrainer_311 | 7.19 | 3.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/AbsPower/BPFOnly/LogisticRegressionTrainer_311.zip |
### acpi DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | LogisticRegressionTrainer_311 | 3.08 | 3.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/specpower-0.7.11/acpi/DynPower/BPFOnly/LogisticRegressionTrainer_311.zip |
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

