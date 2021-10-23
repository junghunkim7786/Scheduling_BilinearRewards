### Scheduling Servers with Stochastic Bi-linear Rewards


## Requirements
- Python 3 >=3.5

## Structure
  * main.py
  This file includes the main function.

  * Preprocess.py
  This file includes the code for extracting and preprocessing real data.

  * Algorithm.py
  This file includes the code for the scheduling algorithm.

  * Environment.py
  This file includes the code for generating an environment (synthetic world or real world) for queueing system with bilinear structure. 

  * Oracle.py
  This file includes the code for running the oracle policy.

## How to run this code
please run this command:

Synthetic data: python3 main.py syn
Real data: python3 main.py real