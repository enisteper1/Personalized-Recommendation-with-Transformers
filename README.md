# Personalized Recommendation with Transformers

<td>
<a target="_blank" href="https://medium.com/hepsiburada-data-science/personalized-recommendations-with-transformers-11c13cff2be">
<img src="https://github-production-user-asset-6210df.s3.amazonaws.com/45767042/259043664-1045243a-e7b4-46d5-a06e-7aa7d6477dec.png" width=32 height=32 />Read on Medium</a>
</td>
&nbsp
<td>
<a target="_blank" href="https://colab.research.google.com/github/enisteper1/Personalized-Recommendation-with-Transformers/blob/main/Personalized_Recommendation_with_Transformers.ipynb">
<img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run in Google Colab</a>
</td>
<br/><br/>
 
This repository contains a guide and the associated code to build a personalized movie recommendation system using the Transformer model. Using the MovieLens dataset, we explore how to preprocess data, define our model, and generate recommendations based on user interactions.

## Contents
1. **Data Preprocessing**: The MovieLens dataset is loaded and preprocessed. We construct vocabularies for movie ids and user ids, and create sequences of user interactions. This process converts the data into a format suitable for our recommendation model. This includes the following sub-steps:

    1.1 **Loading Dataset**
   
    1.2 **Creating Vocabulary**
   
    1.3 **Generating Sequences**
   
    1.4 **Train Test Split**
2. **Model Definition**: We define and initialize our Transformer model, which will be trained using our preprocessed dataset. The steps include:

    2.1 Positional Encoder: A positional encoder is defined for the Transformer, embedding order information required by the model.
   
    2.2 Transformer Model: The transformer model, taking both user id and movie id sequences as input, is defined and initialized. The model generates movie recommendations.
   
3. **Training and Evaluation**: The model is trained using our dataset, after which we evaluate its performance on unseen data. We also generate popular movie recommendations as a baseline to compare the success of our model. At the end, we compare our results with a normalized discounted gain (NDCG) metric, revealing that our model outperforms the baseline.

4. **Conclusion**: This repository provides a comprehensive guide on how to create a personalized movie recommendation system using Transformer models, highlighting their potential use in diverse contexts beyond natural language processing.

<h3 align=left> An Example of Sequence to Recommendation </h3>
<h4 align=left> User Movie Sequence </h3>
<img src="https://github.com/enisteper1/Personalized-Recommendation-with-Transformers/assets/45767042/0af22b19-0614-409b-9c06-bc7ab8690d09">

<h4 align=left> Transformer Model Recommendations </h3>
<img src="https://github.com/enisteper1/Personalized-Recommendation-with-Transformers/assets/45767042/d27bc2cc-1122-4585-ae68-d42066515a6d">


<h4 align=left> Popular Movie Recommendations </h3>
<img src="https://github.com/enisteper1/Personalized-Recommendation-with-Transformers/assets/45767042/735af29d-47e3-4e5b-aa3b-ab1b0237bd83">
