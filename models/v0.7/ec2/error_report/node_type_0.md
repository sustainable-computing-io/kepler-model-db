# Validation results on node type 0

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

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | SGDRegressorTrainer_0 | 13.79 | 3.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/SGDRegressorTrainer_0.json |
| BPFOnly | LogarithmicRegressionTrainer_0 | 43.63 | 16.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LogarithmicRegressionTrainer_0.json |
| CounterIRQCombined | SGDRegressorTrainer_0 | 9.46 | 3.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/SGDRegressorTrainer_0.json |
| Basic | SGDRegressorTrainer_0 | 11.00 | 1.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/SGDRegressorTrainer_0.json |
| BPFIRQ | LogarithmicRegressionTrainer_0 | 47.40 | 11.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_0.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterIRQCombined | SGDRegressorTrainer_0 | 9.72 | 9.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/SGDRegressorTrainer_0.json |
| Basic | SGDRegressorTrainer_0 | 11.02 | 8.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/SGDRegressorTrainer_0.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | GradientBoostingRegressorTrainer_0 | 3.80 | 1.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/GradientBoostingRegressorTrainer_0.zip |
| BPFOnly | XgboostFitTrainer_0 | 6.82 | 2.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/XgboostFitTrainer_0.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_0 | 4.93 | 0.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_0.zip |
| Basic | XgboostFitTrainer_0 | 5.92 | 1.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/XgboostFitTrainer_0.zip |
| BPFIRQ | XgboostFitTrainer_0 | 16.09 | 4.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/XgboostFitTrainer_0.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | GradientBoostingRegressorTrainer_0 | 2.85 | 4.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/GradientBoostingRegressorTrainer_0.zip |
| BPFOnly | GradientBoostingRegressorTrainer_0 | 14.37 | 7.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/GradientBoostingRegressorTrainer_0.zip |
| CounterIRQCombined | XgboostFitTrainer_0 | 2.63 | 19.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/XgboostFitTrainer_0.zip |
| Basic | GradientBoostingRegressorTrainer_0 | 4.30 | 3.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/GradientBoostingRegressorTrainer_0.zip |
| BPFIRQ | XgboostFitTrainer_0 | 18.12 | 5.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/XgboostFitTrainer_0.zip |
