🕋 Intelligent System for Hajj and Umrah Crowd Management

This project is part of my Big Data Analytics assignment at IIUM. I developed an intelligent system to monitor, predict, and manage pilgrim movements using a dataset of 10,000 records.
📋 Project Overview

The goal of this system is to improve the pilgrimage experience by using data to solve real-world problems like overcrowding and transit delays. I explored four main types of data science questions to give a complete picture of the crowd dynamics.
🧪 Key Analysis & Findings
1. Predicting the Crowd (Predictive)

I used a Random Forest model to predict crowd density levels based on things like walking speed, temperature, and even how tired the pilgrims are.
2. Finding Stress Triggers (Diagnostic)

By looking at "Feature Importance," I found that physical distance between people and walking speed are the biggest reasons why pilgrims feel stressed.
3. Does Technology Help? (Causal)

I ran a statistical test to see if AR Navigation actually saves time. Interestingly, the data showed it hasn't made a huge difference yet, suggesting that rituals have a natural pace that gadgets can't speed up.
4. Smart Transport Advice (Prescriptive)

I built a recommendation system that tells pilgrims the best way to travel. For example, even if walking is usually fast, it suggests taking the Train if it starts raining to keep everyone safe and comfortable.
🛠️ How I Built It

    Cleaning: I fixed timestamps, handled missing info, and scaled the numbers so the model stays fair.

    Encoding: I turned categories like "Nationality" and "Activity Type" into formats the computer can actually calculate.

    Visualization: I used line charts and bar graphs to show the "pulse" of the crowd across 24 hours.

🚀 How to Run

    Open the .ipynb file in Google Colab.

    Upload the hajj_umrah_data.csv file.

    Run all cells to see the 8 analysis questions and their results.
