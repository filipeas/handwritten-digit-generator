# Handwritten digit generator
* This project aims to create a python script that can generate digits from 1 to 9 using keras and adversarial keras.
* The proposal is to use generative adversarial networks to generate the digits.
* The base used for learning the network was mnist, provided by keras.

## How to install
** follow the steps:
- Install anaconda;
- Create a new virtual environment and call it gan;
- With the terminal open, run the following commands:
```
conda install --override-channels -c main -c conda-forge boost
conda install python==3.7
conda install tensorflow==1.14
conda install keras=2.3.1
pip uninstall numpy
pip install numpy==1.16.4
python
import tensorflow
tensorflow.__version__
import keras
keras.__version__
```
- then change keras version to 2.1.2:
``` 
pip uninstal keras
pip instal keras==2.1.2 
```
- Finally, install Keras Adversarial:
```
git clone https://github.com/bstriner/keras_adversarial.git
cd keras_adversarial
python setup.py install
```
- and matplotlib:
```
pip install matplotlib
```

* ps: Remembering that as a new virtual environment was created, you will have to install Spyder again.

## Some generated examples
* In the example, we see 2 generated digits, 1 and 4, with a training of 100 epochs.
* It is believed that this algorithm can improve if it is placed around 500 to 1000 epochs.

![Figure 2022-02-19 203355](https://user-images.githubusercontent.com/23065588/154822935-136a495c-3231-4133-a17b-ee24fa44d99f.png)

![Figure 2022-02-19 203407](https://user-images.githubusercontent.com/23065588/154823028-40f3ef62-c66e-400f-9760-8cf1ac25647c.png)