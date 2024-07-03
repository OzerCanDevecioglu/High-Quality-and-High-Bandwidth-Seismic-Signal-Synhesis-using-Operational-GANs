# High-Quality-and-High-Bandwidth-Seismic-Signal-Synhesis-using-Operational-GANs



# Project Description

Vibration sensors are essential in acquiring seismic activity for an accurate earthquake assessment. The state-of-the-art sensors can provide the best signal quality and the highest bandwidth; however, their high cost usually hinders a wide range of applicability and coverage, which is otherwise possible with their basic and cheap counterparts. But, their poor quality and low bandwidth can significantly degrade the signal fidelity and result in an imprecise analysis. To address these drawbacks, in this study, we propose a novel, high-quality, and full bandwidth seismic signal synthesis by transforming the signal acquired from an inferior sensor. We employ 1D Operational Generative Adversarial Networks (Op-GANs) with novel loss functions to achieve this. Therefore, the study's key contributions include releasing a new dataset, addressing operational constraints in seismic monitoring, and pioneering a deep-learning transformation technique to create the first virtual seismic sensor. The proposed method is extensively evaluated over the Simulated Ground Motion (SimGM) benchmark dataset, and the results demonstrated that the proposed approach significantly improves the quality and bandwidth of seismic signals acquired from a variety of sensors, including a cheap seismic sensor, the CSN-Phidgets, and the integrated accelerometers of an Android, and iOS phone, to the same level as the state-of-the-art sensor (e.g., Kinemetrics-Episensor). 
[Paper Link](https://arxiv.org/abs/2202.00589)

![image](https://github.com/OzerCanDevecioglu/High-Quality-and-High-Bandwidth-Seismic-Signal-Synhesis-using-Operational-GANs/assets/98646583/8c514e9f-5a92-45b3-9e8d-72cafb6d8d8f)

## Dataset
![image](https://github.com/OzerCanDevecioglu/High-Quality-and-High-Bandwidth-Seismic-Signal-Synhesis-using-Operational-GANs/assets/98646583/997b794b-6185-4239-b72e-c64b8f8bcd19)

- Training and testıng dataset can be downloaded from the given [link](https://drive.google.com/drive/folders/1XScA_USC8ewJ9uGVBQfCC4KvxUbwi4qp?usp=sharing)
## Run

#### Train
- Download train data to the "mats/" folder
- Start training
```http
  python 1D_Self_Operational_CycleGAN.py
```
- Start evaluation. You can download Pre-trained Network [weights](https://drive.google.com/drive/folders/1ezrWa6A69H5ccNV1y2hb_GuyLsmEk1ff?usp=sharing)
```http
  python test.py
```
- Save outputs to the "test_outputs/" folder 
- Visualize Results
```http
  python plot_outputs.py
```
## Prerequisites
- Pyton 3
- Pytorch
- Pytorch-Lightning
- [FastONN](https://github.com/junaidmalik09/fastonn) 


  
## Results

![image](https://github.com/OzerCanDevecioglu/High-Quality-and-High-Bandwidth-Seismic-Signal-Synhesis-using-Operational-GANs/assets/98646583/483ff2c8-f3cc-4bb6-8677-3dcbf85f7525)




  
## Citation
If you find this project useful, we would be grateful if you cite this paper：

```http
```
