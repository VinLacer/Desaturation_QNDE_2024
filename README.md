# Desaturation_QNDE_2024
This repository contains scripts which generate the results presented in ["Reversing saturation of bandpass signals for QNDE 2024"](WWW.LINK.COM)

## 0. Images of the experiment
Here you can see how we carry out experiments to obtain the data used in this research.


<img src="/images/experiment_2.jpeg" width="300" height="300"> <img src="/images/experiment_1.jpeg" width="300" height="300">

<img src="/images/experiment_0.jpeg" width="300" height="300"> <img src="/images/imersion.jpeg" width="300" height="300">

## 1. Dataset
The dataset required to properly reproduce the results is avaliable at [this Google Drive Folder](https://drive.google.com/drive/folders/1RpN-wGD9NisS9uG2H9xqZy0tvnD0YR42?usp=drive_link). After downloading the "template_waveform.npz" you must copy and paste to the project directory called "scripts" ("Desaturation_QNDE_2024/scripts").

### 1.1 Dataset Organization
```
+---Desaturation-QNDE_2024
|   |---images
        +---images of the experiments for this research 
|   |   
|   \---scripts
        +---template_waveform.npz (NEED TO DOWNLOAD FROM GOOGLE DRIVE)
|       +---Thickness_measurement.py
|       +---waveform_real_data.py
|       +---waveform_synthetic.py
```


## 2. Getting Started

### 2.1 You will need to clone the Desaturation repository. To do this just copy and paste the following commands in the terminal.

```
cd ~
git clone git@github.com:VinLacer/Desaturation_QNDE_2024.git
cd Desaturation_QNDE_2024
```

### 2.2 If you want to obtain the results without an IDE, just follow the bellow commands:

```
cd scripts
```
To obtain the results of the Thickness Measurement execute the following command:
```
pyhton3 Thickness_measurement.py
```
If you want to see the results for Waveform with Synthetic data, type this:
```
python3 waveform_synthetic.py
```
With real data:
```
python3 waveform_real_data.py
```
### Remember to get the data from the Google Drive folder and install the Dependecies (see in topic 3) before do this steps


## 3. Dependecies
You will need the following packages to reproduce the results:
```
Matplotlib #For data visualization
Scipy # for signal processing algorithms
Numpy # for general numerical processing
```
