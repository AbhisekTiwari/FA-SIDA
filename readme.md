# Medical department classification


## To train on Meddialog dataset

1. Download the department tagged dataset.
2. Install the dependencies.
3. Locate the training and testing datasets.
4. [Optional] Change the parameters (batch_size, lr, epochs etc).
5. To use bert-pubmed embedding
``` 
encoder = hub.KerasLayer("https://tfhub.dev/google/experts/bert/pubmed/2")
```
<br>

5. To use bert-based embedding
``` 
encoder = hub.KerasLayer("https://tfhub.dev/tensorflow/bert_en_uncased_L-12_H-768_A-12/4")
```
6. Run the notebook on google colab.
7. Model will be trained and best checkpoint will be saved.


# Medical description generation

## To train for description generation from patient dialogue
1. Download the Meddialog dataset.
2. Install the dependencies.
3. Locate the training and testing datasets.
4. [Optional] Change the parameters (batch_size, lr, epochs etc).
5. Run the notebook on google colab on DialoGPT.
6. Run the notebook on google colab on BART.

