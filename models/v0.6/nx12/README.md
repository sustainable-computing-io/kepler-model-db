# Validation results

## With local estimator

### rapl AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 21.99 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 23.09 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFOnly/SGDRegressorTrainer_1.json |
### rapl DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 23.48 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 23.87 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFOnly/SGDRegressorTrainer_1.json |
### acpi AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 29.45 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 32.73 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFOnly/SGDRegressorTrainer_1.json |
### acpi DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 31.12 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 32.37 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFOnly/SGDRegressorTrainer_1.json |
## With sidecar estimator

### rapl AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 12.49 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | KNeighborsRegressorTrainer_1 | 11.63 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFOnly/KNeighborsRegressorTrainer_1.zip |
| Basic | GradientBoostingRegressorTrainer_1 | 4.07 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/Basic/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 5.01 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | GradientBoostingRegressorTrainer_1 | 4.68 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/CounterOnly/GradientBoostingRegressorTrainer_1.zip |
| KubeletOnly | GradientBoostingRegressorTrainer_1 | 32.80 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/KubeletOnly/GradientBoostingRegressorTrainer_1.zip |
### rapl DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 12.39 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 11.58 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| Basic | GradientBoostingRegressorTrainer_1 | 3.65 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/Basic/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 3.85 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | GradientBoostingRegressorTrainer_1 | 3.84 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/CounterOnly/GradientBoostingRegressorTrainer_1.zip |
| KubeletOnly | GradientBoostingRegressorTrainer_1 | 32.25 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/KubeletOnly/GradientBoostingRegressorTrainer_1.zip |
### acpi AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 18.90 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | KNeighborsRegressorTrainer_1 | 20.12 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFOnly/KNeighborsRegressorTrainer_1.zip |
| Basic | GradientBoostingRegressorTrainer_1 | 5.76 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/Basic/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 7.49 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | GradientBoostingRegressorTrainer_1 | 6.87 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/CounterOnly/GradientBoostingRegressorTrainer_1.zip |
### acpi DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 17.38 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 17.84 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| Basic | GradientBoostingRegressorTrainer_1 | 7.66 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/Basic/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 9.02 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | GradientBoostingRegressorTrainer_1 | 6.54 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/CounterOnly/GradientBoostingRegressorTrainer_1.zip |
