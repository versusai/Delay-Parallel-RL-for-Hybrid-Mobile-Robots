<h1 align="center">Delayed Parallel Deep Reinforcement Learning <br> for Mapless Navigation of Hybrid Aerial-Underwater Vehicles</h1>

This repository contains the code and simulation environments for the paper "for Mapless Navigation of Hybrid Aerial-Underwater Vehicles" which introduces a parallel deep reinforcement learning methodology with delay target updates for mapless navigation of Hybrid Unmanned Aerial Underwater Vehicles (HUAUVs).

## Abstract

We present a novel parallel deep reinforcement learning framework that significantly improves the autonomous navigation, obstacle avoidance, and medium transition capabilities of HUAUVs in simulated air and water environments. By leveraging the parallelization of learning agents, we demonstrate enhanced learning effectiveness and a reduction in required training time.

## Contents

- `Parallel-Hydrone-DRL`: Source code for the parallel deep reinforcement learning algorithm.
- `evaluation`: Evaluation scripts and utilities to assess HUAUV navigation performance.
- `gym_hydrone`: Custom Gym environment for HUAUV simulation.
- `models`: Trained model files and configuration for the reinforcement learning agents.

## Installation

Please ensure that you have installed all the packages listed in `Parallel-Hydrone-DRL/requirements.txt`.

## Usage

To train the models using our parallel deep reinforcement learning framework:
```bash
python3 Parallel-Hydrone-DRL/train.py
```
For evaluation of the trained models:
```bash
python3 evaluation/evaluate.py
```
## Simulation

All simulations were performed in the Gazebo simulator, enhanced with RotorS and UUVSim plugins for realistic aerial and underwater dynamics.

| ![Grando  a-w-d4pg-rl](media/grando__a-w-d4pg-rl.gif) | ![Grando  w-a-d4pg-rl](media/grando__w-a-d4pg-rl.gif) |
|:----------------------------------------------------------:|:----------------------------------------------------------:|
|    A-W D4PG-RL                                    |    W-A D4PG-RL                                    |
| ![Grando  a-w-dsac-rl](media/grando__a-w-dsac-rl.gif)  | ![Grando  w-a-dsac-rl](media/grando__w-a-dsac-rl.gif)  |
|    A-W DSAC-RL                                    |    W-A DSAC-RL                                    |

## Paper and Citation

If you use our methodology or this codebase in your work, please cite:

TODO: Add BibTeX entry for the paper.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Our thanks to the contributors and institutions that supported the research and development of this project:

- Ricardo B. Grando
- Raul Steinmetz
- Junior D. Jesus
- Victor A. Kich
- Alisson H. Kolling
- Rodrigo S. Guerra
- Paulo L. J. Drews-Jr
- Robotics and AI Lab, Technological University of Uruguay
- Centro de Ciencias Computacionais, Universidade Federal do Rio Grande - FURG
- Centro de Tecnologia, Universidade Federal de Santa Maria - UFSM
- Intelligent Robot Laboratory, University of Tsukuba

## Contact

For any inquiries, please contact us at `ricardo.bedin@utec.edu.uy`.

