# RESONATE

Welcome to RESONATE, a unique journal site that allows you to reflect on your entries in a visually engaging way. RESONATE not only captures your thoughts and emotions but also analyzes and presents them using colors for different moods and highlights keywords and patterns. You can also upload photos of your handwritten journal entries, and our AI will read and digitize your handwriting.

## Features

Journal Entries: Easily write and save your daily journal entries.
Mood Analysis: Entries are analyzed to determine the mood of each day and represented with corresponding colors.
Keyword Highlighting: Important keywords and patterns in your entries are highlighted to help you reflect on recurring themes and thoughts.
Visual Representation: Get a visual summary of your journal entries, making it easier to see changes and patterns over time.
Handwriting Recognition: Upload photos of your handwritten journal entries, and our AI will read and digitize them for you.

## Getting Started
## Prerequisites

To run this project locally, you need to have the following installed:

Python 3.x
Node.js
Groq API account and credentials
Vercel account

## Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/resonate.git
cd resonate

## Backend Setup:

    Create a virtual environment:

    bash

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

## Install required packages:

bash

pip install -r requirements.txt

Set up Groq API:

    Sign up for a Groq API account and obtain your API key.
    Create a .env file in the backend directory and add your Groq API key:

    env

    GROQ_API_KEY=your_groq_api_key

Run the backend server:

bash

    python app.py

Frontend Setup:

    Navigate to the frontend directory:

    bash

cd frontend

Install dependencies:

bash

npm install

Start the development server:

bash

        npm start

## Deployment
Deploying the Backend on Vercel

    Log in to Vercel:
        Create an account on Vercel.

    Deploy the Backend:
        Follow the steps to import your project and link your GitHub repository to Vercel.
        Ensure the .env file is included and properly configured in the Vercel environment settings.

Deploying the Frontend on Vercel

    Deploy the Frontend:
        Navigate to the project settings and deploy the frontend directory to Vercel.

## Usage

    Visit your deployed site URL provided by Vercel.
    Create an account or log in to start adding your journal entries.
    Upload photos of handwritten journal entries to have them digitized by the AI.
    View your mood analysis and visual representation on your dashboard.
