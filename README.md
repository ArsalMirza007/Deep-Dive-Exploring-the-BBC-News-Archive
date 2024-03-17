# Explore-BBC-News-Archive

# Instructions:
This code performs the following tasks:

1. **Loading and Pre-processing the Data:**
   - Reads the BBC News dataset from a CSV file.
   - Removes stopwords from the text data.
   - Parses the data from the CSV file into sentences and labels.

2. **Defining Useful Global Variables:**
   - Defines global variables such as `NUM_WORDS`, `EMBEDDING_DIM`, `MAXLEN`, `PADDING`, `OOV_TOKEN`, and `TRAINING_SPLIT` which are used throughout the code.

3. **Training-Validation Split:**
   - Splits the dataset into training and validation sets using a specified proportion.

4. **Tokenization and Padding:**
   - Tokenizes the text data and pads the sequences to the same length for both training and validation sets.

5. **Tokenizing Labels:**
   - Tokenizes the labels and converts them into sequences.

6. **Selecting the Model for Text Classification:**
   - Defines a model architecture for text classification using Keras layers like `Embedding`, `GlobalAveragePooling1D`, and `Dense`.
   - Compiles the model with appropriate loss function and optimizer.
   - Trains the model on the training data and evaluates it on the validation data.
   - Plots the training and validation accuracy and loss graphs.

7. **Optional Exercise - Visualizing 3D Vectors:**
   - Reverse word index and save the embedding layer weights to visualize them in a 3D space using Tensorflow's Embedding Projector.

These tasks collectively prepare, train, and evaluate a model for classifying news articles into different categories based on their text content.
