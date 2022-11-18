# jetbot-env-docker
An image for simulating Nvidia jetbot development environment with jupyter lab GUI.

NOTE: Please assure your cuda/cudnn version is higher than the configuration otherwise the version change is needed, we use [RTX 2080ti]([GeForce RTX 2080 Ti | 規格 | GeForce (nvidia.com)](https://www.nvidia.com/zh-tw/geforce/graphics-cards/geforce-rtx-2080-ti/specifications/)).

## Requirement

privilege: root 

base: ubuntu 20.04

python: 3.8.3

cuda: 11.1

cudnn: 8.0.5

pytorch: 1.8.1

## optional libs

tensorflow-gpu: 2.5