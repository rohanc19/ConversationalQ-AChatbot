# Gemini AI Assistant

## Overview

Gemini AI Assistant is a Streamlit-based web application that leverages Google's Gemini AI model to provide intelligent responses to user queries. This interactive chat interface allows users to engage in conversations with the AI, making it an excellent tool for information retrieval, problem-solving, and general assistance.

## Features

- Real-time chat interface with Gemini AI
- Streaming responses with a typing effect for a more engaging experience
- Chat history management
- Option to clear chat history
- Responsive design suitable for both desktop and mobile devices

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- A Google API key for Gemini AI

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/gemini-ai-assistant.git
   cd gemini-ai-assistant
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Create a `.env` file in the project root and add your Google API key:
   ```
   GOOGLE_API_KEY=your_api_key_here
   ```

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

3. Start chatting with the Gemini AI Assistant by typing your messages in the input box and pressing Enter or clicking the Send button.

4. View the chat history in the main chat window.

5. Use the "Clear Chat History" button to start a new conversation.

## Customization

You can customize the application by modifying the following:

- Change the model: Update the `model = genai.GenerativeModel("gemini-pro")` line to use a different Gemini model.
- Adjust the UI: Modify the Streamlit components in the code to change the layout or add new features.
- Enhance prompts: Customize the initial messages or add system prompts to guide the AI's behavior.

## Contributing

Contributions to the Gemini AI Assistant are welcome. Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch-name`.
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google for providing the Gemini AI API
- Streamlit for the excellent web app framework
- The open-source community for various helpful libraries

## Contact

If you have any questions or feedback, please open an issue on the GitHub repository.

Happy chatting with Gemini AI!
