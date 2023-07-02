# INSTRUCTIONS TO UPLOAD YOUR PROJECT

We use this to guarantee the same structure for all projects.
Projects will be then uploaded to our [project page](https://opencampus-sh.github.io/oc-ml-projects/) and there these information will be displayed.
So you can check at any time the [project page](https://opencampus-sh.github.io/oc-ml-projects/) to have an idea about how that would look like.

### Objective

Your objective is to train a neural network to estimate the sales from past data. You can choose the form of the input and the output, usually the input is the data for a specific day (or more than one day) and the output is the sales for a specific day (or more than one).

### Data

More information on the data can be found in the data folder.
We have 2 datasets, which they contain similar data, the first one is smaller and maybe a bit simpler (and alreay used), the second may require some small pre-processing and is a bit larger and contains more location (so more challenging).
In each folder there is a presentation or a readme file to explain.

### Technical Information

It is advisable to start using FFNN without special features and find the optimal architecture configuration. Later you can use LSTM, CNN (1D) or whatever you like to try to improve the result.

### Target Results

To compare your results with the ones from previous groups, please use the Mean Absolute Percentage Error ([Wikipedia](https://en.wikipedia.org/wiki/Mean_absolute_percentage_error) - [Tensorflow Metric](https://www.tensorflow.org/api_docs/python/tf/keras/metrics/MeanAbsolutePercentageError))

Approximately you should reach an error below 20% on the prediction for a single day in the dataset1. Best results from the last semesters arrived around 15-16% error.

Once you are done, you could indicate the error you got (MAPE) and which architecture you used and it will be added here in a sort of ranking.

