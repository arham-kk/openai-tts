# OpenAI Text-To-Speech

## Overview

This repository features a Gradio interface designed to leverage the OpenAI Text-To-Speech (TTS) API. The interface lets users create speech from provided text using different models and voice options.

### Getting Started

To begin using this interface, follow these steps:

1. Clone this repository to your local machine.
    ```bash
    git clone https://github.com/arham-kk/openai-tts.git
    cd openai-tts
    ```

2. Install the required dependencies.
    ```bash
    pip install -r requirements.txt
    ```

### Requirements

Ensure that the following dependencies are installed:

- `gradio`
- `openai`

You can install them using:
```bash
pip install -r requirements.txt
```

## Usage

1. Obtain an OpenAI API key and enter it into the provided textbox.
2. Choose a TTS model (`tts-1` or `tts-1-hd`) and a voice option from (`alloy`, `echo`, `fable`, `onyx`, `nova`, `shimmer`).
3. Input the desired text into the input textbox.
4. Click the "Generate" button or press Enter to create the corresponding speech.
5. The generated speech will be displayed as an audio output.

## Code Structure

The code is organized into two main components:

- `tts`: This module contains the function responsible for interacting with the OpenAI API to generate speech.
- `gradio_interface`: This module sets up the Gradio interface, including input fields, buttons, and the speech output.

## Setup

Follow these steps to set up and run the Gradio interface:

1. Obtain your OpenAI API key.
   - If you don't have an API key, sign up for one on the [OpenAI website](https://beta.openai.com/signup/).
   - Replace the placeholder in the interface with your API key.

2. Run the Gradio interface.
    ```bash
    python app.py
    ```

3. Input your text and choose the desired model and voice options.

4. Click the "Generate" button or press Enter to generate speech.


## License

This code is provided under the [MIT License](https://opensource.org/licenses/MIT). Feel free to modify and distribute it as needed.
