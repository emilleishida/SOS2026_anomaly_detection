<p>
<img src="images/snad_cropped.png" width="200">
<img src="images/coniferest_cropped.png" width="120">
</p>

# Anomaly detection in Astronomical Light curves
Material for [School of Statistics 2026](https://indico.in2p3.fr/event/37891/)  
*by Emille Ishida, May/2026*  

Original data from the [PLAsTiCC Kaggle](https://www.kaggle.com/c/PLAsTiCC-2018) data challenge
Analysis taken from the [SNAD tutorials](https://coniferest.snad.space/en/latest/notebooks.html)

## Installation

In order to proper run the materials given here, we advise you to creat a virtual environment and work within it.  
In a terminal, create a dedicated folder and source the environment:

```bash
mkdir venv
cd venv
python -m venv anomaly
source anomaly/bin/activate
```
**[Warning] This material was only tested in Python 3.12**  

If everything is correct, you should see the virutal environment identification in the beginning of your command line.  
From now on, this directory should be reserved exclusively to the virtual environment, and you should NOT work within it.  
Create another directory for your work files, clone this repository and install the necessary dependencies:

```bash
cd ..  
mkdir git_repo  
cd git_repo  
git clone https://github.com/emilleishida/SOS2026_anomaly_detection.git
pip install --upgrade pip              # make sure you have the latest pip version
pip install -r requirements.txt
```

You are now ready to call the jupyter notebook:

``bash
jupyter notebook  
``

This should open a windown in your browser, giving you access to the notebook.
