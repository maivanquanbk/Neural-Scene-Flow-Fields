# Neural-Scene-Flow-Fields
PyTorch implementation of paper "Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes"


## Dependency
The code is tested with Pytorch >= 1.2, the depdenency library includes PIL, opencv, skimage, json, scipy.

## Video preprocessing 
(1) Download Midas Model from ..., and put it on directory 
```bash
   # Usage
    python save_poses_nerf.py --data_path /phoenix/S7/zl548/nerf_data/kid-running/dense/
    python run_midas.py --data_path /home/zl548/nerf_data/kid-running/dense/
    cd RAFT
    python run_flows_video.py --model models/raft-things.pth --data_path /home/zl548/nerf_data/kid-running/dense/ --epi_threhold 1.0
```
