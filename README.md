# yoink

Motion planning for grasping a flying projectile with a robotic arm and two-finger gripper. Completed as a final project for 6.843, Russ Tedrake's excellent robotic manipulation class. Simulation done in Drake, writeups in LaTeX, and crying in banana lounge.

The associated Deepnote project can be viewed [here](https://deepnote.com/project/Gronkowskiiwa-lKm9Ye1YTHiV27yUSU5Iug/%2Fyoink%2Fyoink.ipynb).

## Version Control
Version control with this particular setup is a little strange. Deepnote is pulling an image from Docker Hub with Drake preinstalled, but it doesn't include `git` since it's not designed for active development. This is fixable by running `apt update && apt install -y git` in a Deepnote terminal, and then version control should work.

Since the GitHub integration is already setup, it should load your GitHub account details automatically and you shouldn't need to login.