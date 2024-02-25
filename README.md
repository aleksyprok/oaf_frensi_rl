# oaf_frensi_rl
Frensi's reinforcement learning code for the OAF pitch day.

## Installation instructions

- Clone the repository to your local machine.
- Navigate to the project directory.
- Make sure you are in a bash session on the GPU node, for SDCC run 
``srun --partition=gpu_p100_titan --gres=gpu:1 --pty bash -i``
- Run `conda env create -f environment.yml --name oaf_env` to install the necessary dependencies and create
  a virtual environment called `oaf_env`.
