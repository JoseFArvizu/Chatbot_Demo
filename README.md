
# Simple Chatbot using OpenAI API

This project contains a simple chatbot implemented in a Jupyter Notebook using OpenAI's API. It uses a basic user interface built with IPython widgets to interact with the model and provides a foundation for experimenting with GPT-style chat functionality.

---

## Files

- `Simple_Chatbot.ipynb`: Main notebook that runs the chatbot UI and connects to the OpenAI API.
- `config.py`: Stores your API key. Make sure to replace `'API_Key'` with your actual key.

---

## Features

- Simple chatbot interface using `ipywidgets`
- Interacts with OpenAI's language model (`gpt-3.5-turbo`)
- Supports interactive input/output in a notebook environment

---

## Installation

Before running the notebook, make sure you have Python 3.7+ and the required libraries installed. You can install them using:

```bash
pip install openai ipywidgets
```

Make sure to enable `ipywidgets` in Jupyter:

```bash
jupyter nbextension enable --py widgetsnbextension --sys-prefix
```

---

## Setup

1. Clone this repository or download the files.
2. Install the dependencies (see above).
3. Open `config.py` and replace:

   ```python
   api_key = 'API_Key'
   ```

   with your actual OpenAI API key.

4. Run the notebook `Simple_Chatbot.ipynb` in Jupyter.

---

## Usage

1. Open the notebook.
2. Enter your message into the text input.
3. Click the “Send” button or press Enter.
4. View the chatbot’s response below.

---

## Notes

- Ensure your API key has access to the `gpt-3.5-turbo` model or whichever model you're calling.
- This project is intended for educational and prototyping purposes.
