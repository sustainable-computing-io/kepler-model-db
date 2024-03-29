# Validation results on node type 1

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| c5d.metal | 96 | 2 | -1 | -1 |

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
| BPFOnly | SGDRegressorTrainer_1 | 0.40 | 30.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/SGDRegressorTrainer_1.json |
| BPFIRQ | SGDRegressorTrainer_1 | 0.80 | 24.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/SGDRegressorTrainer_1.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_1 | 0.32 | 56.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/SGDRegressorTrainer_1.json |
| BPFIRQ | SGDRegressorTrainer_1 | 0.57 | 54.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/SGDRegressorTrainer_1.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_1 | 4.30 | 41.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/PolynomialRegressionTrainer_1.zip |
| BPFOnly | LinearRegressionTrainer_1 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LinearRegressionTrainer_1.zip |
| CounterIRQCombined | PolynomialRegressionTrainer_1 | 3.07 | 15.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/PolynomialRegressionTrainer_1.zip |
| Basic | LinearRegressionTrainer_1 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/LinearRegressionTrainer_1.zip |
| BPFIRQ | LinearRegressionTrainer_1 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LinearRegressionTrainer_1.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_1 | 3.26 | 24.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/PolynomialRegressionTrainer_1.zip |
| BPFOnly | LinearRegressionTrainer_1 | 0.00 | 0.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/LinearRegressionTrainer_1.zip |
| CounterIRQCombined | PolynomialRegressionTrainer_1 | 2.82 | 25.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/PolynomialRegressionTrainer_1.zip |
| Basic | LinearRegressionTrainer_1 | 0.00 | 0.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/LinearRegressionTrainer_1.zip |
| BPFIRQ | LinearRegressionTrainer_1 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/LinearRegressionTrainer_1.zip |
