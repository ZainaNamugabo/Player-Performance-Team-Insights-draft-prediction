# Player Performance, Team Insights & Draft Predoction.

This repository contains a machine learning pipeline for predicting WNBA player win shares based on draft information and player attributes. The project demonstrates how to preprocess draft data, train a predictive model, and evaluate its performance using error metrics.

📌 Project Overview

Goal: Predict future performance based on draft pick and early career stats.

Approach:

Load draft/player dataset (wnba draft dataset from Kaggle).

Preprocess categorical and numerical features using sklearn pipelines.

Train models and compare performance ( Random Forest / XGBoost / Linear Regression depending on the notebook).

Evaluate predictions on test data.

Generate results with actual vs predicted win shares, prediction error, and player draft pick.

# Dashboard Description

This project focuses on analyzing WNBA draft data to uncover patterns in player selection, team strategies, and long-term performance outcomes. The goal was to transform a complex dataset into a clear, interactive dashboard that tells a meaningful story at a glance.

The dashboard provides a high-level overview with key figures like total players, teams, and colleges represented, then dives deeper into draft trends. It explores which colleges produce the most top picks, how teams utilize their draft selections, and how a player’s draft position relates to performance metrics like win shares and minutes played.

I designed the layout to be both visually engaging and easy to navigate, with filters that allow users to drill down by team, player, and years played. This makes it simple to explore specific scenarios or identify broader trends across seasons.

# Key Highlights:

Snapshot metrics (total players, teams, colleges)

Breakdown of overall picks by college and team

Trend analysis of win shares and minutes by draft position

Year-by-year draft distribution

Interactive filters for deeper exploration

Clean, structured layout for quick insights

This dashboard is a great example of how sports data can be used to tell a deeper story—helping analysts, fans, or decision-makers better understand what really drives value in a draft.
