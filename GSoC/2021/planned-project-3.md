## DevoNet: Specialized Convolutional Neural Network (CNN) for Biological Data 

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm which can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image and be able to differentiate one from the other.[1] The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics [2].

Transfer learning is a common practice in Deep learning because it enables us to build reliable models in a timesaving way. With transfer learning, rather than starting the learning process from scratch, we start from exemplars that have been learned when solving a different problem. In this way we can leverage previous learnings and avoid starting from scratch (It is like standing on the shoulder of giants.) [3]

The intuition behind transfer learning for image classification is that if a model is trained on a large and general enough dataset, this model will effectively serve as a generic model of the visual world. You can then take advantage of these learned feature maps without having to start from scratch by training a large model on a large dataset.

We can use these pre-trained models to extract a general description of classes and features without requiring a prohibitive amount of training data.
We estimate that the amount of required training data may be reduced by an order of magnitude. To get this advantage, pre-trained models must be suitable to the type of input data. There are a number of models specialized for language processing and general use, but options are fewer within the unique feature space of developmental biology. Devonet will be a CNN designed specifically for Biological data, and  will increase the scope of transfer learning and will significantly advance the prevailing Deep learning results. 

References:  
[1] S. Albawi, T. A. Mohammed and S. Al-Zawi, "Understanding of a convolutional neural network," 2017 International Conference on Engineering and Technology (ICET), Antalya, 2017, pp. 1-6, doi: 10.1109/ICEngTechnol.2017.8308186.

[2] T. Wiatowski and H. Bölcskei, "A Mathematical Theory of Deep Convolutional Neural Networks for Feature Extraction," in IEEE Transactions on Information Theory, vol. 64, no. 3, pp. 1845-1866, March 2018, doi: 10.1109/TIT.2017.2776228.

[3] M. Jogin, Mohana, M. S. Madhulika, G. D. Divya, R. K. Meghana and S. Apoorva, "Feature Extraction using Convolution Neural Networks (CNN) and Deep Learning," 2018 3rd IEEE International Conference on Recent Trends in Electronics, Information & Communication Technology (RTEICT), Bangalore, India, 2018, pp. 2319-2323, doi: 10.1109/RTEICT42901.2018.9012507.
