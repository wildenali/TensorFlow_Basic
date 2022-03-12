# TensorFlow 2.x Basic

### Source
- https://www.youtube.com/watch?v=tPYj3fFJGjk&t=1s
- https://www.guru99.com/tensorflow-tutorial.html

1. Install Virtual Environment in Windows
    - `$ pip install virtualenv`
    - `$ virtualenv venv`
    - `$ cd env/Scripts`
    - `$ activate.bat`
    - `$ cd ../..`

2. Install Virtual Environment in Ubuntu

    - `$ sudo apt-get update`
    - `$ sudo apt-get install python3-pip`
    - `$ sudo apt install python3-venv`
    - `$ python3 -m venv env`
    - `$ source env/bin/activate`
    - `$ pip install requests`

3. Install TensorFlow
    - `$ pip install --upgrade pip`
    - `$ pip install tensorflow`
    - `$ pip install tf-nightly` //opsional

4. If using Jupyter Notebook in Windows
    - Change directory to your project
    - `$ ipython kernel install --user --name=venv`
    - `$ jupyter notebook`
    - On the jupyter notebook, open the project and change the kernel to venv

5. If using Jupyter Notebook in Ubuntu
    - Change directory to your project
    - `$ jupyter notebook` (pip install jupyter)
    - `$ ipython kernel install --user --name=env`
    - On the jupyter notebook, open the project and change the kernel to .env
   
6. How to run the project using jupyter notebook
    - `$ pwd` # must be on the project
    - `$ jupyter notebook`

7. Install matplotlib
    - `$ source .env/bin/activate`
    - `$ pip install matplotlib`