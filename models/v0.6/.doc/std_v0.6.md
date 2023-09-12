# Pipeline std_v0.6

## Description

This pipeline is introduced as an intial pipeline for the first release of kepler-model-server which is align with Kepler release v0.6.

## Components

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

### stressng
- stress
    - CPU (cpu) 
    - branch to 1024 randomly selected locations and hence exercise (branch)  
    - cyclic nanosecond sleeps (cyclic) 
    - exercising CPU generic registers (regs)
    - CPU level 1 cache with reads and writes (l1cache)
    - CPU cache with random wide spread memory read and writes to thrash the CPU cache (cache)
    - "Sustainable Memory Bandwidth in High Performance Computers" benchmarking tool by John D. McCalpin (stream)
    - virtual memory (vm-rw) 16G
    - mix of sequential, random and memory mapped read/write operations (iomix)
    - pipe write operations (pipe)
    - network performing SCTP send/receives (sctp)
- n = 4, 8, 15*, 32 where *max CPU cores in baselineMachine is 15
- Max CPU frequency = 2GHz, 2.8GHz, 3.6GHz
