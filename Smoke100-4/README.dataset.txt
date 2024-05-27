# Smoke100 > 640x640 M-H-L
https://universe.roboflow.com/smoke-detection/smoke100-uwe4t

Provided by a Roboflow user
License: CC BY 4.0

# Smoke Detection Dataset

This computer vision smoke detection dataset contains images of synthsized smoke in both indoor and outdoor settings. Check out the source link below for more information on this dataset.

source: 

Smoke100k dataset
https://bigmms.github.io/cheng_gcce19_smoke100k/


## Use Cases
- Identifying smoke indoors 
- Identifying smoke outdoors (but **not** with aerial imagery) 
- Identifying smoke-like object (eg: mist/steam from humidifiers)



## Testing

You can test this model by using the [Roboflow Inference Widget](https://blog.roboflow.com/testing-a-computer-vision-model-in-10-seconds-or-less/) found above. The action hits the model inference API, which in turn produces the color coded bounding boxes on the objects the model was trained to detect, along with its labels, and confidence for each prediction. The feature also produces the JSON output provided by the API.

