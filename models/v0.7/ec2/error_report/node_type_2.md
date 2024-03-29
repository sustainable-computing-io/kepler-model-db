# Validation results on node type 2

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| i3en.metal | 96 | 2 | -1 | -1 |

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
| BPFOnly | SGDRegressorTrainer_2 | 0.44 | 24.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/SGDRegressorTrainer_2.json |
| Basic | SGDRegressorTrainer_2 | 5.61 | 44.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/SGDRegressorTrainer_2.json |
| BPFIRQ | SGDRegressorTrainer_2 | 0.80 | 23.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/SGDRegressorTrainer_2.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_2 | 0.32 | 67.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/SGDRegressorTrainer_2.json |
| BPFIRQ | SGDRegressorTrainer_2 | 0.81 | 68.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/SGDRegressorTrainer_2.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_2 | 3.22 | 13.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/PolynomialRegressionTrainer_2.zip |
| BPFOnly | PolynomialRegressionTrainer_2 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/PolynomialRegressionTrainer_2.zip |
| CounterIRQCombined | PolynomialRegressionTrainer_2 | 2.94 | 15.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/PolynomialRegressionTrainer_2.zip |
| Basic | PolynomialRegressionTrainer_2 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/PolynomialRegressionTrainer_2.zip |
| BPFIRQ | PolynomialRegressionTrainer_2 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/PolynomialRegressionTrainer_2.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | PolynomialRegressionTrainer_2 | 3.59 | 29.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/PolynomialRegressionTrainer_2.zip |
| BPFOnly | PolynomialRegressionTrainer_2 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/PolynomialRegressionTrainer_2.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_2 | 3.16 | 22.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_2.zip |
| Basic | PolynomialRegressionTrainer_2 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/PolynomialRegressionTrainer_2.zip |
| BPFIRQ | PolynomialRegressionTrainer_2 | 0.00 | 0.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/PolynomialRegressionTrainer_2.zip |
