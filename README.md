# HackathonAuroraBorealias

CUDA Debugging:

check GPU driver version:
nvidia-smi
nvcc --version


Torch Debugging:
pip uninstall torch
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118

Test GPU Availability:


Set Path:
set CUDA_HOME=C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.8
set PATH=%CUDA_HOME%\bin;%PATH%

Link to 11.8: https://developer.nvidia.com/cuda-toolkit-archive
