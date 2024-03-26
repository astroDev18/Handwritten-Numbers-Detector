# Handwritten Numbers Model
## Base Model
A Machine Learning Model that reads handwritten numbers and predicts what value they contain. It achieves 97% reliability in tests.
### An Image of The Model Predicting a Number:

![Image of Model Working](https://cdn.discordapp.com/attachments/755504752011378822/1222203897297502288/image.png?ex=66155d14&is=6602e814&hm=48c940dee3007c758df79353733d35915367fa22c39aea47d25e9a82a276d670&)

## Optimized Model
By using rotations to create new and more varied training data and increasing the epoch to 10, I was able to reach an average of 0.976 effeciency, approaching 0.98 nearly.
### An image of the model reaching 0.976 effeciency in predicting number values:

![Image of High Effeciency](https://cdn.discordapp.com/attachments/755504752011378822/1222264037887447202/image.png?ex=66159517&is=66032017&hm=270c92514aed08fd8c7333edf767e65aa5dbad47f8947bb27164ce52da167433&)

## Getting Started

You can download the project and run the jupyter notebook file, the base_model.ipynb shows the base ML Model, and the second optimized_model.ipynb shows the more effecient model. 
To run further in-depth analysis, download the MNIST dataset from https://pjreddie.com/projects/mnist-in-csv/ and change the path to use the test and train data respectively.

### Prerequisites

Have a working VS Code editor setup with Jupyter Notebooks plug-in installed

### Installing

Download the project, then hit run at the top for the Jupyter Notebook to execute. It should run all code cases after that point, no further setup needed.

## Built With

* [Jupyter Notebooks]([https://docs.jupyter.org/en/latest/](https://github.com/jupyter/notebook)) - The code framework used
* [Python](https://www.python.org/) - Programming language used

## Authors

* **astro_dev** - *Developed Project* - [astroDev18](https://github.com/astroDev18)

## Acknowledgments

* Inspiration and learning from Tariq Rashed's book, "How to Build Your Own Neural Network"
