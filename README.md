# Quadruped locomotion via model-based RL

## Prerequisites

- Python 3.8
- [Isaac Gym](https://github.com/leggedrobotics/legged_gym?tab=readme-ov-file)
- (Optional) Docker

## Installation

Optionally, pull the docker image from Docker Hub via `docker pull knotnote/leggedgym:latest`.

## Usage

### Docker

Start a docker container via:

```bash
docker run -it --net=host \
  --gpus all --env="NVIDIA_DRIVER_CAPABILITIES=all" \
  --env="QT_X11_NO_MITSHM=1" \
  --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" \
  knotnote/leggedgym:latest
```
