
# Pipeline specpower 

## Description

Use [SPECPower](https://www.spec.org/benchmarks.html#power) ssj 2008 data to train a power model by converting power to platform_power (acpi source) and ssj_ops to CPU time based on reference cycle count.

## Components

- **Extractor:** default
- **Isolator:** min
- **AbsPower Trainers:**

  - PolynomialRegressionTrainer
  - GradientBoostingRegressorTrainer
  - SGDRegressorTrainer
  - KNeighborsRegressorTrainer
  - LinearRegressionTrainer
  - SVRRegressorTrainer
  - XgboostFitTrainer
  - LogarithmicRegressionTrainer
  - LogisticRegressionTrainer
  - ExponentialRegressionTrainer


- **DynPower Trainers:** 

  (same as AbsPower Trainers)

## Workload information


### SPECPower

<details>

https://www.spec.org/power_ssj2008/

</details>

        
    