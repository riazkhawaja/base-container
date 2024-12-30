This repo contains the Dockerfile used to create an image for gradient runtime on Paperspace, that is compatible with Kohya SS. The image can be found [here](https://hub.docker.com/repository/docker/mriaz9908/pt201-cudatk118-py310/general).

For compatibility with Kohya SS, it includes the following on top of the base container provided by paperspace:
- python3.10-venv
- python3-tk
- python 3.10
- CUDA 11.8 toolkit
- CUDNN 8.9.6.50