# CMBF: Cross-Modal-Based Fusion Recommendation Algorithm

[Paper](https://www.mdpi.com/1424-8220/21/16/5275)

Some of the competing multi-modal recommender algorithm:

1. [VBPR](https://arxiv.org/abs/1510.01784): Visual Bayesian Personalized Ranking from Implicit Feedback
    
    incorporates visual information into the recommendation model, which is a significant improvement over the matrix decomposition model that relies on the hidden vectors of users and items.
    
2. [MLFM](https://arxiv.org/abs/1907.05576): Neural News Recommendation with Attentive Multi-View Learning
    
    multi-modal post-fusion classification method based on text and images. It uses machine learning models to extract text and image features, learns specific classifiers for each modality, and then learns fusion strategies from the results of each modality classifier.
    
3. [DICM](https://arxiv.org/pdf/1711.06505.pdf): Image Matters: Visually modeling user behaviors using Advanced Model Server
    
    this method extracts user visual preference features using the item image features of the user’s historical behavior and the image features of the target item, stitches them with the user’s ID features and the image features of the target item, and inputs them into a deep neural network for click-through rate prediction.