# AI Chatbot with Streamlit Interface

A modern chatbot application built using Google's Gemini AI model with a clean Streamlit interface.

## Features

- Real-time chat interface
- Powered by Google's Gemini Pro 1.5 AI model
- Modern and responsive design
- Message history tracking
- Easy-to-use interface
- Built-in deployment options

## Prerequisites

- Python 3.x
- Google Gemini API key

## Required Python Packages

```
streamlit
python-dotenv
google-generativeai
```

## Setup

1. Clone this repository or download the files
2. Create a `.env` file in the project root directory
3. Add your Gemini API key to the `.env` file:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

## Installation

1. Create a virtual environment:
   ```
   python -m venv venv
   ```

2. Activate the virtual environment:
   - Windows:
     ```
     .\venv\Scripts\activate
     ```
   - Linux/Mac:
     ```
     source venv/bin/activate
     ```

3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Application Locally

1. Make sure your virtual environment is activated
2. Run the Streamlit app:
   ```
   streamlit run streamlit_app.py
   ```
3. The app will automatically open in your default web browser

## Deployment

The application can be easily deployed to Streamlit Cloud:

1. Push your code to a GitHub repository
2. Go to [share.streamlit.io](https://share.streamlit.io/)
3. Sign in with your GitHub account
4. Click on "New app"
5. Select your repository and the `streamlit_app.py` file
6. Add your `GEMINI_API_KEY` as a secret in the Streamlit Cloud dashboard

## Project Structure

- `streamlit_app.py` - Main application file with Gemini AI integration
- `requirements.txt` - Python package dependencies
- `.env` - Environment variables (API key)
- `README.md` - Project documentation

## Usage

1. Start the application using the instructions above
2. Type your message in the input field
3. Press Enter to send your message
4. The AI will respond in real-time

## Security Notes

- Keep your API key secure and never commit it to version control
- Use environment variables for sensitive information
- For production deployment, use Streamlit Cloud's secrets management

## Development

The project uses:
- Streamlit for the web interface
- Google's Generative AI for chat responses
- Modern UI components
- Session state management

## License

This project is open source and available under the MIT License.
