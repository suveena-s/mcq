# MCQ Generator

An automated Multiple Choice Question (MCQ) generator using OpenAI's GPT model and LangChain, with a Streamlit interface.

## Description

This project generates multiple-choice questions from given text input. It uses OpenAI's GPT model to create questions and evaluate their complexity, ensuring they are suitable for the specified subject and student level.

## Features

- Generate MCQs from text input
- Customize number of questions, subject, and tone
- Automatic evaluation and adjustment of question complexity
- Streamlit web interface for easy use
  

## Installation

1. Clone the repository
2. Install required packages:pip install -r requirements.txt
3.  Set up your OpenAI API key in a `.env` file:OPENAI_API_KEY=your_api_key_here

## Usage

Run the Streamlit app:
streamlit run StreamlitAPP.py

Follow the interface prompts to generate MCQs.

## Technologies Used

- Python
- OpenAI GPT
- LangChain
- Streamlit
- Pandas
