Benchmark Performance

* Short summary: The model that lead us to the benchmark score is Attention UNet. In our implementation, we have constructed a class that loads the data and applies the following transformations to the images: resize and normalization. Our approach consists of making predictions only for the most common 11 classes. Adam was selected as an optimizer. For computing the loss we have opted for the Cross Entropy function.
* In terms of enhancing metrics, we have optimized the memory usage and the training time. This was done by reducing the number of classes from 150 to 11.
* Kaggle Link: https://www.kaggle.com/code/vladbaranceanu/ade20k-sample-submission
* Competition Score: 1.00579