
# Pipeline ec2 

## Description

Use [kepler-model-traing-playbook](https://github.com/sustainable-computing-io/kepler-model-training-playbook) to collect power data from EC2 spot instance

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

  - stress
    - CPU (cpu)
