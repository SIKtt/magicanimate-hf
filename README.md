# MagicAnimate-hf

---
title: MagicAnimate
emoji: 💃
colorFrom: purple
colorTo: purple
sdk: gradio
sdk_version: 4.4.0
python_version: 3.8
app_file: app.py
models:
 - zcxu-eric/MagicAnimate
 - runwayml/stable-diffusion-v1-5
 - stabilityai/sd-vae-ft-mse
pinned: false
---

```
from huggingface_hub import snapshot_download

snapshot_download(repo_id="runwayml/stable-diffusion-v1-5", local_dir="./stable-diffusion-v1-5")
snapshot_download(repo_id="stabilityai/sd-vae-ft-mse", local_dir="./sd-vae-ft-mse")
snapshot_download(repo_id="zcxu-eric/MagicAnimate", local_dir="./MagicAnimate")
```

```
torch==2.1.0
torchvision==0.16
```
