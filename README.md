# AI Hydration Assistant

An AI-powered hydration tracking application built with Python, FastAPI, LangChain, SQLite, and Streamlit.

The application allows users to record their daily water intake, monitor hydration progress, and receive personalized AI-powered hydration insights based on their consumption data.

## Features

- Track and log daily water intake
- Store hydration data using SQLite
- RESTful backend API with FastAPI
- AI-powered hydration assistant using LangChain and OpenAI
- Personalized hydration feedback and recommendations
- Interactive Streamlit dashboard
- Daily hydration progress visualization
- Simple and beginner-friendly architecture

## Tech Stack

### Backend
- Python
- FastAPI
- SQLite
- Pydantic

### AI
- LangChain
- OpenAI API

### Frontend
- Streamlit

## Architecture

```text
User
  │
  ▼
Streamlit Dashboard
  │
  ▼
FastAPI Backend
  │
  ├── Hydration API
  │
  ├── SQLite Database
  │
  └── LangChain AI Assistant
          │
          ▼
      OpenAI API
