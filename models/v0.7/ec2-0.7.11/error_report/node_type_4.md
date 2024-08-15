# Validation results on node type 4

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8252c | 48 | 2 | 188 | 4500 |

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
| CounterOnly | SGDRegressorTrainer_4 | 26.95 | 5.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/SGDRegressorTrainer_4.json |
| BPFOnly | LogarithmicRegressionTrainer_4 | 60.73 | 11.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/LogarithmicRegressionTrainer_4.json |
| CounterIRQCombined | SGDRegressorTrainer_4 | 28.33 | 5.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/SGDRegressorTrainer_4.json |
| Basic | SGDRegressorTrainer_4 | 21.00 | 4.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/SGDRegressorTrainer_4.json |
| BPFIRQ | ExponentialRegressionTrainer_4 | 92.82 | 14.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/ExponentialRegressionTrainer_4.json |
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
| CounterOnly | PolynomialRegressionTrainer_4 | 4.85 | 0.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/PolynomialRegressionTrainer_4.zip |
| BPFOnly | XgboostFitTrainer_4 | 39.04 | 2.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/XgboostFitTrainer_4.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_4 | 3.54 | 2.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_4.zip |
| Basic | GradientBoostingRegressorTrainer_4 | 1.68 | 2.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/GradientBoostingRegressorTrainer_4.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_4 | 12.08 | 4.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_4.zip |
### rapl-sysfs DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_4 | 5.04 | 3.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterOnly/PolynomialRegressionTrainer_4.zip |
| BPFOnly | GradientBoostingRegressorTrainer_4 | 28.32 | 11.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/BPFOnly/GradientBoostingRegressorTrainer_4.zip |
| CounterIRQCombined | KNeighborsRegressorTrainer_4 | 5.02 | 8.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterIRQCombined/KNeighborsRegressorTrainer_4.zip |
| Basic | PolynomialRegressionTrainer_4 | 4.23 | 6.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/Basic/PolynomialRegressionTrainer_4.zip |
### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

