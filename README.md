# Event-Entry-Predictive-Analysis-and-Clustering

In the domain of event management, accurately predicting attendee access and preferences is crucial. My recent project involved analyzing the 'Event_entry' dataset to identify patterns and construct predictive models that forecast whether an individual's entry to an event would be granted.

To prepare the data for analysis,  encoded categorical variables and partitioned the dataset into training and testing sets. I used PCA analysis to reduce the dimensionality of the dataset and built Logistic Regression models on datasets with 2, 4, and 6 dimensions. Additionally, employed a LASSO Logistic Regression model to evaluate the robustness of the model.

 Also used Decision Tree Analysis to capture the essence of the dataset's predictive signals. The tree's branches were pruned based on the insights garnered from the accuracy assessments using test data, thus ensuring the model's interpretability did not come at the cost of overfitting.

Lastly,  used K Means Clustering to discover natural groupings within the event attendees based on 'Age' and 'Price' alone. Using the Elbow method, determined the optimal number of clusters, which led to a segmentation that was as insightful as it was practical. The visualization of these clusters yielded a map of demographic and economic divides, hinting at potential strategies for targeted marketing and event customization.

In conclusion, my project demonstrates the strength of data-driven decision-making in event management, showcasing how analytical techniques can illuminate the path to strategic and operational excellence.
