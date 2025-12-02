# SceneFlowReconstruction

- Arthur Kowara
- a2kowara@uwaterloo.ca
- CS680 Project
- 20825696

# Specifics
- python 3.10.9
- NVIDIA RTX 5080 GPU
- Cuda 12

# sceneflow_reconstruction.ipynb
- jupyter notebook based off the orginal sceneflow reconstruction paper https://github.com/gengshan-y/expansion
- Personal modifcations were made to run the tests disscussed in my paper

# KITTI Dataset
- Too large for github
- Need to download the dataset from https://www.cvlibs.net/datasets/kitti/eval_scene_flow.php
- Please reach out to me if you need assistance getting the dataset

# Requirements
- pip install -r requirements.txt

# fpttc_tau 
- Holds the precomputed per pixel motion in depth from fpttc workflow
- tau0 is the MID of frame 0 based on frame 1
- tau1 is the MID of frame 1 based on frame 0
- Original https://github.com/LChanglin/FP-TTC
- Personal Modifications https://github.com/akowara/FP-TTC

# Metric 3d_depths
- Holds the precomputed Metric 3d depths of each images
- Original https://github.com/YvanYin/Metric3D
- Personal Modifcations were made to match the requiremnts desired, please contact for futher information

# precomputed
- Holds the precomputed monodepth and optical flow results from https://github.com/gengshan-y/expansion

# utils 
- Utils files from https://github.com/gengshan-y/expansion

# dataloader
- Data laoding files from https://github.com/gengshan-y/expansion