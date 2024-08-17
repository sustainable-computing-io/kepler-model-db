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

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | SGDRegressorTrainer_1 | 3.08 | 10.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/SGDRegressorTrainer_1.json |
| CgroupOnly | LogarithmicRegressionTrainer_1 | 56.58 | 16.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/LogarithmicRegressionTrainer_1.json |
| BPFOnly | LogarithmicRegressionTrainer_1 | 8.29 | 15.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LogarithmicRegressionTrainer_1.json |
| CounterIRQCombined | LogarithmicRegressionTrainer_1 | 4.62 | 11.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/LogarithmicRegressionTrainer_1.json |
| Basic | SGDRegressorTrainer_1 | 2.58 | 13.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/SGDRegressorTrainer_1.json |
| BPFIRQ | LogarithmicRegressionTrainer_1 | 8.56 | 15.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_1.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | LogarithmicRegressionTrainer_1 | 2.38 | 81.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/LogarithmicRegressionTrainer_1.json |
| CounterIRQCombined | LogarithmicRegressionTrainer_1 | 4.46 | 28.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/LogarithmicRegressionTrainer_1.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | SGDRegressorTrainer_1 | 3.08 | 10.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/SGDRegressorTrainer_1.zip |
| CgroupOnly | GradientBoostingRegressorTrainer_1 | 51.18 | 18.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | XgboostFitTrainer_1 | 4.02 | 3.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/XgboostFitTrainer_1.zip |
| CounterIRQCombined | LinearRegressionTrainer_1 | 3.07 | 8.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/LinearRegressionTrainer_1.zip |
| Basic | XgboostFitTrainer_1 | 1.42 | 4.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/XgboostFitTrainer_1.zip |
| BPFIRQ | LogarithmicRegressionTrainer_1 | 8.56 | 15.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_1.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | XgboostFitTrainer_1 | 2.05 | 20.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/XgboostFitTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 6.47 | 6.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | LinearRegressionTrainer_1 | 2.82 | 75.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/LinearRegressionTrainer_1.zip |
| Basic | KNeighborsRegressorTrainer_1 | 2.00 | 35.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/KNeighborsRegressorTrainer_1.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 1.85 | 56.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
