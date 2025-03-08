# 🎬 AI Movie Recommendation Agent

[![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)](https://www.python.org/downloads/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-green.svg)](https://openai.com/)
[![Agno](https://img.shields.io/badge/Agno-Framework-orange.svg)](https://github.com/agno-agi/agno)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115+-brightgreen.svg)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An intelligent movie recommendation system built with Python, leveraging OpenAI's GPT-4 and Exa tools to provide personalized movie suggestions based on user preferences.

## 🌟 Features

- **Personalized Recommendations**: Tailored movie suggestions based on user preferences and viewing history
- **Comprehensive Movie Details**: Including ratings, runtime, language, and content advisories
- **Interactive Web Interface**: Easy-to-use playground for querying recommendations
- **Real-time Updates**: Latest movie information and trending films
- **Structured Output**: Well-formatted responses with detailed movie information
- **Multi-criteria Search**: Filter by genre, rating, language, and more

## 🚀 Getting Started

### Prerequisites

- Python 3.12 or higher
- OpenAI API key
- Exa API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/pakagronglb/agent-movie-exa-recommendation.git
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -U agno fastapi uvicorn
```

4. Create a `.env` file in the project root:
```env
OPENAI_API_KEY="your-openai-api-key"
EXA_API_KEY="your-exa-api-key"
```

### Usage

Run the application:
```bash
python agent_movie_recommendation.py
```

Access the playground:
- Local endpoint: http://localhost:7777
- Agno playground: https://app.agno.com/playground?endpoint=localhost%3A7777

## 💡 Example Queries

- "Recommend me some sci-fi movies similar to Inception"
- "What are the best comedy movies from 2023?"
- "Show me highly-rated drama movies with strong female leads"
- "Find me movies like The Dark Knight"

## 🎯 Features in Detail

### Movie Information Provided
- 🎬 Title & Release Year
- 🎭 Genre & Subgenres
- ⭐ IMDb Rating
- ⏳ Runtime & Primary Language
- 📖 Plot Summary
- 🔞 Content Advisory
- 🎥 Cast & Director

### Recommendation Approach
- Analyzes user preferences
- Curates diverse selections
- Includes classic and contemporary films
- Provides streaming availability
- Suggests similar movies

## 🛠️ Technical Details

- **Framework**: Agno AI Framework
- **API**: OpenAI GPT-4
- **Search Tools**: Exa
- **Web Framework**: FastAPI
- **Environment Management**: python-dotenv

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Credits

This project is based on the tutorial by [Jie Jenn](https://youtu.be/kC2EIzjQOMY). Special thanks for the excellent guidance and inspiration.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📧 Contact

For questions and support, please open an issue in the repository. 