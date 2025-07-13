# valorant-anylysis-with-LLm
## 🔍 Overview
This project analyzes enemy performance in Valorant matches by gathering player data via Riot API and evaluating their strength using ChatGPT.  
It helps players prepare strategic insights before gameplay based on past performance metrics.

## 🧠 Features
- Retrieve player match history via Riot Games API
- Extract key metrics such as kills, deaths, agents used, and map performance
- Use ChatGPT to analyze and summarize enemy strengths
- Present AI-generated evaluation in user-friendly format

## 🎮 Technologies
- Python 3.x  
- Riot Games API (account and match history endpoints)  
- OpenAI's GPT API  
- Flask (optional, for frontend)

## 📡 How It Works
1. User inputs target player’s Riot ID (e.g., PoTaARA#Jo5)
2. The system fetches PUUID from Riot’s account endpoint
3. Match history is retrieved for analysis
4. Stats are summarized and sent to ChatGPT for evaluation
5. Output includes strengths, patterns, and agent recommendations

## 🚫 Disclaimer
This project complies with Riot's developer policies and does **not**:
- Display rank estimates (MMR/ELO)
- Shame or misrepresent players
- Reveal private or unauthorized information

## 🌐 Status
Prototype stage. Not publicly distributed. For private testing and development only.
