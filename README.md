# AQIanalyzer
AQI Analyzer
🏭 AQI Prediction Web App

📌 About the Project

Air pollution is one of the leading threats to environmental and human health. The **Air Quality Index (AQI)** simplifies complex air pollution data into a single number to effectively communicate health risks to the public.

This project:

- Uses **regression models** (e.g., **Random Forest**) to predict AQI  
- Is trained on data from **Kerala's CAAQMS** *(Dec 2023 – Feb 2024)*  
- Takes real-time pollutant levels as input and classifies air quality *(e.g., Good, Moderate, Hazardous)*  
- Is deployed as an **interactive Streamlit web app**


🚀 Features

- 📊 **User Input Panel**  
  Input key air pollutant concentrations:
  - CO (Carbon Monoxide)
  - O₃ (Ozone)
  - NO (Nitric Oxide)
  - NO₂ (Nitrogen Dioxide)
  - NOx (Nitrogen Oxides)
  - NH₃ (Ammonia)
  - SO₂ (Sulfur Dioxide)
  - PM2.5 (Fine Particulate Matter)
  - PM10 (Respirable Particulate Matter)

- 🤖 **Real-time AQI Prediction**  
  Predicts AQI using a trained machine learning model.

- 🟢 **AQI Classification**  
  Outputs AQI category based on CPCB standards:
  - Good 🟢
  - Satisfactory 🟡
  - Moderate 🟠
  - Poor 🔴
  - Very Poor 🟣
  - Severe ⚫

- 📈 **Pollutant Visualization**  
  Displays an optional bar chart showing the levels of each input pollutant.


 💻 Tech Stack

- Python
- Streamlit
- scikit-learn (Random Forest)
- Pandas, NumPy
- Matplotlib / Seaborn (for visualization)
