## Model Robustness  
We used the simple train-test split approach while training the deep learning models for devolearn, in order to get better performance we should use techniques like:

* _k_-fold cross validation 

* Ensemble models 

* Hyperparameter optimization 

* Label smoothing (reduces overconfident “wrong”  predictions)

* Support for variable sized images with Adaptive average pooling

## Usability  
As the library grows, we should have a better place to host proper documentation on gitbook or on a website like devoworm.github.io/devolearn/docs. 

In training DevoLearn’s deep-learning models on commonly available data, the more common the use case, the more potential users we get. 

* adding support for more species 

* devolearn should also contain pre-trained deep-learning models from other species which are of high importance in developmental biology. 

We should look for more datasets spread across different species which could be used for devolearn. Then we can split up the different models as:

__Example:__   
~~~
from devolearn.c_elegans import segmenter          ## species 1   
from devolearn.zebra_fish import age_estimator     ## species 2  
~~~

## Online demos

