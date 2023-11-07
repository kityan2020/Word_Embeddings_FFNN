# Word_Embeddings_FFNN

# Word Embeddings
Here was a very fun and interesting assignment that I worked on in a graduate Natural Language Processing class. In Part I of the assignment, it focused on anaylzing all of William Shakespeare's play and the total lines spoken in each play. From that data, I generated a documented term matrix and plot the data into the graph to represent the similarity of each plays based on the lines spoken. I used CountVectorizer and TFIDF Vectorizer objects to anaylze the difference of the graph data when each was used. Repeated the process by anaylzing the characters lines being spoken from each play. Then, I worked on a generating word embeddings starting out with a Do it yourself Word Embedding to understand the process of how word embeddings are created for each play. Then, I tested out the Word2Vec object from gensim.models to generate the word embeddings more easier based on each word spoken in each play. Repeted the same process for anaylzing the players as well

# Classifying text with a Feed-Forward Neural Network
Created a simple Feed-Forward Neural Network that helps classifying emails from the Enron dataset to classify whether or not an email is a spam. I used the Glove pretrain word embeddings based in order to get the word_embedding vector for each word in the email dataset. Finally, I used PyTorch and separated the dataset with a 80% training set, 10% validation set, and 10% testing set along with creating 3 dataloader to feed each dataset to train our model with PyTorch. For this structure of the model, I used a linear layer with a 100 x 15 dimension for the input size, the Rectified Linear unit ReLu activation layer and finally, an output linear layer with a dimension of 15 x 2. I set the batch size to 128 going through 100 epochs of the dataset. The end result was 96.5% test accuracy of accurately classifying emails to be either spam or not spam. 

Overall, a very fun assignment to do! :slightly_smiling_face:
