# 🤖 Chat Bot V1

Welcome to **Chat Bot V1**, a simple yet entertaining chatbot that can respond to various user inputs with witty, humorous, and sometimes cynical replies. The bot is built using Python and leverages natural language processing (NLP) techniques to understand and respond to user queries.

## 🌟 Features

- **Humorous Replies**: The bot is designed to respond with funny and sarcastic comments.
- **Weather and AI Jokes**: Built-in knowledge about weather and artificial intelligence with a humorous twist.
- **Dynamic Conversation**: The bot can handle various greetings, farewells, and common phrases, making the conversation flow naturally.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Antot-12/Chat-Bot-V1.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd Chat-Bot-V1
   ```
3. **Install required dependencies**:
   Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```
   If `requirements.txt` is not provided, manually install the dependencies:
   ```bash
   pip install numpy scikit-learn nltk
   ```

4. **Download NLTK resources**:
   The chatbot uses NLTK for text processing. You need to download the necessary resources:
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('wordnet')
   ```

## 🚀 Usage

To start the chatbot, simply run the `chat_bot.py` script:

```bash
python chat_bot.py
```

Once the chatbot starts, you can type your messages, and it will respond with something witty or sarcastic. If you want to exit the conversation, simply type `вихід` or `прощавай`.

## 🧠 How It Works

- **Lemmatization**: The bot processes user inputs by breaking them down into their root forms using NLTK’s WordNetLemmatizer.
- **Text Vectorization**: It then vectorizes these inputs using `CountVectorizer`.
- **Naive Bayes Classifier**: The chatbot uses a Multinomial Naive Bayes model to classify the input and predict the appropriate response category.
- **Random Responses**: For a more human-like interaction, the bot picks a random response from the predefined list corresponding to the predicted category.

## 🎉 Acknowledgments

- **NLTK**: For providing an extensive suite of NLP tools.
- **Scikit-learn**: For making machine learning in Python straightforward.
- **You**: For trying out Chat Bot V1!

---

Happy chatting! 😄
