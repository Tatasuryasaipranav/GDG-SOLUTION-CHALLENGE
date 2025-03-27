Overview of the Code
Imports & Setup

streamlit for UI

requests for API calls

Title & Session State

Initializes chat history using st.session_state.messages

Display Chat History

Loops through stored messages and displays them

User Input Handling

Captures user input using st.chat_input()

Adds user query to chat history

API Call to Gemini

Sends request to Google's Gemini API using requests.post()

Extracts AI response from JSON

Displaying AI Response

Shows AI-generated response in chat

Stores it in st.session_state.messages

Error Handling

Catches API request failures with try-except
Project Overview: Empowering Small and Marginal Farmers with AI-Driven Agricultural Solutions
Objective:
To enhance agricultural productivity and sustainability for small and marginal farmers using AI-powered solutions.

Key Components:
AI-Powered Crop Advisory – Provides real-time recommendations for crop selection, soil health, and pest control.

Weather & Soil Analysis – AI integrates weather forecasts and soil data for precision farming.

Smart Irrigation Management – Optimizes water usage with AI-driven insights.

Market Linkage & Price Prediction – Helps farmers get better prices through AI-driven market trends.

Mobile & IoT Integration – Enables access to AI solutions via mobile apps and smart sensors.

Expected Impact:
Improved crop yields and reduced losses
Efficient resource utilization (water, fertilizers)
Better market access and fair pricing
Enhanced decision-making with AI-driven insights
