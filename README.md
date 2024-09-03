# WanderWithDevesh

WanderWithDevesh is a web application that transforms natural language queries into SQL queries, executes them, and displays user-friendly responses. This tool simplifies database interactions for users who may not be familiar with SQL syntax.

## Live Application

[![Live Application](https://img.shields.io/badge/Live%20Application-<COLOR>?style=for-the-badge&logo=<LOGO>&logoColor=white)]()

## Video Demo

[![Video Demo](https://img.shields.io/badge/Video%20Demo-<COLOR>?style=for-the-badge&logo=<LOGO>&logoColor=white)]()

## Documentation

[![codelabs](https://img.shields.io/badge/codelabs-4285F4?style=for-the-badge&logo=codelabs&logoColor=white)]()

## Features

<img width="1280" alt="Screenshot 2024-02-28 at 12 36 02 PM" src="https://github.com/deveshcode/GPT-WanderWithDevesh/assets/37287532/2d7da0b1-0eb6-4164-b3cd-221cca06d372">

- Natural Language Processing: Convert natural language questions into executable SQL queries.
- Query Execution: Run SQL queries directly from natural language input.
- Results Formatting: Display results in a human-readable format.
- Interactive Explainer: Visual flow from natural language question to SQL query to formatted answer.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

- Prerequisites
- Node.js
- React
- FastAPI
- Uvicorn (for serving FastAPI)
- OpenAI API key (for natural language processing)

## Installation

1. Git clone the repository:

```bash
git clone https://github.com/deveshcode/shopping-multimodal-rag.git
cd shopping-multimodal-rag
```

2. Install the required packages:

```bash
cd frontend
npm install
cd ../backend
pip install -r requirements.txt
```

3. Create a .env file in the root directory and add your API keys:

```bash
OPENAI_API_KEY=your_openai_api_key
```

## Running the Application

1. Start the backend server:

```bash
cd backend
uvicorn main:app --reload
```

2. Start the frontend development server

```bash
cd frontend
npm start
```

Open your browser and navigate to http://localhost:3000 to use the application.

## Usage

To run the REST API server:

```bash
uvicorn app:app --host 0.0.0.0 --port 8001 --reload
```

To run the Streamlit app:

```bash
streamlit run app.py
```

Open the provided URL in your web browser to access the application.

### Example Inputs
- Hey, Which Countries do you guys give tour packages in ? 
- Oh Great, which cities in USA do you guys give tour for ? 
- How many days for the Los Angeles tour ?
- And how much will Los Angeles cost me ?
- What’s the best cusine to try out in Paris ?
- How many days will I get in the Tour for city of Paris ?
- What's the package cost in Paris?
- Which all cities do you guys cover again ?
- Give me London City details ?
- How many days will I get in the city of Bali ?

## Tools and Technologies

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/)

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

## License
Distributed under the MIT License. See LICENSE for more information.
