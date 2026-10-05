# Next-Word Prediction Using LSTM

A deep learning project that predicts the next word in a sequence using a Long Short-Term Memory (LSTM) neural network.

## 📌 Project Overview

Next-word prediction is a Natural Language Processing (NLP) task where a model learns patterns from a sequence of words and predicts the most likely word that comes next.

This project uses an LSTM-based neural network to learn word sequences from a text dataset. The trained model can then generate predictions based on the words provided as input.

## 🎯 Objective

To build an LSTM neural network capable of learning sequential language patterns and predicting the next word based on a given sequence of preceding words.

## 🧠 How It Works

The project follows these main steps:

1. Text data is collected and prepared for training.
2. The text is tokenized into numerical sequences.
3. Input sequences and their corresponding target words are created.
4. The sequences are converted into a suitable format for model training.
5. An LSTM neural network is trained on the prepared sequences.
6. The trained model learns relationships between words in a sequence.
7. Given a sequence of words, the model predicts the most probable next word.

## 🏗️ Model Architecture

The LSTM model consists of:

* **Embedding Layer** – Converts word indices into dense vector representations.
* **LSTM Layer** – Learns dependencies and patterns within word sequences.
* **Dense Layer** – Produces probability scores for the possible next words.
* **Softmax Activation** – Converts the scores into a probability distribution.

### Model Flow

```text
Input Word Sequence
        ↓
Tokenization
        ↓
Embedding Layer
        ↓
LSTM Layer
        ↓
Dense Layer
        ↓
Softmax
        ↓
Predicted Next Word
```

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Natural Language Processing (NLP)
* Long Short-Term Memory (LSTM)
* Jupyter Notebook

## 📂 Project Structure

```text
dlrl_proj/
│
├── next_word_lstm.ipynb
├── next_word_lstm.keras
├── tokenizer.json
├── config.json
├── README.md
└── .gitignore
```

## 📄 Files Description

| File                   | Description                                                                           |
| ---------------------- | ------------------------------------------------------------------------------------- |
| `next_word_lstm.ipynb` | Jupyter Notebook containing data preparation, model building, training and prediction |
| `next_word_lstm.keras` | Saved trained LSTM model                                                              |
| `tokenizer.json`       | Saved tokenizer used for converting words into numerical sequences                    |
| `config.json`          | Configuration information associated with the model                                   |
| `README.md`            | Project documentation                                                                 |
| `.gitignore`           | Specifies files that should not be tracked by Git                                     |

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Open the Project

Navigate to the project directory:

```bash
cd Next-Word-Prediction-LSTM
```

### 3. Install Dependencies

Install the required Python libraries:

```bash
pip install tensorflow numpy jupyter
```

### 4. Run the Notebook

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
next_word_lstm.ipynb
```

Run the notebook cells in sequence.

## 🔮 Example

The model can take a sequence such as:

```text
Artificial intelligence is
```

and predict a probable next word based on the patterns learned during training.

The exact prediction depends on the training dataset and the trained model.

## 📊 Training

The model is trained using:

* **Optimizer:** Adam
* **Loss Function:** Categorical Cross-Entropy
* **Output Activation:** Softmax
* **Model Type:** Sequential LSTM Network

The notebook also contains the training process and performance visualization.

## 🔬 Applications

Next-word prediction can be used as a foundation for:

* Smart text input systems
* Autocomplete applications
* Chatbots
* Text generation
* Language modeling
* Writing assistance tools

## 🔮 Future Enhancements

Possible improvements include:

* Training on a larger and more diverse dataset
* Using multiple LSTM layers
* Implementing bidirectional LSTM
* Adding temperature-based text generation
* Developing a web-based prediction interface
* Deploying the model as an API
* Comparing LSTM with GRU and Transformer-based models

## 👩‍💻 Author

**Thrisha Acharya**

Bachelor of Engineering – Artificial Intelligence and Machine Learning
Canara Engineering College, Mangalore

---

⭐ If you find this project useful, consider giving the repository a star!
