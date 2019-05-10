# Skip_gram
###
<strong>It implements skip gram (Word2Vec) model in pytorch.</strong>

### Dateset
Dataset can be downloaded from https://s3.amazonaws.com/video.udacity-data.com/topher/2018/October/5bbe6499_text8/text8.zip . It should be kept in the same directory as the notebook file. 

### Model description
Code for the LSTM is provided in the notebook Word2Vec.ipynb. The model is created in the class named SkipGram.
1. Model Structure
     * We are using skip gram Word2Vec model with 300 dimension embedding layer followed by log_softmax.
     * Cosine similarity is used to find words with similar context on each epoch.
  
2. Loss : Negative Log Likelihood Loss.

3. Optimizer : Adam optimizer.

### Usage
To use the code, execute all the cells in the notebook and get the required embeddings from the model's embedding layer.
      
### How to Contribute
Find any typos? Have another resource you think should be included? Contributions are welcome!

* Fork this repository.

* Clone the repository to your desktop to make changes.

      $ git clone {YOUR_REPOSITORY_CLONE_URL}

* Issue a pull request by clicking on the green pull request icon.

Instead of cloning the repository to your desktop, you can also go to README.md in your fork on GitHub.com, hit the Edit button (the button with the pencil) to edit the file in your browser, then hit the Propose file change button, and finally make a pull request.

### License
This repository has been licensed under Apache 2.0.

