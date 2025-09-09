Takes text input from the user and gives a response using a transformer model.

Uses Hugging Face Transformers library.

Helps us understand attention mechanism, embeddings, and transfer learning.

Can be extended in the future to a full chatbot app.

             Tools & Tech

Python 3.x

Hugging Face Transformers

PyTorch / TensorFlow

Jupyter Notebook / VS Code

Chatbot-using-Transformers/
│── chatbot/            # main chatbot code
│── tests/              # testing files
│── setup.py            # installation file
│── requirements.txt    # dependencies
│── README.md           # this file :)


How to Run

git clone https://github.com/annubhhavv/Chatbot-using-Transformers.git
cd Chatbot-using-Transformers

pip install -r requirements.txt

python chatbot/main.py

                  Future Plans

Since we are still learning, there are many things we want to add later:

Fine-tuning the model on our own dataset.

Adding memory so the chatbot remembers the conversation.

Deploying on web using Flask / Streamlit.

Evaluating chatbot with metrics (BLEU, ROUGE).

