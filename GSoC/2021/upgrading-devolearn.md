## Upgrading DevoLearn 0.2.0
Devolearn was created during Google Summer of Code 2020, and is now a standalone program (PyPi repository: https://pypi.org/project/devolearn/). DevoLearn is a pre-trained Deep Learning model for the segmentation of microscopy images. It is specialized for the analysis of 2-D slices of _C. elegans embryogenesis_, although it can be useful in the analysis of embryogenesis in other species. This project will focus on creating benchmarks for performance and then testing the improved model on a broad range of data sets. Your goals will be to improve overall performance in terms of accuracy and generalizability, enhance functionality (via a graphical user interface), and perhaps add additional pre-trained models to the DevoLearn library. Proficiency in Python and CoLab/Jupyter Notebooks is required.

### More details:
#### There would be 4 key elements in this project:
* Improving the current models
* Training and adding more useful models 
* Improving usability
* (optional) Interactive online demos. 

#### Improving the current models
We used the simple train-test split approach while training the deep learning models for devolearn, in order to get better performance we should use techniques like:

* _k_-fold cross validation 
* Ensemble models 
* Hyperparameter optimization 
* Label smoothing 
* Support for variable sized images with Adaptive average pooling
* Using more training data for re-training the pre-existing models for better accuracy.

#### Adding more models

Devolearn should also contain pre-trained deep-learning models from other species which are of high importance in developmental biology. We can split up the different species as:

__Example:__   
~~~
from devolearn.c_elegans import segmenter          ## species 1   
from devolearn.zebra_fish import age_estimator     ## species 2, this is just an example
~~~

#### Improving usability  
As the library grows, we should have a better place to host proper documentation on a static website which could be named like devoworm.github.io/devolearn/docs. 

Most importantly, we have to train devolearn’s deep-learning models on commonly available data, the more common the use case, the more potential users we get. 

#### Online demos

Colab notebooks, however simple they may seem, are still a bit intimidating to people from non CS backgrounds, so we should focus on making interactive demos which showcase both our research and tutorials. For example, we can make semi-interactive web pages which contain “slider-like” mechanisms to interpolate between different values. This would make it more readable and intuitive. An example can be found on [this paper](https://distill.pub/2017/feature-visualization/#enemy-of-feature-vis). 

#### More Information on Pre-requisites
Proficiency in python with a good hold of tools like numpy, pandas and PyTorch.

#### Resources
* [DevoLearn source code](https://github.com/DevoLearn/devolearn) and [contribution guidelines](https://github.com/DevoLearn/devolearn/blob/master/.github/contributing.md)
* [Wormbook](http://www.wormbook.org/)
* [GSoC 2020](https://github.com/devoworm/GSoC-2020/tree/master/Pre-trained%20Models%20(DevLearning))


#### Get in touch:
* [Dr. Bradly Alicea](https://twitter.com/balicea1)
* [Mayukh Deb](https://twitter.com/mayukh091)
* [Join our slack](https://launchpass.com/openworm)


