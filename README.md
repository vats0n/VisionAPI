# VisionAPI

Parses Names, Registration Number, Registration Date, Engine Number, Chassis Number and Manufacturing Date given an image of a driving license to an Excel file

Demo: https://license-vision.herokuapp.com

Create GCP project , activate Cloud Vision API and get service account key

How to run

In terminal

```
source ./bin/activate
pip install -r requirements.txt
export GOOGLE_APPLICATION_CREDENTIALS='path_to_key'
flask run
```

![Driving License](https://github.com/Nirmal2000/VisionAPI/blob/master/static/9.jpg)

![Result](https://github.com/Nirmal2000/VisionAPI/blob/master/static/result.jpg)
