# Validation results on node type 3

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8259cl | 96 | 2 | 755 | 3500 |

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
| CounterOnly | SGDRegressorTrainer_3 | 10.72 | 3.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/SGDRegressorTrainer_3.json |
| BPFOnly | SGDRegressorTrainer_3 | 59.64 | 17.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/SGDRegressorTrainer_3.json |
| CounterIRQCombined | SGDRegressorTrainer_3 | 16.23 | 4.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/SGDRegressorTrainer_3.json |
| Basic | SGDRegressorTrainer_3 | 11.31 | 4.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/SGDRegressorTrainer_3.json |
| BPFIRQ | SGDRegressorTrainer_3 | 67.67 | 12.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/SGDRegressorTrainer_3.json |
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
| CounterOnly | XgboostFitTrainer_3 | 4.25 | 0.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/XgboostFitTrainer_3.zip |
| BPFOnly | GradientBoostingRegressorTrainer_3 | 19.37 | 5.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_3.zip |
| CounterIRQCombined | XgboostFitTrainer_3 | 4.61 | 1.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/XgboostFitTrainer_3.zip |
| Basic | PolynomialRegressionTrainer_3 | 8.54 | 3.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/PolynomialRegressionTrainer_3.zip |
| BPFIRQ | XgboostFitTrainer_3 | 26.38 | 6.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/XgboostFitTrainer_3.zip |
### rapl-sysfs DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | KNeighborsRegressorTrainer_3 | 8.05 | 74.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterOnly/KNeighborsRegressorTrainer_3.zip |
| CounterIRQCombined | PolynomialRegressionTrainer_3 | 8.41 | 68.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterIRQCombined/PolynomialRegressionTrainer_3.zip |
| Basic | GradientBoostingRegressorTrainer_3 | 3.53 | 25.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/Basic/GradientBoostingRegressorTrainer_3.zip |
### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

