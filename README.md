# How to set up your Machine Learning Environment
Basic Machine Learning Environment set up using Anaconda

## Step 1 - Download and install Anaconda
Download Anaconda - https://www.anaconda.com/download/ <br />
Go with the latest stable version of python (Recommended)

## Step 2 - Create a new Environment
From start menu locate Conda Prompt. Use Anaconda Prompt to create new environment. <br />
Copy the following command in Anaconda Prompt.
```
conda create -n ml-env pip python=3.9
```
Here `ml-env` is machine learning environment name. <br />
This creates a new environment in Anaconda. <br />
To activate environment use the following command:
```
activate ml-env
```
Now instead of (base) prompt should change to (ml-env)

## Step 3 - Install required packages
Type the following command for installing respective packages
### Scipy
```
pip install scipy
```
### Numpy
Numpy is installed with Scipy by default. If required use following command to install Numpy.
```
pip install numpy
```
### Matplotlib
```
pip install matplotlib
```
### Pandas
```
pip install pandas
```
### Scikit-learn
```
pip install scikit-learn
```
### Tensorflow
For systems with only CPU
```
pip install tensorflow
```
If this doesn't work and gives error, use the followinng command to ignore installed version of Tensorflow and upgrade.
```
pip install --ignore-installed --upgrade tensorflow
```
For systems with GPU
```
pip install tensorflow-gpu
```
If this doesn't work and gives error, use the followinng command to ignore installed version of Tensorflow and upgrade.
```
pip install --ignore-installed --upgrade tensorflow-gpu
```
### Keras
By default installed with other packages. In-case required use the following command.
```
pip install keras
```

### END