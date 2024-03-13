# Deep Learning for Real-Time P-Wave Detection: A Case Study in Indonesia's Earthquake Early Warning System
This is the official implementation of paper **Deep Learning for Real-Time P-Wave Detection: A Case Study in Indonesia's Earthquake Early Warning System** (TBA) <br />


### Installation
To run this repository, we suggest to install packages with Anaconda.

Clone this repository:

```bash
git clone https://github.com/bowoadi/realtime_earthquake_detection.git
cd realtime_earthquake_detection
```

Create a new environment via conda & pip

```bash
conda update conda
conda create --name red python==3.7 tensorflow-gpu -y
conda activate red
pip install --upgrade pip
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch -y
pip install jupyter tqdm obspy

```