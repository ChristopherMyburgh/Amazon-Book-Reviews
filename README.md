# Amazon-Book-Reviews
Using NLP to perform Semantic Analysis to determine whether or not a review can be classified as positive or negative.

A initial Data exploration was conducted to validate the distribution of reviews. It was found that the mean words per review was 4.34 words. This mean was used to create a a max length of 4 during the tokenization process. 
The project uses Recurrent Neural Networks to achieve the task. 6 Models have been employed within this task. All 6 are built on the same architecture, while only
the hyperparameters of each has been modified. Each model contains a different batch size and output dimension. All models were run over 20 epochs  
