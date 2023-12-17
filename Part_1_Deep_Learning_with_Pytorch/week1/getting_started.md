### PYTORCH INSTALLATION
See the [Official Pytorch installation guide](https://pytorch.org/get-started/locally/)

### Conda (CPU Installation)
```bash
conda create -n deep_learning python=3.9 -y
conda activate deep_learning
conda install pytorch torchvision torchaudio cpuonly -c pytorch -y
```

### Google Colab
Pytorch is already installed, import, use, and smile 😊
```
import torch
print(f"{torch.__version__}")
```