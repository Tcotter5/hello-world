# Hello, World!

### Please scroll down for HW Flask code
![This is an image](https://eoimages.gsfc.nasa.gov/images/imagerecords/0/885/modis_wonderglobe_lrg.jpg)




```
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "Hello, World! <h1>Hi Rick<h1>"

if __name__ == "__main__":
    app.run() 
```
