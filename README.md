# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)

---

## 🎯 Introduction
This project demonstrates the AI Driven Hyper-Personalization & Recommendations. This project is going to address the problem statements.

**Hyper-Personalized Financial Product Recommendations:**</br>
   A banking-focused model that suggests credit card palns,loan options and credit limit based on the transaction history and the customer profile.
   
**Predictive Customer Insights & Business Strategies:**</br>
   AI-Driven insights that predict customer preferences and purchasing potential, allowing business to tailor enagagement startegies.
   
## 🎥 Demo
📹 [Video Demo](https://youtu.be/RA7CZfqk_6Yhttps://youtu.be/RA7CZfqk_6Y)  
🖼️ [Screenshots:](https://github.com/ewfx/aidhp-recommend-bee/tree/main/link-to-image)

[Product Recommendation](https://github.com/user-attachments/assets/875cd697-495e-4514-8cd3-5944374e7b61) </br>
[Insights](https://github.com/user-attachments/assets/76e57815-577f-4f5a-afd4-550b270deac6)</br>

## 💡 Inspiration
The significance of hyper-personalization lies in its ability to create atruely one-on-one experience for customers, which is crucial in today's highly competitive market.By using advanced algorithms and the power of Large Language models(LLMs),businesses can predict what their customers want, sometimes even before they know it themselves.Hyper personalization builds stroger relationships,increases engagement , and ultimately drives higher conversion rates.

## ⚙️ What It Does
This project contains several AI models work together to create dynamic and individualized experiences.</br>

**Clustering:** KMeans helps to determine which segment a customer belongs to , allowing for more relevant and targeted product recommendations.</br>

**Multi-Target Classifcation:** The multi target classifier enables product recommendation by predicting the likelihood that the customer will be interested in various financial products.</br>

**Random Forest Regression:** Once a product is recommended ,the random forest models furthuer customize the experiences by predicting the exact loan amounts or credit limits, making the recommendation more actinable and precise.</br>

**LLM Insights:** The use of LLM ensures that the business recieves each customer  personalized summary and insights about their finacial standings , making the interaction more conversational and humman-like. 

## 🛠️ How We Built It

**Data Systhesis:** Faker python library is used to systhesis customer profile, transaction and demographics data.</br>

**Model setup:** Load all pre-trained machine learning models using the joblib from the local directory, including the KMeans clustering model,multi-target classifier and Random Forest regression models.</br>

**Customer Data Processing:** Accepts customer data, process it and scales the data using a pretarined scaler.Thadata is then segmented into clusters and used for the product recommendation and loan prediction.</br>

**Product Recommendation:** Using the multi-target classifier ,the app predicts the most probable product the customer might be interested in.Based on this prediction, the app uses the appropriate regression model to predict a specific loan amount or credit limit.</br>

**LLM Integration Insights:** Leveraging Hugging Faces LLM,the app generates personalized text insights for each customer based on their profile.</br>

## 🚧 Challenges We Faced
Creating the test data is the biggest challenge.

## 🏃 How to Run
1. Clone the repository  
   ```sh
   git clone https://github.com/ewfx/aidhp-recommend-bee.git
   ```
2. Install dependencies  
   ```sh
   pip install -r requirements.txt (for Python)
   ```
3. Run all the cells Hyper-Personalization.ipynb.since we are using synthasized test data using faker library, this step is mandatory.Sample customer data can be obtained after running the notebook .
4. Run the project  
   ```sh
    python app.py
   ```

## 🏗️ Tech Stack
- 🔹 Frontend: Flask (html)
- 🔹 Backend: Flask API, JobLib
- 🔹 AI Algorithms/Models: K Means, Multi-target classifier,Random Forest Regressor, Huggingfaces pipeline,langchain,transformers
- 🔹 Other: Huggingface's LLM (AutoModelForCausalLM)

## 👥 Team
- **Ravu Venugopal Rao** - [GitHub](#) | [LinkedIn](#)
- **Mylavarapu Satyaprasad** - [GitHub](#) | [LinkedIn](#)
- **Shreya Srikrishna** - [GitHub](#) | [LinkedIn](#)
- **Juhita Naga Priya** - [GitHub](#) | [LinkedIn](#)
