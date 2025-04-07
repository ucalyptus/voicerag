# Customer Support Voice Agent 🎙️

A Streamlit-powered application that converts documentation into interactive voice responses using OpenAI's Text-to-Speech capabilities. This tool helps users get quick, voice-enabled answers to their documentation-related questions.

## Features

- 🔍 Documentation crawling and indexing
- 🔊 Voice-powered responses using OpenAI's TTS
- 💡 Intelligent context-aware answers
- 📚 Vector-based document search
- 🎯 Multiple voice options
- 📥 Downloadable audio responses

## Prerequisites

- Python 3.8+
- OpenAI API key
- Qdrant instance and API key
- Firecrawl API key

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ucalyptus/customer_support_voice_agent.git
cd customer_support_voice_agent
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project root with your API keys:
```env
QDRANT_URL=your_qdrant_url
QDRANT_API_KEY=your_qdrant_api_key
FIRECRAWL_API_KEY=your_firecrawl_api_key
OPENAI_API_KEY=your_openai_api_key
```

## Usage

1. Start the Streamlit application:
```bash
streamlit run script.py
```

2. Configure the system using the sidebar:
   - Enter your API keys
   - Specify the documentation URL
   - Select your preferred voice

3. Ask questions about the documentation and receive both text and voice responses

## Voice Options

The following voices are available:
- alloy
- ash
- ballad
- coral
- echo
- fable
- onyx
- nova
- sage
- shimmer
- verse

## System Components

- **Vector Database**: Uses Qdrant for efficient document storage and retrieval
- **Document Crawler**: Utilizes Firecrawl for documentation scraping
- **Embedding Model**: FastEmbed for text embedding generation
- **Processing Agents**: GPT-4 powered agents for context processing and TTS optimization
- **Voice Synthesis**: OpenAI's TTS model for natural-sounding responses

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[MIT License](LICENSE)

## Support

For support, please open an issue in the GitHub repository or contact the maintainers. 