# graphcast_oper

$  sudo docker run -it --gpus all --ipc=host --ulimit memlock=-1 --ulimit stack=67108864 -v $(pwd):/workspace  nvcr.io/nvidia/modulus/modulus:24.04

$ pip install ai-models-graphcast

$ git clone https://github.com/ecmwf-lab/ai-models-graphcast

$ pip install -r requirements-gpu.txt -f https://storage.googleapis.com/jax-releases/jax_cuda_releases.html
