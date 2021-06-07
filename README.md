# Food ordering chatbot

***This application was developed as a project under the CS-510 (Introduction to Artificial Intelligence) course at Drexel University.***

A food ordering smart assistant trained using a multi-layer perceptron neural network on restaurant corpus in python.

### Execution Steps:

Install external libraries and packages:

```
pip install nltk
pip install tflearn
pip install tensorflow
pip install numpy
pip install scikit-learn
```

Download all nltk data using python:

```
import nltk
nltk.download()
```

Train the model:
execute all rows in "training.ipynb"

(The model and pickle object will save automatically)

Once the model is trained start the chat bot using the command:

```
python3 chatbot.py
```

Evaluate the model:
execute all rows in "evaluate.ipynb"
