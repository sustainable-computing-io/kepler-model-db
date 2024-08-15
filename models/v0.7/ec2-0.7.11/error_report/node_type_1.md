# Validation results on node type 1

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_e5_2686v4 | 72 | 2 | 503 | 3000 |

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
| CounterOnly | LogarithmicRegressionTrainer_1 | 12.01 | 6.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/LogarithmicRegressionTrainer_1.json |
| BPFOnly | LogarithmicRegressionTrainer_1 | 5.76 | 15.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/LogarithmicRegressionTrainer_1.json |
| CounterIRQCombined | LogarithmicRegressionTrainer_1 | 6.88 | 6.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/LogarithmicRegressionTrainer_1.json |
| Basic | LogarithmicRegressionTrainer_1 | 6.44 | 7.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/LogarithmicRegressionTrainer_1.json |
| BPFIRQ | LogarithmicRegressionTrainer_1 | 8.62 | 18.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_1.json |
### rapl-sysfs DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | LogarithmicRegressionTrainer_1 | 6.43 | 20.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterOnly/LogarithmicRegressionTrainer_1.json |
| CounterIRQCombined | LogarithmicRegressionTrainer_1 | 4.43 | 33.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterIRQCombined/LogarithmicRegressionTrainer_1.json |
| Basic | LogarithmicRegressionTrainer_1 | 11.20 | 19.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/Basic/LogarithmicRegressionTrainer_1.json |
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
| CounterOnly | XgboostFitTrainer_1 | 1.51 | 4.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterOnly/XgboostFitTrainer_1.zip |
| BPFOnly | KNeighborsRegressorTrainer_1 | 2.58 | 4.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFOnly/KNeighborsRegressorTrainer_1.zip |
| CounterIRQCombined | PolynomialRegressionTrainer_1 | 3.31 | 2.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/CounterIRQCombined/PolynomialRegressionTrainer_1.zip |
| Basic | GradientBoostingRegressorTrainer_1 | 2.21 | 5.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/Basic/GradientBoostingRegressorTrainer_1.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 4.85 | 1.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
### rapl-sysfs DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_1 | 4.58 | 11.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterOnly/PolynomialRegressionTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 3.04 | 15.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | LogarithmicRegressionTrainer_1 | 4.43 | 33.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/CounterIRQCombined/LogarithmicRegressionTrainer_1.zip |
| Basic | PolynomialRegressionTrainer_1 | 2.00 | 70.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/Basic/PolynomialRegressionTrainer_1.zip |
| BPFIRQ | XgboostFitTrainer_1 | 3.34 | 13.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2-0.7.11/rapl-sysfs/DynPower/BPFIRQ/XgboostFitTrainer_1.zip |
### redfish AbsPower model

No model available

### redfish DynPower model

No model available

### trained_power_model AbsPower model

No model available

### trained_power_model DynPower model

No model available

