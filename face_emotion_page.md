## Face Emotion project page

**Executive Summary** 

This deep learning project proposes the Complex Convolutional Neural Network (CNN) for the accurate detection of facial emotions. The dataset provided to train the models is composed of small size grayscale images of faces expressing four types of emotion: happy, sad, neutral or surprised. Using Transfer Learning did not prove beneficial in classifying the images of the given dataset. The performance of these pre-built architectures was lower than expected so building a more complex but flexible CNN model was the best approach to work with the specific dataset. The suggested model achieved high performance with 82% accuracy. However, it is subject to a number of limitations, including the lower accuracy in predicting certain classes, and when facial occlusion is present. Its computation efficiency is also linked to the volume and size of images to be processed. It is recommended that stakeholders consider these limitations and challenges in building an improved and robust predictive model, as well as use a larger and more diverse training dataset, explore data augmentation techniques to improve the model’s accuracy and evaluate the trade off of developing a more complex but more computationally expensive model.

### Workflow Summary

Below is a diagram explaining our workflow. We shall build different 6 models, train each model on the training dataset, monitor the performance of the model on the validation dataset and evaluate the model on the test dataset using the metric 'accuracy'.

We shall use the color modes grayscale (g) and RGB (rgb) for the input images of our model and see which color mode gives the best performance. For the Transfer Learning Architecture models, only RGB color mode will be used. We shall use Data Loaders to load and preprocess image data efficiently and effectively.

During training, we shall use the categorical cross-entropy loss function because the task is a multi class prediction. The loss is the difference between the true class probabilities and the predicted class probabilities.

Then we shall compare and evaluate each model, and choose the best one to solve our task.

Finally, with the chosen model, we will predict the classes of emotions on the test data and generate a classification report and a confusion matrix to gain more insight on the performance of the chosen model and identify areas we can improve. 

<img src="images/‎modeling_workflow.png?raw=true"/>

### 2. Assess assumptions on which statistical inference will be based

```javascript
if (isAwesome){
  return true
}
```

### 3. Support the selection of appropriate statistical tools and techniques

<img src="images/dummy_thumbnail.jpg?raw=true"/>

### 4. Provide a basis for further data collection through surveys or experiments

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 
