# Hello, World!

### Please scroll down for HW Flask code
![This is an image](https://eoimages.gsfc.nasa.gov/images/imagerecords/0/885/modis_wonderglobe_lrg.jpg)

**Within the Terminal**
1. Install your virtualenv ($ pip3 install virtualenv)
2. Create a folder that will hold your virtual environments ($ mkdir VENV)
3. Choose the folder you just created ($ cd VENV)
4. Generate an additonal folder within VENV ($ virtualenv venv1)
5. Activate environment ($ source/venv1/activate)
6. Install Flask ($ pip3 install Flask)
7. Generate requirments file for sharing/saving purposes ($ pip3 freeze --local > requirements.txt)
8. Open Python within terminal ($ python3) 
9. Enter code below! 


```
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, World! <h1>Hi Rick<h1>"

if __name__ == "__main__":
    app.run() 
```

