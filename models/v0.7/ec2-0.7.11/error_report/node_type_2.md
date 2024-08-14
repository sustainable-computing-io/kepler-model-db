# Validation results on node type 2

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8275cl | 96 | 2 | 188 | 3900 |

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
| CounterOnly | SGDRegressorTrainer_2 | 21.99 | 4.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/SGDRegressorTrainer_2.json |
| BPFOnly | LogarithmicRegressionTrainer_2 | 64.46 | 20.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/LogarithmicRegressionTrainer_2.json |
| CounterIRQCombined | SGDRegressorTrainer_2 | 18.57 | 3.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/SGDRegressorTrainer_2.json |
| Basic | SGDRegressorTrainer_2 | 23.95 | 4.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/SGDRegressorTrainer_2.json |
| BPFIRQ | LogarithmicRegressionTrainer_2 | 58.10 | 15.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_2.json |
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
| CounterOnly | KNeighborsRegressorTrainer_2 | 6.88 | 2.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/KNeighborsRegressorTrainer_2.zip |
| BPFOnly | GradientBoostingRegressorTrainer_2 | 14.83 | 2.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_2.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_2 | 4.01 | 1.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_2.zip |
| Basic | XgboostFitTrainer_2 | 4.35 | 1.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/XgboostFitTrainer_2.zip |
| BPFIRQ | XgboostFitTrainer_2 | 19.82 | 5.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/XgboostFitTrainer_2.zip |
### rapl-sysfs DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | KNeighborsRegressorTrainer_2 | 8.38 | 17.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterOnly/KNeighborsRegressorTrainer_2.zip |
| BPFOnly | GradientBoostingRegressorTrainer_2 | 37.26 | 15.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/BPFOnly/GradientBoostingRegressorTrainer_2.zip |
| CounterIRQCombined | KNeighborsRegressorTrainer_2 | 8.59 | 17.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterIRQCombined/KNeighborsRegressorTrainer_2.zip |
| Basic | GradientBoostingRegressorTrainer_2 | 6.05 | 70.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/Basic/GradientBoostingRegressorTrainer_2.zip |
| BPFIRQ | KNeighborsRegressorTrainer_2 | 37.55 | 16.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/BPFIRQ/KNeighborsRegressorTrainer_2.zip |
### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

