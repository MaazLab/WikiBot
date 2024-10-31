# WikiBot

**WikiBot** is a basic chatbot that uses Langgraph and groq to retrieve information directly from Wikipedia. The bot is designed to answer general knowledge questions efficiently, using the `Gemma2-9b-It` model. Currently, the project is set up in a Jupyter notebook, and future enhancements include a UI built with Streamlit or Gradio, complete with image features.

## Features

- **Knowledge Source**: Uses Wikipedia as a knowledge base.
- **Model**: Powered by the `Gemma2-9b-It` model.
- **Langgraph Integration**: Simplifies the integration of NLP and groq.
- **Future UI**: Planned support for a user interface with image capabilities using Streamlit or Gradio.

## Requirements

- Python 3.8 or later
- Jupyter Notebook
- Langgraph
- groq library

## Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/WikiBot.git
   cd WikiBot

2. **Install Dependencies**

    Use the following command to install required libraries:
    
    ```bash
    pip install -r requirements.txt

3. **Set Up API Key**
    
    You'll need a GROQ_API_KEY to access the groq API.
    - Create a ```.env``` file in the root directory of the project.
    - Add your API key to the ```.env``` file as follows:
    ```bash
    GROQ_API_KEY=your_groq_api_key_here

## Usage
    
In the notebook, you can interact with the chatbot by entering your questions in the specified cell
WikiBot will fetch answers using Wikipedia and display them in the output.


## Future Development

- **UI**: A more interactive UI will be developed using Streamlit or Gradio.
- **Image Support**: Future versions will include image generation and display capabilities.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have ideas or improvements.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software for both commercial and non-commercial purposes, as long as you include the original license. See the [LICENSE](LICENSE) file for full details.

## Note
This project is still in its early stages. Stay tuned for updates as more features are added!