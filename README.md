# Quantum Shield Chatbot

This is a chatbot application built using Python's `tkinter` library for the GUI and Google's GeminiAI for generating responses. The chatbot provides a user-friendly interface for interacting with the AI model.

## Features

- **Team Branding**: Displays the team name and logo.
- **User Input**: Allows users to enter their name and start a chat session.
- **Chat Display**: Shows the conversation between the user and the chatbot.
- **Message Entry**: Users can type their messages and send them to the chatbot.
- **AI Response**: The chatbot generates responses using the GeminiAI model.

## Requirements

- Python 3.x
- `tkinter` library (usually included with Python)
- `Pillow` library for image handling
- `google-genai` library for AI model interaction

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/quantum-shield-chatbot.git
    cd quantum-shield-chatbot
    ```

2. Install the required libraries:
    ```sh
    pip install pillow google-genai
    ```

3. Update the [TEAM_IMAGE_PATH](http://_vscodecontentref_/0) in the code with the actual path to your team logo image.

4. Set your GeminiAI API key in the code:
    ```python
    client = genai.Client(api_key="YOUR_GEMINIAI_API_KEY")
    ```

## Usage

1. Run the application:
    ```sh
    python Hackindia.py
    ```

2. Enter your name in the input field and click "Start Chat" to begin the conversation.

3. Type your messages in the message entry field and click "Send" to interact with the chatbot.

## Code Overview

- **Main File**: `Hackindia.py`
- **Libraries Used**:
  - [tkinter](http://_vscodecontentref_/1): For creating the GUI.
  - `Pillow`: For handling images.
  - [google-genai](http://_vscodecontentref_/2): For interacting with the GeminiAI model.

## Example

![Chatbot UI](screenshot.png)

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [Google GeminiAI](https://cloud.google.com/genai) for providing the AI model.
- [Pillow](https://python-pillow.org/) for image handling.
- [tkinter](https://docs.python.org/3/library/tkinter.html) for the GUI framework.