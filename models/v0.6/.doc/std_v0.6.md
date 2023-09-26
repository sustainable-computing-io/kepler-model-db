
# Pipeline std_v0.6 

## Description

This pipeline is introduced as an intial pipeline for the first release of kepler-model-server which is align with Kepler release v0.6.

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


- **DynPower Trainers:** 

  (same as AbsPower Trainers)

## Workload information


### stressng

- stress
    - CPU (cpu) 
    - branch to 1024 randomly selected locations and hence exercise (branch)  
    - exercising CPU generic registers (regs)
    - CPU level 1 cache with reads and writes (l1cache)
    - CPU cache with random wide spread memory read and writes to thrash the CPU cache (cache)
    - "Sustainable Memory Bandwidth in High Performance Computers" benchmarking tool by John D. McCalpin (stream)
    - virtual memory (vm-rw) 16G
    - network performing SCTP send/receives (sctp)
- n = 4, 8, 15*, 32, 40 where *max CPU cores in baselineMachine is 15
- Max CPU frequency = 2GHz, 2.8GHz, 3.6GHz


<details>

| stress |
| --- |
| none;sleep;none;none;none |
| 3600000;cpu;1;none;none |
| 3600000;cpu;2;none;none |
| 2000000;cpu;4;none;none |
| 2000000;cpu;8;none;none |
| 2000000;cpu;15;none;none |
| 2000000;cpu;24;none;none |
| 2000000;cpu;32;none;none |
| 2000000;cpu;40;none;none |
| 2800000;cpu;4;none;none |
| 2800000;cpu;8;none;none |
| 2800000;cpu;15;none;none |
| 2800000;cpu;24;none;none |
| 2800000;cpu;32;none;none |
| 2800000;cpu;40;none;none |
| 3600000;cpu;4;none;none |
| 3600000;cpu;8;none;none |
| 3600000;cpu;15;none;none |
| 3600000;cpu;24;none;none |
| 3600000;cpu;32;none;none |
| 3600000;cpu;40;none;none |
| 2000000;branch;4;none;none |
| 2000000;branch;8;none;none |
| 2000000;branch;15;none;none |
| 2000000;branch;24;none;none |
| 2000000;branch;32;none;none |
| 2000000;branch;40;none;none |
| 2800000;branch;4;none;none |
| 2800000;branch;8;none;none |
| 2800000;branch;15;none;none |
| 2800000;branch;24;none;none |
| 2800000;branch;32;none;none |
| 2800000;branch;40;none;none |
| 3600000;branch;4;none;none |
| 3600000;branch;8;none;none |
| 3600000;branch;15;none;none |
| 3600000;branch;24;none;none |
| 3600000;branch;32;none;none |
| 3600000;branch;40;none;none |
| 2000000;regs;4;none;none |
| 2000000;regs;8;none;none |
| 2000000;regs;15;none;none |
| 2000000;regs;24;none;none |
| 2000000;regs;32;none;none |
| 2000000;regs;40;none;none |
| 2800000;regs;4;none;none |
| 2800000;regs;8;none;none |
| 2800000;regs;15;none;none |
| 2800000;regs;24;none;none |
| 2800000;regs;32;none;none |
| 2800000;regs;40;none;none |
| 3600000;regs;4;none;none |
| 3600000;regs;8;none;none |
| 3600000;regs;15;none;none |
| 3600000;regs;24;none;none |
| 3600000;regs;32;none;none |
| 3600000;regs;40;none;none |
| 2000000;l1cache;4;none;none |
| 2000000;l1cache;8;none;none |
| 2000000;l1cache;15;none;none |
| 2000000;l1cache;24;none;none |
| 2000000;l1cache;32;none;none |
| 2000000;l1cache;40;none;none |
| 2800000;l1cache;4;none;none |
| 2800000;l1cache;8;none;none |
| 2800000;l1cache;15;none;none |
| 2800000;l1cache;24;none;none |
| 2800000;l1cache;32;none;none |
| 2800000;l1cache;40;none;none |
| 3600000;l1cache;4;none;none |
| 3600000;l1cache;8;none;none |
| 3600000;l1cache;15;none;none |
| 3600000;l1cache;24;none;none |
| 3600000;l1cache;32;none;none |
| 3600000;l1cache;40;none;none |
| 2000000;cache;4;none;none |
| 2000000;cache;8;none;none |
| 2000000;cache;15;none;none |
| 2000000;cache;24;none;none |
| 2000000;cache;32;none;none |
| 2000000;cache;40;none;none |
| 2800000;cache;4;none;none |
| 2800000;cache;8;none;none |
| 2800000;cache;15;none;none |
| 2800000;cache;24;none;none |
| 2800000;cache;32;none;none |
| 2800000;cache;40;none;none |
| 3600000;cache;4;none;none |
| 3600000;cache;8;none;none |
| 3600000;cache;15;none;none |
| 3600000;cache;24;none;none |
| 3600000;cache;32;none;none |
| 3600000;cache;40;none;none |
| 2000000;stream;4;none;none |
| 2000000;stream;8;none;none |
| 2000000;stream;15;none;none |
| 2000000;stream;24;none;none |
| 2000000;stream;32;none;none |
| 2000000;stream;40;none;none |
| 2800000;stream;4;none;none |
| 2800000;stream;8;none;none |
| 2800000;stream;15;none;none |
| 2800000;stream;24;none;none |
| 2800000;stream;32;none;none |
| 2800000;stream;40;none;none |
| 3600000;stream;4;none;none |
| 3600000;stream;8;none;none |
| 3600000;stream;15;none;none |
| 3600000;stream;24;none;none |
| 3600000;stream;32;none;none |
| 3600000;stream;40;none;none |
| 2000000;vm-rw;4;vm-rw-bytes;15G |
| 2000000;vm-rw;8;vm-rw-bytes;7G |
| 2000000;vm-rw;15;vm-rw-bytes;4G |
| 2000000;vm-rw;24;vm-rw-bytes;2G |
| 2000000;vm-rw;32;vm-rw-bytes;1G |
| 2800000;vm-rw;4;vm-rw-bytes;15G |
| 2800000;vm-rw;8;vm-rw-bytes;7G |
| 2800000;vm-rw;15;vm-rw-bytes;4G |
| 2800000;vm-rw;24;vm-rw-bytes;2G |
| 2800000;vm-rw;32;vm-rw-bytes;1G |
| 3600000;vm-rw;4;vm-rw-bytes;15G |
| 3600000;vm-rw;8;vm-rw-bytes;7G |
| 3600000;vm-rw;15;vm-rw-bytes;4G |
| 3600000;vm-rw;24;vm-rw-bytes;2G |
| 3600000;vm-rw;32;vm-rw-bytes;1G |
| 2000000;sctp;4;none;none |
| 2000000;sctp;8;none;none |
| 2000000;sctp;15;none;none |
| 2000000;sctp;24;none;none |
| 2000000;sctp;32;none;none |
| 2000000;sctp;40;none;none |
| 2800000;sctp;4;none;none |
| 2800000;sctp;8;none;none |
| 2800000;sctp;15;none;none |
| 2800000;sctp;24;none;none |
| 2800000;sctp;32;none;none |
| 2800000;sctp;40;none;none |
| 3600000;sctp;4;none;none |
| 3600000;sctp;8;none;none |
| 3600000;sctp;15;none;none |
| 3600000;sctp;24;none;none |
| 3600000;sctp;32;none;none |
| 3600000;sctp;40;none;none |

repetition: 1

</details>

        
    