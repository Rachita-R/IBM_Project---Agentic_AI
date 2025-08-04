# IBM_Project---Agentic_AI
# 🌍 Travel Planner Agent  

## 📌 Overview  
The **Travel Planner Agent** is an AI-powered assistant built using IBM Watsonx that helps users plan trips efficiently and intelligently. It leverages real-time data and user preferences to generate personalized travel recommendations, create itineraries, suggest accommodations, and provide transport and weather updates.  

By integrating tools, maps, and local guides, the agent ensures a seamless and enjoyable travel planning experience.  

---

## 🎯 Purpose  
The purpose of this project is to transform the traditionally complex process of trip planning into a **simple, personalized, and automated experience**.  

Key benefits include:  
- Personalized itineraries tailored to user preferences and budgets  
- Real-time updates on weather, transportation, and bookings  
- Streamlined suggestions for destinations, stays, and activities  
- Alerts for changes and optimized scheduling on the go  

---

## ⚙️ Features  
- 🏖️ **Destination Recommendations**: Suggests destinations based on user preferences, season, and budget  
- 🗓️ **Itinerary Creation**: Generates day-by-day travel plans including activities, meals, and sightseeing  
- 🏨 **Accommodation Suggestions**: Recommends hotels, hostels, or rentals with budget and rating filters  
- 🚆 **Transport Options**: Provides flight, train, or local transport recommendations with estimated costs and durations  
- 🌦️ **Weather Integration**: Real-time weather updates and travel advisories  
- 📍 **Local Guides & Tips**: Shares cultural, safety, and transportation tips for smooth travel  
- 🔔 **Booking Management**: Helps manage and track bookings, sending alerts for changes  
- 🧾 **Optimized Schedules**: Adjusts plans dynamically for convenience, cost, and time efficiency  

---

## 🏗️ Architecture  
The agent is built using:  
- **Framework**: LangGraph  
- **Architecture**: ReAct  
- **Model**: IBM Granite (`granite-3-3-8b-instruct`)  
- **Runtime**: Python 3.11 environment on IBM Watsonx  
- **Deployment**: IBM Watsonx Agent Lab  

**Core Components:**  
1. **Instructions Module**: Defines the AI’s role, behavior, and greetings  
2. **Knowledge Sources**: CSV files with destinations, transport, accommodations, and weather data  
3. **Tools Integration**: Custom tools for real-time data (maps, weather, bookings)  
4. **Agent Workflow**: User input → Reasoning → Tool usage → Response generation  

---

## 📂 Data Files  
Upload the following CSVs under the **Knowledge** section in Agent Lab:  
- `destinations.csv` → Best times to visit, attractions, budget ranges  
- `transport.csv` → City-wise transport modes, cost, and duration  
- `accommodation.csv` → Hotel recommendations with ratings and notes  
- `weather.csv` → City/month weather averages and travel advice  
- `local_guides.csv` → Cultural, transport, and safety tips  

---

## 🚀 Getting Started  

### Prerequisites  
- IBM Cloud Account with Watsonx access  
- Deployment Space created in Watsonx  
- Knowledge files (CSV) uploaded in Agent Lab  

### Steps  
1. Clone or upload the project to your IBM Watsonx environment  
2. Go to **Agent Lab → Build**  
3. Configure:  
   - Framework: **LangGraph**  
   - Architecture: **ReAct**  
   - Instructions: Paste the Travel Planner Agent instructions  
4. Add CSV knowledge sources under **Knowledge**  
5. Add or create custom tools (e.g., weather API, booking tool)  
6. Deploy the agent with a **Serving Name** (required for endpoint access)  
7. Test via the **Preview tab** or API reference  

---

## 📊 Example Use Case  

**User:**  
"I want to plan a 5-day budget-friendly trip to Japan in October."  

**Agent Response:**  
- Recommended Cities: Tokyo, Kyoto  
- Suggested Activities: Visit Shibuya Crossing, Arashiyama Bamboo Forest, Kyoto temples  
- Accommodation: APA Hotel (Budget) ~ $80/night  
- Transport: JR Pass for Shinkansen travel between Tokyo and Kyoto  
- Weather: 20°C average, pleasant for sightseeing  
- Local Tip: Purchase a Suica card for easy metro access  

---

## 📌 Future Enhancements  
- Integration with live flight and hotel APIs  
- Voice-enabled assistant  
- Currency exchange and budgeting assistant  
- Emergency contact database integration  
- Multi-language support for international travelers  

---

## 📜 References  
- [TravelAgent: An AI Assistant for Personalized Travel Planning](https://arxiv.org/abs/2409.08069?utm_source=chatgpt.com)  
- [Vaiage: A Multi-Agent Solution to Personalized Travel Planning](https://arxiv.org/abs/2505.10922?utm_source=chatgpt.com)  
- [Optimizing Travel Itineraries with AI Algorithms](https://arxiv.org/pdf/2410.17943?utm_source=chatgpt.com)  
- [TravelPlanner Benchmark](https://arxiv.org/abs/2402.01622?utm_source=chatgpt.com)  
- [GuideGeek AI Travel Assistant](https://en.wikipedia.org/wiki/GuideGeek?utm_source=chatgpt.com)  

---

## Author  
**Rachita Rudraganti**  
B.Tech CSE Student | AI & Cloud Enthusiast  
