# Activator-Inhibitor Reaction-Diffusion Simulations

## Description
Simulations for an activator-inhibitor pair of partial differential equations representing a reaction-diffusion circuit. The activator can be of two forms: juxtacrine, or paracrine. In the former, it travels in space through neighbour activation, in the latter, through diffusion. The inhibitor is always diffusible. This repository contains code for running 1D and 2D simulations of a single circuit. Additionally, it enables running two independent or cross-inhibiting circuits in two dimensions.

## Structure
- 1D simulations
  - single runs
  - 1D_batch
- 2D simulations
  - single runs
  - 2D_batch

## Usage
Single, 1D simulations:
python 1D simulations/main.py

With output 3D visualization:
python 1D simulations/run_3D_surface_visualization.py --output test

Batch 1D simulations:
python 1D simulations/1D_batch/batch_runner.py -c 1D simulations/1D_batch/config.yaml

Single 2D simulations for a single circuit:
python simulations/main.py

Batch 2D simulations for a single circuit:
python 2D_simulations/2D_batch/batch_runner_2D.py

Single 2D simulations for a dual circuit:
python 2D simulations/main_coupled_2D.py

Batch 2D simulations for coupled circuits:
python 2D_simulations/2D_batch/batch_coupled_2D.py
