# FasTRack_Python_implementation

A recreated Python implementation of the FasTrack framework for safe, real-time motion planning and control.

This project includes a recreation of the 5D–3D vehicle model example from the original FasTrack paper, with all constraints and dynamics faithfully implemented.

- Planning: Rapidly-exploring Random Tree (RRT) for global path planning

- Control: Carrot-Chase tracking controller for real-time trajectory tracking

- Reachability: HJ precomputation for computing tracking error bounds; Offline reachability computation module; Seamless integration of planner + tracker + safety constraints

- Simulation: 2D environment with circular obstacles; Start–goal navigation; Real-time visualization




## 📖 Citation

If you use this repository, please cite the original FasTrack paper:

https://doi.org/10.48550/arXiv.2102.07039



@article{bansal2020fastrack,
  title        = {Safe Real-Time Motion Planning With Fast and Complete Trajectory Tracking},
  author       = {Bansal, Somil and Chen, Mo and Herbert, Sylvia and Tomlin, Claire},
  journal      = {IEEE Transactions on Automatic Control},
  volume       = {66},
  number       = {11},
  pages        = {4938--4953},
  year         = {2021},
  publisher    = {IEEE}
}
