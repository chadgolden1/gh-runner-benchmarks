# GitHub Runner Benchmarks
Exploring performance characteristics of GitHub hosted runners

## Windows 2022 Runner IOPS
This repository contains a workflow that measures the IOPS of C:, D:, and VHDX (ReFS) drives Windows 2022 GitHub hosted runners.

*Example benchmark results:*
| 💾 Drive               | 🚀 IOPS    |
|:-----------------------|-------------:|
| C:                     | 4535.53 |
| D:                     | 14124.59 |
| E: (C:\dev_drive.vhdx) | 58570.90 |
| E: (D:\dev_drive.vhdx) | 63628.74 |

See the [**Benchmark IOPS**](https://github.com/chadgolden1/gh-runner-benchmarks/actions/workflows/bench.yml) workflow for more details.
