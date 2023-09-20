# Validation results

## With local estimator

### rapl AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 70.75 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 66.32 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFOnly/SGDRegressorTrainer_1.json |
| Basic | SGDRegressorTrainer_1 | 28.87 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/Basic/SGDRegressorTrainer_1.json |
| CounterIRQCombined | SGDRegressorTrainer_1 | 31.15 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/CounterIRQCombined/SGDRegressorTrainer_1.json |
| CounterOnly | SGDRegressorTrainer_1 | 28.54 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/CounterOnly/SGDRegressorTrainer_1.json |
| KubeletOnly | SGDRegressorTrainer_1 | 97.63 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/KubeletOnly/SGDRegressorTrainer_1.json |
### rapl DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 64.88 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 69.34 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFOnly/SGDRegressorTrainer_1.json |
| Basic | SGDRegressorTrainer_1 | 26.96 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/Basic/SGDRegressorTrainer_1.json |
| CounterIRQCombined | SGDRegressorTrainer_1 | 36.02 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/CounterIRQCombined/SGDRegressorTrainer_1.json |
| CounterOnly | SGDRegressorTrainer_1 | 26.70 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/CounterOnly/SGDRegressorTrainer_1.json |
### acpi AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 88.48 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 93.57 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFOnly/SGDRegressorTrainer_1.json |
| Basic | SGDRegressorTrainer_1 | 50.41 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/Basic/SGDRegressorTrainer_1.json |
| CounterIRQCombined | SGDRegressorTrainer_1 | 49.05 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/CounterIRQCombined/SGDRegressorTrainer_1.json |
| CounterOnly | SGDRegressorTrainer_1 | 46.93 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/CounterOnly/SGDRegressorTrainer_1.json |
### acpi DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | SGDRegressorTrainer_1 | 97.08 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFIRQ/SGDRegressorTrainer_1.json |
| BPFOnly | SGDRegressorTrainer_1 | 97.65 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFOnly/SGDRegressorTrainer_1.json |
| Basic | SGDRegressorTrainer_1 | 40.10 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/Basic/SGDRegressorTrainer_1.json |
| CounterIRQCombined | SGDRegressorTrainer_1 | 45.66 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/CounterIRQCombined/SGDRegressorTrainer_1.json |
| CounterOnly | SGDRegressorTrainer_1 | 42.57 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/CounterOnly/SGDRegressorTrainer_1.json |
## With sidecar estimator

### rapl AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 39.42 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 34.40 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| Basic | KNeighborsRegressorTrainer_1 | 11.19 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/Basic/KNeighborsRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 13.07 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | KNeighborsRegressorTrainer_1 | 8.97 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/CounterOnly/KNeighborsRegressorTrainer_1.zip |
| KubeletOnly | GradientBoostingRegressorTrainer_1 | 91.51 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/AbsPower/KubeletOnly/GradientBoostingRegressorTrainer_1.zip |
### rapl DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 35.64 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | KNeighborsRegressorTrainer_1 | 38.77 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/BPFOnly/KNeighborsRegressorTrainer_1.zip |
| Basic | KNeighborsRegressorTrainer_1 | 10.09 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/Basic/KNeighborsRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 13.49 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | KNeighborsRegressorTrainer_1 | 10.50 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/CounterOnly/KNeighborsRegressorTrainer_1.zip |
| KubeletOnly | GradientBoostingRegressorTrainer_1 | 94.88 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/rapl/DynPower/KubeletOnly/GradientBoostingRegressorTrainer_1.zip |
### acpi AbsPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 54.90 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 49.52 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| Basic | KNeighborsRegressorTrainer_1 | 15.48 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/Basic/KNeighborsRegressorTrainer_1.zip |
| CounterIRQCombined | KNeighborsRegressorTrainer_1 | 24.22 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/CounterIRQCombined/KNeighborsRegressorTrainer_1.zip |
| CounterOnly | KNeighborsRegressorTrainer_1 | 20.17 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/CounterOnly/KNeighborsRegressorTrainer_1.zip |
| KubeletOnly | KNeighborsRegressorTrainer_1 | 133.05 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/AbsPower/KubeletOnly/KNeighborsRegressorTrainer_1.zip |
### acpi DynPower model

| feature group | model name | mae | url |
| --- | --- | --- | --- |
| BPFIRQ | GradientBoostingRegressorTrainer_1 | 49.89 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFIRQ/GradientBoostingRegressorTrainer_1.zip |
| BPFOnly | GradientBoostingRegressorTrainer_1 | 55.99 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/BPFOnly/GradientBoostingRegressorTrainer_1.zip |
| Basic | GradientBoostingRegressorTrainer_1 | 19.75 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/Basic/GradientBoostingRegressorTrainer_1.zip |
| CounterIRQCombined | GradientBoostingRegressorTrainer_1 | 22.67 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/CounterIRQCombined/GradientBoostingRegressorTrainer_1.zip |
| CounterOnly | KNeighborsRegressorTrainer_1 | 17.60 | https://raw.githubusercontent.com/sustainable-computing-io/kepler-model-db/main/models/v0.6/nx12/std_v0.6/acpi/DynPower/CounterOnly/KNeighborsRegressorTrainer_1.zip |
