# Validation results on node type 3

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| m7i.metal-24xl | 96 | 2 | -1 | -1 |

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
| BPFOnly | SGDRegressorTrainer_3 | 0.37 | 31.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/SGDRegressorTrainer_3.json |
| BPFIRQ | SGDRegressorTrainer_3 | 0.75 | 24.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/SGDRegressorTrainer_3.json |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| BPFOnly | SGDRegressorTrainer_3 | 0.33 | 85.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/SGDRegressorTrainer_3.json |
## With sidecar estimator

### acpi AbsPower model

No model available

### acpi DynPower model

No model available

### intel_rapl AbsPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | GradientBoostingRegressorTrainer_3 | 5.20 | 15.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/GradientBoostingRegressorTrainer_3.zip |
| BPFOnly | PolynomialRegressionTrainer_3 | 0.00 | 0.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/PolynomialRegressionTrainer_3.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_3 | 2.93 | 27.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_3.zip |
| Basic | PolynomialRegressionTrainer_3 | 0.00 | 0.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/PolynomialRegressionTrainer_3.zip |
| BPFIRQ | PolynomialRegressionTrainer_3 | 0.00 | 1.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/PolynomialRegressionTrainer_3.zip |
### intel_rapl DynPower model

| Feature group | Model name | MAE | MAPE (%) | URL |
| --- | --- | --- | --- | --- |
| CounterOnly | GradientBoostingRegressorTrainer_3 | 5.18 | 22.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterOnly/GradientBoostingRegressorTrainer_3.zip |
| BPFOnly | PolynomialRegressionTrainer_3 | 0.00 | 0.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFOnly/PolynomialRegressionTrainer_3.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_3 | 7.21 | 30.7 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_3.zip |
| Basic | PolynomialRegressionTrainer_3 | 0.00 | 0.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/Basic/PolynomialRegressionTrainer_3.zip |
| BPFIRQ | PolynomialRegressionTrainer_3 | 0.00 | 0.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/DynPower/BPFIRQ/PolynomialRegressionTrainer_3.zip |
