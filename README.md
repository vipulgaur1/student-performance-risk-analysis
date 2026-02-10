# Student Performance Prediction and Academic Risk Analysis System

## Overview
This project is a Flask-based academic analytics system designed to analyze structured student academic data and provide performance insights through an explainable dashboard. The focus is on system design, data analysis, and visualization rather than black-box prediction.

## Problem Statement
In academic environments, students often lack clear visibility into their current academic performance, while faculty members handling multiple classes find it difficult to track individual student progress. This system aims to bridge that gap by converting academic data into actionable insights.

## System Description
The system accepts academic inputs such as attendance percentage, internal marks, and assessment scores. Using rule-based and statistical logic, it calculates a performance score, identifies academic risk levels, and presents the results through a student dashboard.

## Key Features
- Academic data input (attendance, marks, assessments)
- Performance score calculation
- Academic risk classification (Low / Medium / High)
- Student performance dashboard
- Rule-based recommendation system
- Explainable and evaluatable logic

## Tech Stack
- Python
- Flask
- HTML
- Bootstrap

## Current Scope
- Single-student analysis
- Rule-based performance evaluation
- Dashboard-based visualization

## Future Scope
- Faculty-driven marks upload
- Multi-student and class-level analysis
- Historical performance tracking
- Machine learning-based prediction models (post-academic phase)

## How to Run
```bash
pip install -r requirements.txt
python app.py
