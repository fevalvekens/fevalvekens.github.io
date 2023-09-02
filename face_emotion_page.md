## Face Emotion project page

### Executive Summary 

This deep learning project proposes the Complex Convolutional Neural Network (CNN) for the accurate detection of facial emotions. The dataset provided to train the models is composed of small size grayscale images of faces expressing four types of emotion: happy, sad, neutral or surprised. Using Transfer Learning did not prove beneficial in classifying the images of the given dataset. The performance of these pre-built architectures was lower than expected so building a more complex but flexible CNN model was the best approach to work with the specific dataset. The suggested model achieved high performance with 82% accuracy. However, it is subject to a number of limitations, including the lower accuracy in predicting certain classes, and when facial occlusion is present. Its computation efficiency is also linked to the volume and size of images to be processed. It is recommended that stakeholders consider these limitations and challenges in building an improved and robust predictive model, as well as use a larger and more diverse training dataset, explore data augmentation techniques to improve the model’s accuracy and evaluate the trade off of developing a more complex but more computationally expensive model.

### Model Comparison 

Below is a diagram explaining our workflow. We shall build different 6 models, train each model on the training dataset, monitor the performance of the model on the validation dataset and evaluate the model on the test dataset using the metric 'accuracy'.
<img src="model_comparison.png?raw=true"/>

### General Design steps

The modelling part (see blue blox in the above diagram) is an iterative process.

In the first iteration, we will run the model with a set of parameters that we shall use as a start. We will build and compile the model with the Adam optimiser (learning rate = 0.001). We shall fit the model with a batch size of 32, number of epochs 30.

At the end of our first iteration, we shall plot the training and validation accuracies to evaluate how our model is learning and performing. Then we shall evaluate our model's performance on unseen data. Based on the performance, we shall make changes to our base model, which could include:

- adding more layers to increase the complexity of our model if the plot shows that our model is underfitting
- using regularisation techniques to prevent the overfitting of our model if we see that our model is performing better on training data than on validation
- changing the activation function
- changing the size of the kernels in our convolutional layers

On the following iterations, we shall also tune the hyper parameters of our model to improve its performance by changing:

- the batch size when we fit our model
- the type of optimizer and / or learning rate
- the number of epochs

At every iteration, we shall record the results obtained along with the changes we made on the model or the hyperparamaters so we can keep track of the whole modeling process.

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

```javascript
if (isAwesome){
  return true
}
```

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 
