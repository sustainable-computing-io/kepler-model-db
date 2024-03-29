# Validation results on node type 0

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| m5zn.metal | 48 | 2 | -1 | -1 |

[With local estimator](#with-local-estimator)

[With sidecar estimator](#with-sidecar-estimator)

## With local estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | SGDRegressorTrainer_0 | 13.15 | 5.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/SGDRegressorTrainer_0.json |
| BPFOnly | LogarithmicRegressionTrainer_0 | 31.17 | 11.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LogarithmicRegressionTrainer_0.json |
| CounterIRQCombined | SGDRegressorTrainer_0 | 15.06 | 6.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/SGDRegressorTrainer_0.json |
| Basic | SGDRegressorTrainer_0 | 8.53 | 4.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/SGDRegressorTrainer_0.json |
| BPFIRQ | LogarithmicRegressionTrainer_0 | 48.22 | 13.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_0.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| Basic | SGDRegressorTrainer_0 | 11.10 | 13.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/SGDRegressorTrainer_0.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | KNeighborsRegressorTrainer_0 | 6.95 | 1.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/KNeighborsRegressorTrainer_0.zip |
| CgroupOnly | SVRRegressorTrainer_0 | 95.91 | 19.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/SVRRegressorTrainer_0.zip |
| BPFOnly | GradientBoostingRegressorTrainer_0 | 25.00 | 6.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_0.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_0 | 3.95 | 0.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_0.zip |
| Basic | XgboostFitTrainer_0 | 4.05 | 1.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/XgboostFitTrainer_0.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_0 | 14.99 | 5.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_0.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_0 | 4.05 | 14.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/PolynomialRegressionTrainer_0.zip |
| BPFOnly | XgboostFitTrainer_0 | 46.97 | 18.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/XgboostFitTrainer_0.zip |
| CounterIRQCombined | LinearRegressionTrainer_0 | 3.96 | 65.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/LinearRegressionTrainer_0.zip |
| Basic | LinearRegressionTrainer_0 | 2.47 | 22.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/LinearRegressionTrainer_0.zip |
