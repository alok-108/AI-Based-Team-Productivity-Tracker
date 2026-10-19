# AI-Based-Team-Productivity-Tracker
AI-Based Team Productivity Tracker helps teams analyze productivity trends using AI. It supports CSV uploads and Jira API integration to fetch real-time task data. The app provides insights into team performance with visualizations and time-series forecasting. Built with Gradio, Prophet, and Python libraries.

## Features
- Upload team task data as a CSV file, or fetch it from Jira through its REST API
- Visualize productivity trends with matplotlib and seaborn
- Forecast future trends with time-series models built on Prophet
- Interactive UI built with Gradio

## Getting started
1. Install the dependencies:
   ```bash
   pip install gradio pandas seaborn matplotlib prophet streamlit requests
   ```
2. Open `AI_Based_Team_Productivity_Tracker.ipynb` in Jupyter or Google Colab and run the cells in order.
3. Upload a CSV file, or enter your Jira details, in the app that starts.
