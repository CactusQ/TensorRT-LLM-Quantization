
# TensorRT-LLM-Quantization
Benchmarking different quantization settings using GPT-2 as an example. </br>
Can be customzied and repurposed for other models or metrics.

Video walkthrough and explanation:

[![Youtube video link](https://img.youtube.com/vi/ESZK5p7yGmQ/0.jpg)](https://youtu.be/ESZK5p7yGmQ)


## Prerequisites
- NVIDIA GPU with CUDA support
- Docker and NVIDIA Container Toolkit installed (will be installed in the notebook as well)
- Python 3.10, pip, and necessary Python libraries
- Jupyter or Google Colab

Or run the docker container and install Jupyter there:
```bash
docker run --rm --runtime=nvidia --gpus all --entrypoint /bin/bash -it nvidia/cuda:12.1.0-devel-ubuntu22.04
```
