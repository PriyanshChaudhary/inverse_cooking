# inverse_cooking
This model allows you to know how a dish came to life. The ingredients, the process, everything that was reqd. to make it from an image of the dish itself.
If you are already an ML learner or even a beginner in this field, you might have thought of how this model was built.
Well the first thing that comes to mind is image recognition of the food and then predicting the dishes on the model trained on a large dataset. 

Congratulations,
if you've thought along these lines you have made a good invesment of your time in this field. But you are half right. Though indeed we did an image prediction on the images, we instead of an entire inage were more focused on the ingredient pipeline.
# OVERVIEW
When you finally go to a restaurant that you always wanted to go, step inside and order that dish that you always dreamt yourself eating, wanted to know how that food came to fruition, what magic was involved in making that fine masterpiece but never had the chance to. Fortunately, we have machine learning for our rescue. In this project, I have introduced a model that runs on a machine learning platform which can help one identify the name and the recipe used in order to make the dish. This machine learning model is based on a theory by making an extension of the retrieval system to a cross-validation embedded system which allows it to extract the ingredient embeddings from an image of the food and identify the correct name & recipe by cross-validating with the Recipe1M dataset. The model then identifies the ingredients and the relative image with the dataset simultaneously to produce the optimum results.

# Implementation
with the help of this model one is able to procure the recipe and name of the dish depicted in the image. In this model, we have produced a method for extracting the details of the dish using two modalities: the ingredients and the image of the food itself. Using these two modalities together, this model is able to achieve the higher threshold of accuracy in comparison to the previously built models.
