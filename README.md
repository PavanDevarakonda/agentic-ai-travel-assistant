
# 🧳 Agentic AI Travel Assistant using CrewAI

This project demonstrates an intelligent, modular AI travel assistant that can autonomously plan trips — including flights, accommodations, and weather — using autonomous agents coordinated through CrewAI.

## ✈️ Overview

The notebook implements:
- A multi-agent CrewAI system powered by LLMs
- Real-time flight, hotel, and weather planning using public APIs
- Agent coordination for personalized itinerary generation
- Modular design that separates tools, agents, and orchestration logic

## 🤖 Agent Architecture

- **Flight Agent**: Searches for flights based on input criteria
- **Hotel Agent**: Suggests hotels by price and rating
- **Weather Agent**: Fetches forecasts for the destination
- **Planner Agent**: Synthesizes results into a complete itinerary

## 🧰 Tech Stack

- Python
- CrewAI
- OpenAI (or compatible LLMs)
- API integrations (flights, hotels, weather)
- Jupyter Notebook

## 🛡️ Security Note

For safety, ensure your API keys are stored as environment variables and not hardcoded in the notebook.

```python
import os
openai.api_key = os.getenv("OPENAI_API_KEY")
```

## 🚀 How to Run

1. Clone the repo
2. Install dependencies (CrewAI, requests, OpenAI, etc.)
3. Export necessary environment variables
4. Launch the notebook:

```bash
jupyter notebook AI_Travel_Agent.ipynb
```

## 🌍 Future Improvements

- Add Streamlit-based UI
- Persist recommendations to a database
- Add more tools (e.g., local events, restaurant planner)

## 📌 License

This project is for demonstration and academic purposes only.
