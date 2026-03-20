 E-Triage Assistant

Overview
This project is a Real-Time Emergency Response Triage Assistant that helps medical staff make quick decisions using Intelligent Context Pruning.

 Features
- Accepts patient symptoms
- Retrieves only relevant medical data
- Provides urgency level (High/Medium/Low)
- Suggests recommended action
- Shows latency and context reduction

 Tech Stack
React, FastAPI, Python, FAISS

 How It Works
The system uses semantic search to retrieve only the top relevant medical cases instead of processing full patient history. This reduces latency and improves response time.

Results
- Context reduction: ~85%
- Latency: ~400ms (simulated)

Run Instructions
1. Start backend using FastAPI
2. Run frontend using npm start
3. Enter symptoms and click "Run Triage"
