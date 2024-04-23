# Computer Vision 
## Tutorial 2: Reproducible Deep Learning

This lesson introduces essential tools for developing deep learning projects to promote code *reproducibility* and *reusability*. We will cover three open-source tools: (1) [Git](https://git-scm.com/), (2) [Docker](https://www.docker.com/), and (3) [Hydra ](https://github.com/facebookresearch/hydra). The choice of tools is questionable but offers a good compromise between practicality and educational needs.

## Local set-up
You can run this project in any local environment. Just as an example, you may choose an [Anaconda](https://www.anaconda.com/products/individual) virtual enviroment. If so, you can create a virtual environment with the following command:
```bash
conda create -n reprodl python=3.12 pip; conda activate reprodl
```
and install all the requirements.
```bash
pip install -r requirements.txt
```