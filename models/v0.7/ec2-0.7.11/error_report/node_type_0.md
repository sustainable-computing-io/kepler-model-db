# Validation results on node type 0

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8259cl | 96 | 2 | 377 | 3500 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### hmc AbsPower model

No model available

### hmc DynPower model

No model available

### rapl-msr AbsPower model

No model available

### rapl-msr DynPower model

No model available

### rapl-sysfs AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | SGDRegressorTrainer_0 | 13.10 | 5.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/SGDRegressorTrainer_0.json |
| BPFOnly | LogarithmicRegressionTrainer_0 | 42.54 | 18.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/LogarithmicRegressionTrainer_0.json |
| CounterIRQCombined | SGDRegressorTrainer_0 | 14.23 | 4.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/SGDRegressorTrainer_0.json |
| Basic | SGDRegressorTrainer_0 | 17.27 | 3.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/SGDRegressorTrainer_0.json |
| BPFIRQ | SGDRegressorTrainer_0 | 71.18 | 15.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/SGDRegressorTrainer_0.json |
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

No model available

### acpi DynPower model

No model available

### hmc AbsPower model

No model available

### hmc DynPower model

No model available

### rapl-msr AbsPower model

No model available

### rapl-msr DynPower model

No model available

### rapl-sysfs AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | GradientBoostingRegressorTrainer_0 | 4.23 | 1.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/GradientBoostingRegressorTrainer_0.zip |
| BPFOnly | KNeighborsRegressorTrainer_0 | 33.82 | 6.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/KNeighborsRegressorTrainer_0.zip |
| CounterIRQCombined | KNeighborsRegressorTrainer_0 | 5.27 | 4.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/KNeighborsRegressorTrainer_0.zip |
| Basic | XgboostFitTrainer_0 | 4.50 | 2.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/XgboostFitTrainer_0.zip |
| BPFIRQ | XgboostFitTrainer_0 | 17.21 | 4.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/XgboostFitTrainer_0.zip |
### rapl-sysfs DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | XgboostFitTrainer_0 | 3.75 | 19.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterOnly/XgboostFitTrainer_0.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_0 | 5.44 | 14.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_0.zip |
| Basic | XgboostFitTrainer_0 | 3.69 | 17.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/Basic/XgboostFitTrainer_0.zip |
### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

