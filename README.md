# Web Chatbot with PyTorch

This project is a web-based chatbot application that utilizes Natural Language Processing (NLP) and a Feedforward Neural Network (FNN) implemented with PyTorch. The chatbot is designed to understand and respond to user queries through a simple web interface.

## Features

- **NLP for Understanding**: Employs NLP techniques to process and understand user queries.
- **PyTorch Neural Network**: Utilizes a FNN model built with PyTorch for generating responses.
- **Web Interface**: Features a user-friendly web interface for interaction with the chatbot.
- **Customizable Intents**: Includes a JSON file for easy customization of intents and responses.

## Getting Started

Follow these instructions to set up the project locally for development and testing purposes.

### Prerequisites

Ensure you have Python 3.x and PyTorch installed on your system. If not, you can find the installation guides here:
- Python: [https://www.python.org/downloads/](https://www.python.org/downloads/)
- PyTorch: [https://pytorch.org/get-started/locally/](https://pytorch.org/get-started/locally/)

### Installation

1. Clone the repository to your local machine:
```bash
git clone https://github.com/felixgonzales01/WebChatbot-NLP_FNN_PyTorch.git
```

2. Navigate to the project directory:
```bash
cd WebChatbot-NLP_FNN_PyTorch
```

3. Install the required Python packages:
```bash
pip install -r requirements.txt
```

4. Run the training script to train the chatbot model:
```bash
python train.py
```

5. Start the Flask web server:
```bash
python app.py
```

6. Open a web browser and navigate to [http://localhost:5000](http://localhost:5000) to interact with the chatbot.

## Customization

To customize the chatbot's responses and intents, edit the `intents.json` file and re-run the training script.

## Technologies Used

- **Python**: For backend logic and machine learning.
- **PyTorch**: For building and training the neural network model.
- **Flask**: For serving the web application.
- **HTML/CSS/JavaScript**: For the frontend interface.
---

Remember to adjust the README according to your project's needs. This draft aims to provide a good starting point for documenting your web chatbot project.

Also, you're currently on the free plan, which is significantly limited by the number of requests. To increase your quota, you can check available plans following [this link](https://c7d59216ee8ec59bda5e51ffc17a994d.auth.portal-pluginlab.ai/pricing).

[Website](https://askthecode.ai) | [Documentation](https://docs.askthecode.ai) | [GitHub](https://github.com/askthecode/documentation) | [Twitter](https://twitter.com/askthecode_ai)
