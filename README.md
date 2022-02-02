# Federated Learning

> This repository is made for the Network Softwarization course project - Apr 2020.

A brief study on Federated Learning, based on TensorFlow's [Federated Learning for Text Generation](https://www.tensorflow.org/federated/tutorials/federated_learning_for_text_generation) tutorial.

In this project, a model for text generation is built using Federated Learning.
First, a pre-trained Keras model is loaded, and then, it is fine-tuned using federated training.
The reason for taking this approach is thoroughly explained in the [report](/report/report.pdf).

For the pre-trained model, the text from two of the Charles Dickens' books, and for the federated learning part, a federated version of works of Shakespeare provided by TFF is used.

---

#### Sample output after 30 rounds of training:

- Input:
> What of TensorFlow Federated, you ask?

- Output:
> What of TensorFlow Federated, you ask? Shall I<br>
> "Tell me what is it."<br>
> "She had an impact feelly in a traband, and came running at emerge carlied with visible besides anything good remembran every head. My mother in the old law, seeme

#### Performance

![accuracy](/report/accuracy.png)

![loss](/report/loss.png)
