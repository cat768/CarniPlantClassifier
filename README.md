# Plant Classifier
This repo uses TensorFlow's Inception V3 Model to classify the exact species of a carnivorous plant. 
The model can be used to classify more types of plants, simply add more labeled folders of images. 
I used [Siraj Raval's TensorFlow tutorials](https://www.youtube.com/watch?v=QfNvhPx5Px8) to develop this. 
Another useful resource for working with TensorFlow's Inception V3 Model is [CodeLab](https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/?utm_campaign=chrome_series_machinelearning_063016&utm_source=gdev&utm_medium=yt-desc#0).

![el](plant_photos/tomato/2Q==.jpg)
![el](plant_photos/potato/images.jpg)

## Requirements

* [TensorFlow Installation](https://www.tensorflow.org/install/)
* [TensorFlow Models](https://github.com/tensorflow/tensorflow)

## Usage

1. Run the classifyPlant script to output the label of the image. 
   `python classifyPlant.py /path/to/file`
  
## Results

### Training Accuracy
![accuracy](accuracies/test_accuracy.png)
### Test Potato Image
![accuracy](accuracies/potato_test.png)
### Test Tomato Image
![accuracy](accuracies/tomato_test.png)


