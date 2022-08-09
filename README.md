# Hand-Written-Digit-Recognition

### About MNIST dataset:
The MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consists of a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. Additionally, the black and white images from NIST were size-normalized and centered to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.


## Getting Started

How to use
```    
git clone https://github.com/dhruvabisht/Hand-Written-Digit-Recognition.git
cd Handwritten-Digit-Recognition
pip3 install -r requirements.txt 
python3 tf_cnn.py
```
* You can also run the `load_model.py` to skip the training of NN. It will load the pre saved model from `model.json` and `model.h5` files.
```
python3 load_model.py <path/to/image_file>
```
For example
```
python3 load_model.py assets/images/1a.jpg 
```
 
## Prerequisites

- Python 3.5
- OpenCV
```
sudo apt-get install python-opencv
``` 
