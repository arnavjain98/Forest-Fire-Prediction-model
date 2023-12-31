# Forest-Fire-Prediction-model
Problem Definition
Natural disasters in general have an adverse effect on all parts of the world, and preventing them has been a challenge since the beginning of human existence. For our project, we would like to focus on forest fires, as we believe they strike the right balance between difficulty of prediction and available data for analysis. A Bankrate study on the effect of forest fires on the United States estimated that wildfires accounted for over $11.2 billion in damage (Sleight, 2022). There are already robust models used by large scale organizations that can make some predictions, but there is no fully operational model.
Figure 1: Firefighters at work during 2020 California Wildfires
Our research will seek to explore data that relates our independent variables (different fire-causing factors) with our dependent variable (whether or not a fire will occur.) Attempting different methods learned in class, our goal is finding data that provides us with enough related information, then creating a model to thoroughly analyze the data to make data based predictions of forest fire occurrences.
Dataset Description
Extensive research has been done to consider the main contributors to forest fires, which in turn would be advantageous to study in preventing them. While searching for useful datasets, we found that one dataset might not have everything we need, so we decided to search for multiple datasets to satisfy our data needs. We have uncovered substantial data on three high level categories: Fire history, Weather Data and Vegetation. This information should be adequate in allowing us to create a potentially successful model.
1. Fire history: This data is primarily obtained from local fire departments that maintain records of past fires in their specific areas, different remote sensing techniques like satellite imagery and from datasets owned by government agencies like the US Forest
 
Service. The data that we would be concentrating on are fire frequency, fire severity and
climate and weather patterns in that particular locality.
2. Weather data: We can obtain this data from weather stations, remote sensing methods
like thermal imaging, rain gauges etc. The parameters that we would like to focus on are
temperature, humidity, precipitation and wind speed and direction.
3. Vegetation: LiDAR is one of the most common methods used to get information on
vegetation in a given area. The variables we’d be considering as part of our model are vegetation type, vegetation moisture and density.
Once we acquire the necessary data, it is subjected to statistical analysis and machine learning algorithms to identify patterns and trends that would be useful to help prevent forest fires.
Proposed Methods
Neural Networks can be a powerful tool for Forest Fire Prediction. Neural networks can capture complex, non-linear relationships between the input features and the target variable, which can be useful in predicting forest fires. Forest fires are influenced by a variety of factors, including temperature, humidity, wind speed and direction, precipitation, and topography. Neural networks can help to identify and model these relationships in a way that traditional statistical models may not be able to.
Another feature of Neural Networks is Pattern Recognition. They are excellent at recognizing the patterns and making predictions based on those patterns. The historical data might come into effect as it can help to identify areas at risk and give us the trend for the recurring patterns.
Neural Networks are able to adapt and learn from new data, which can be useful in a dynamic environment like a forest. As the conditions change, the neural networks can adjust its outcomes based on the new data. It can also handle large amounts of data which is necessary when building a forest fire prediction model. By training the neural network on a large dataset, it can learn to make more accurate predictions.
Training and Evaluation
The data is going to be split by the common split ratio of 80:20, where 80% of the data will be used for training and 20% of the data will be used for testing. We will also be using randomization before splitting the data to avoid biases. We will also be cross-validating the model. This will involve splitting the datasets into multiple parts, training the model on one end and testing it on remaining. It will help reduce the impact of random variations in the training and testing datasets and provide a more robust evaluation of our model.
The performance metrics used for evaluating this model include- Precision recall curve and ROC curve.
Conclusion
With this project, we aim to develop a fully functioning model that would help us accurately manage and prevent forest fires before they cause extensive damage to forest ecosystems and wildlife habitats.
