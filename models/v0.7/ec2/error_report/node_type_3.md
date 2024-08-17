# Validation results on node type 3

| processor | cores | chips | memory | frequency |
| --- | --- | --- | --- | --- |
| intel_xeon_platinum_8259cl | 96 | 2 | 377 | 3500 |

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
| CounterOnly | LogarithmicRegressionTrainer_3 | 16.61 | 13.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/LogarithmicRegressionTrainer_3.json |
| CgroupOnly | SGDRegressorTrainer_3 | 99.30 | 13.3 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/SGDRegressorTrainer_3.json |
| BPFOnly | LogarithmicRegressionTrainer_3 | 28.10 | 13.8 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/LogarithmicRegressionTrainer_3.json |
| CounterIRQCombined | LogarithmicRegressionTrainer_3 | 14.04 | 11.0 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/LogarithmicRegressionTrainer_3.json |
| Basic | LogarithmicRegressionTrainer_3 | 16.62 | 9.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/LogarithmicRegressionTrainer_3.json |
| BPFIRQ | LogarithmicRegressionTrainer_3 | 26.38 | 14.6 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/LogarithmicRegressionTrainer_3.json |
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
| CounterOnly | XgboostFitTrainer_3 | 3.16 | 0.4 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterOnly/XgboostFitTrainer_3.zip |
| CgroupOnly | SVRRegressorTrainer_3 | 97.67 | 16.5 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CgroupOnly/SVRRegressorTrainer_3.zip |
| BPFOnly | XgboostFitTrainer_3 | 10.15 | 0.9 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFOnly/XgboostFitTrainer_3.zip |
| CounterIRQCombined | PolynomialRegressionTrainer_3 | 5.31 | 1.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/CounterIRQCombined/PolynomialRegressionTrainer_3.zip |
| Basic | XgboostFitTrainer_3 | 6.36 | 1.2 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/Basic/XgboostFitTrainer_3.zip |
| BPFIRQ | GradientBoostingRegressorTrainer_3 | 7.26 | 2.1 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.7/ec2/intel_rapl/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_3.zip |
### intel_rapl DynPower model

No model available

