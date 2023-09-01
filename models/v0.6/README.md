# Pre-release Build

The pipeline in this folder is trained by Kepler model server towards v0.6.

## Pipeline information

- **Extractor:** DefaultExtractor
- **Isolator:** MinIsolator
- **Trainers:**
    - SGDRegressorTrainer
    - SVRRegressorTrainer
    - KNeighborsRegressorTrainer
    - LinearRegressionTrainer
    - GradientBoostingRegressorTrainer
    - Model PolynomialRegressionTrainer

## Workload information

- stressng
- coremark
    ```yaml
        repetition: 5
        iterationSpec:
            iterations:
            - name: thread
            values:
            - "4"
            - "8"
            - "16"
            - "32"
    ```
- parsec
    ```yaml
        repetition: 1
        interval: 10
        iterationSpec:
            iterations:
            - name: input
            values:
            - "native"
            - name: package
            values:
            - "bodytrack"
            - "canneal"
            - "raytrace"
            - "ferret"
    ```

## Trained pipelines

Machine ID|raw data|trained pipeline|collect time|last update time
---|---|---|---|---
nx12|&check;|&check;|