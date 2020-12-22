#Upgrading DevoLearn 

## Model Robustness  
We used the simple train-test split approach while training the deep learning models for devolearn, in order to get better performance we should use techniques like:

* _k_-fold cross validation 
* Ensemble models 
* Hyperparameter optimization 
* Label smoothing (reduces overconfident “wrong”  predictions)
* Support for variable sized images with Adaptive average pooling
* Using more training data for re-training the pre-existing models for better accuracy.

## Usability  
As the library grows, we should have a better place to host proper documentation on gitbook or on a static website which could be named like devoworm.github.io/devolearn/docs. 

Most importantly, we have to train devolearn’s deep-learning models on commonly available data, the more common the use case, the more potential users we get. 

## Adding support for more species 

Devolearn should also contain pre-trained deep-learning models from other species which are of high importance in developmental biology. 

We should look for more datasets spread across different species which could be used for devolearn. Then we can split up the different models as:

__Example:__   
~~~
from devolearn.c_elegans import segmenter          ## species 1   
from devolearn.zebra_fish import age_estimator     ## species 2  
~~~

## Online demos

Colab notebooks, however simple they may seem, are still a bit intimidating to people from non CS backgrounds, so we should focus on making interactive demos which showcase both our research and tutorials. For example, we can make semi-interactive web pages which contain “slider-like” mechanisms to interpolate between different values. This would make it more readable and intuitive. An example can be found on [this paper](https://distill.pub/2017/feature-visualization/#enemy-of-feature-vis). 
