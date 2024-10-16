# Quizify - A Streamlit Quiz Generator App

Quizify is a web-based application built with Streamlit that generates quizzes from YouTube transcripts and PDF files using the Azure OpenAI API. It includes user authentication, quiz generation, and scoring features. 

## Features

- **User Authentication**: Users can register and log in to their accounts. Passwords are stored securely using hashing techniques.
- **Quiz Generation**: Convert YouTube videos or PDF documents into Multiple Choice Questions (MCQs).
- **Scoring System**: Users can take quizzes and see their scores at the end.
- **User History**: Track and display user history, including previous quiz attempts and scores.
- **API Integration**: Uses Azure OpenAI API for generating quiz questions.

## Tech Stack

- **Frontend**: React (for frontend UI)
- **Backend**: Streamlit (Python-based framework for fast prototyping)
- **Database**: Pickle files for user data (or upgrade to a database such as SQLite or Firebase)
- **API**: Azure OpenAI API for generating questions
- **Hosting**: Streamlit Cloud

## Installation

### Prerequisites

- Python 3.x
- An API key from Azure OpenAI
- Streamlit installed (`pip install streamlit`)
- A `.env` file for securely storing API keys

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/quizify.git
   cd quizify
