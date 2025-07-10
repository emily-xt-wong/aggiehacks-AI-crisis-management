# ⏰ AggieHacks Hackathon: AI Crisis Management

As part of my MSBA program, this hackathon project analyzes IoT, geo-spatial, and temporal data to create an AI agent that generates real-time risk notifications for smart cities during crises such as floods or earthquakes. 
The system is headed by a rule-based decision-maker, compiling information from fake news analysis, cascading risk analysis, and general geo-spatial risk analysis to create a succinct 
course of action for the city and its residents to ensure safety and real-time accurate information.

---

## 📌 Project Objective

To build an AI-Powered Crisis Intelligence System that becomes the thinking brain of a smart city during a multi-disaster scenario.
The system aims to:
1. Predict cascading disasters (e.g., flood → power outage → hospital overload)
2. Detect fake news or conflicting information in real time
3. Visualize risk zones and live incident maps
4. Recommend action plans (e.g., "Evacuate Zone C, reroute ambulances")
5. Explain decisions clearly (so city leaders can trust it)

---

## 🗂️ Files in This Repository

| File | Description |
|------|-------------|
| `code.ipynb` | Python notebook containing all code used for sentiment analysis, cascade risk prediction, and area risk. |
| `summary-report.pdf` | One-page summary of the AI-system. |
| `submission-deck.pdf` | Slide deck summarizing development and deliverables. |

---

## 🧠 Key Insights

- **Sensor reliability**: IoT data can be faulty, so the risk model should be able to accurately assess risk through the noisy data.
- **Media reliability**: News and social media posts can be unreliable, leading to further risk during an emergency. Flagging risky posts helps with accurate emergency response.
- **Area Risk**: There are notable geographic differences across the city, with varying levels of historical disaster impacts.
- **Real-time alerts**: Real-time alerts aggregate the most recent information to mitigate any noise in IoT and media data.

---

## 🛠️ Technologies Used

- **Python** - Tensorflow, sci-kit-learn, pandas, GNNs
- **Sentiment Models** – pre-trained BERT sentiment models to flag fake news
- **Canva** – for presentation and visual storytelling

---

## 📚 Hackathon Impact

This submission led to our team being one of eight finalists out of 25 submissions. 
Our team won the 'Best Data Storytelling' award for how we effectively communicated our results to the judges. 
