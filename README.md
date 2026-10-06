# nba_sports_gambling
# 🏀 NBA Sports Gambling Prediction Using Machine Learning

> A machine learning project inspired by the Stanford research paper **"The Bank is Open: AI in Sports Gambling"**,
> exploring whether historical NBA game data and machine learning models can predict the total points scored in an NBA game.

---

## 👥 Team

**Team Members**

- **Shasank SK-PES2UG24SC460** — Data preprocessing, feature engineering, Random Forest, Neural Network, project integration
- **Shashwath - PES2UG24CS463** — Collaborative Filtering, LSTM, additional machine learning model, evaluation and comparison

> This is a collaborative two-person machine learning project developed as part of our academic work in Computer Science and Engineering

---

# 📌 Introduction

Sports betting markets use statistical models and large amounts of historical data to estimate the expected outcome of sporting events.

One of the most common betting markets in basketball is the **Over/Under**, where a sportsbook predicts a total number of points that both teams are expected to score.

For example:

> **Over/Under Line = 220.5 points**

If the two teams score more than 220.5 points, the result is **Over**.

If they score fewer than 220.5 points, the result is **Under**.

This project investigates whether machine learning models can independently predict the **combined total points scored by both teams** in an NBA game using historical game statistics.

The project is inspired by the Stanford paper:

> **"The Bank is Open: AI in Sports Gambling"**  
> Alexandre Bucquet and Vishnu Sarukkai  
> Stanford University

Our implementation follows the core research question and general modelling philosophy of the paper while using an alternative publicly available NBA dataset.

---

# 🎯 Project Objective

The main objective of this project is:

> **Predict the total number of points scored by both teams in an NBA game using historical team performance data and machine learning.**

For a given matchup:

```text
Home Team + Away Team
        ↓
Historical Performance
        ↓
Feature Engineering
        ↓
Machine Learning Model
        ↓
Predicted Total Points