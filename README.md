# MNIST-Deep Learning
Reading handwritten digits

## Architecture
There will be picture(Architecture) of DeepLearning algorithm
[!](MNIST_structure.png)

### Jupyter-Notebook
Launching Jupyter Notebook as we did before

### Front-end
Installing web server and executing index.html
- open port 80 for web access
- install nginx
```
sudo apt update
sudo apt install nginx
```
- copy index.html and static folder in /var/www/html/
- modify index.html with your BACKEND public IP.

### Back-end
Installing backend server and running python script
- open port 5000
- install Miniconda
```
wget httрs://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
sh Miniconda3-latest-Linux-x86_64.sh
```
- create virtual environment / install requirements.txt
```
conda create -n backend
conda activate backend
conda install opencv
pip install -r requirements.txt
```
- copy cnn-minst / keras_flask.py
- launch keras_flask.py
```
python keras_flask.py
```
## Pre-Finish
## MNIST Deep DeepLearning

## Finish and Result
picture as a Result
