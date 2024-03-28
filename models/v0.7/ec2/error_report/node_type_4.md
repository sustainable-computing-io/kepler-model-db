# Validation results on node type 4

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| i3.metal | 72 | 2 | -1 | -1 |

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
| CounterOnly | SGDRegressorTrainer_4 | 4.43 | 5.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/SGDRegressorTrainer_4.json |
| CgroupOnly | ExponentialRegressionTrainer_4 | 55.75 | 17.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/ExponentialRegressionTrainer_4.json |
| BPFOnly | LogarithmicRegressionTrainer_4 | 13.46 | 16.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LogarithmicRegressionTrainer_4.json |
| CounterIRQCombined | SGDRegressorTrainer_4 | 4.71 | 5.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/SGDRegressorTrainer_4.json |
| Basic | SGDRegressorTrainer_4 | 4.11 | 5.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/SGDRegressorTrainer_4.json |
| BPFIRQ | LogarithmicRegressionTrainer_4 | 14.39 | 16.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_4.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | SGDRegressorTrainer_4 | 3.96 | 7.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/SGDRegressorTrainer_4.json |
| CounterIRQCombined | SGDRegressorTrainer_4 | 4.30 | 11.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/SGDRegressorTrainer_4.json |
| Basic | SGDRegressorTrainer_4 | 3.92 | 10.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/SGDRegressorTrainer_4.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | XgboostFitTrainer_4 | 2.31 | 1.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/XgboostFitTrainer_4.zip |
| CgroupOnly | XgboostFitTrainer_4 | 51.94 | 18.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/XgboostFitTrainer_4.zip |
| BPFOnly | XgboostFitTrainer_4 | 5.04 | 9.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/XgboostFitTrainer_4.zip |
| CounterIRQCombined | XgboostFitTrainer_4 | 2.28 | 1.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/XgboostFitTrainer_4.zip |
| Basic | GradientBoostingRegressorTrainer_4 | 2.15 | 1.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/GradientBoostingRegressorTrainer_4.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_4 | 4.92 | 9.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_4.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | KNeighborsRegressorTrainer_4 | 2.32 | 2.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/KNeighborsRegressorTrainer_4.zip |
| CgroupOnly | SVRRegressorTrainer_4 | 57.06 | 14.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CgroupOnly/SVRRegressorTrainer_4.zip |
| BPFOnly | GradientBoostingRegressorTrainer_4 | 4.30 | 18.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/GradientBoostingRegressorTrainer_4.zip |
| CounterIRQCombined | XgboostFitTrainer_4 | 2.01 | 3.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/XgboostFitTrainer_4.zip |
| Basic | XgboostFitTrainer_4 | 1.99 | 4.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/XgboostFitTrainer_4.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_4 | 4.37 | 18.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/GradientBoostingRegressorTrainer_4.zip |
