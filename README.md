# DEANet++ – Low-Light Image Enhancement (PyTorch)

This repository implements a reproducible version of **DEANet++** from the paper:

> **"A Joint Network for Low-Light Image Enhancement Based on Retinex"  
> Yonglong Jiang et al., Cognitive Computation (2024)**  


---

##  Features
- Retinex-based decomposition into Reflectance & Illumination  
- Enhancement network using Dense blocks + Channel Attention  
- Adjustment network (U-Net + ResBlocks)  
- Works on the LOL dataset (real low/normal-light pairs)  
- Training + inference scripts included  

---

##  Project Structure

models/
decompose_net.py
enhance_net.py
adjust_net.py
deanetpp.py
dataset.py
losses.py
train.py
eval.py

