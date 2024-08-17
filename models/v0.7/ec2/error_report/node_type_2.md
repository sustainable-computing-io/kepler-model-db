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

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | LogarithmicRegressionTrainer_2 | 23.27 | 11.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/LogarithmicRegressionTrainer_2.json |
| BPFOnly | LogarithmicRegressionTrainer_2 | 60.32 | 17.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LogarithmicRegressionTrainer_2.json |
| CounterIRQCombined | SGDRegressorTrainer_2 | 14.18 | 4.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/SGDRegressorTrainer_2.json |
| Basic | LogarithmicRegressionTrainer_2 | 16.32 | 10.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/LogarithmicRegressionTrainer_2.json |
| BPFIRQ | LogarithmicRegressionTrainer_2 | 42.44 | 15.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_2.json |
### intel_rapl DynPower model

No model available

## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | GradientBoostingRegressorTrainer_2 | 7.86 | 1.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/GradientBoostingRegressorTrainer_2.zip |
| BPFOnly | XgboostFitTrainer_2 | 32.39 | 2.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/XgboostFitTrainer_2.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_2 | 7.48 | 1.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_2.zip |
| Basic | XgboostFitTrainer_2 | 7.22 | 2.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/XgboostFitTrainer_2.zip |
| BPFIRQ | XgboostFitTrainer_2 | 24.32 | 2.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/XgboostFitTrainer_2.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | KNeighborsRegressorTrainer_2 | 7.63 | 13.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/KNeighborsRegressorTrainer_2.zip |
| BPFOnly | GradientBoostingRegressorTrainer_2 | 18.89 | 14.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/GradientBoostingRegressorTrainer_2.zip |
| Basic | KNeighborsRegressorTrainer_2 | 7.97 | 31.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/KNeighborsRegressorTrainer_2.zip |
| BPFIRQ | XgboostFitTrainer_2 | 23.32 | 9.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/XgboostFitTrainer_2.zip |
