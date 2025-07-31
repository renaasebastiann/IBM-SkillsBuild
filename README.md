# IBM-SkillsBuild
# 🧳 Travel Planner Agent – AI Itinerary Generator

This project is an AI-powered travel planning assistant that generates customized trip itineraries based on user preferences, destination, budget, and trip duration.

## 🔍 Problem Statement
Travel planning is often time-consuming and overwhelming. This agent aims to simplify the process using IBM Watsonx Granite foundation models to create intelligent, budget-aware, and context-rich itineraries.

## 🛠️ Technologies Used
- IBM Cloud Lite
- IBM Watsonx.ai Studio
- Prompt Lab (Granite 13B Model)
- Vector Store for RAG grounding
- Deployment Space (for sharing)
- Cloud Object Storage (assets)

## ⚙️ How It Works
1. User inputs a travel request (e.g., "Plan a 4-day trip to Kerala under ₹30,000").
2. The prompt sends the request to the Granite LLM via Watson Prompt Lab.
3. It references a vector store (optional) to add contextual info.
4. The model returns a full itinerary including transport, hotels, food, and places to visit.

## 🚀 Features
- Budget-conscious travel plans
- Personalized daily itinerary
- Real-time web tool options (search, calculator)
- Lightweight deployment without backend coding

## 🧪 Sample Prompt
> Plan a 4-day budget trip to Kerala for two college students who love beaches, nature, and street food. Budget is ₹30,000. Include daily itinerary with transport, places to visit, food recommendations, and hotel suggestions.



