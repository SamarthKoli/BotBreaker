# Enhanced CAPTCHA Solution for UIDAI

## Overview
This project introduces a robust CAPTCHA system designed for the UIDAI portal to differentiate between bots and human users. By leveraging passive environmental parameters and active interaction mechanisms, the solution ensures enhanced security while providing an optimized user experience.

## Features

### 1. **Passive Environmental Parameter Collection**
- Captures browser context data, including:
  - Mouse movements
  - Keystrokes
  - Time spent on the page
- Uses this data to passively assess whether the user is a human or a bot.

### 2. **AI/ML Backend Analysis**
- An AI/ML model processes the collected environmental parameters in real time.
- Outputs a probability score to classify users as human or bot.
- Developed using Python libraries like Scikit-learn, NumPy, and Pandas.

### 3. **Fallback Active CAPTCHA**
- If passive detection is inconclusive, an active CAPTCHA is triggered:
  - Requires the user to connect two identical shapes on a grid using their mouse.
  - Prompts the user to enter a specific key combination within a time limit.

### 4. **Optimized User Experience**
- Designed to limit human interaction, ensuring minimal disruption while maintaining security.
- Protects against DoS/DDoS attacks and fraud attempts.

### 5. **Pluggable Solution Architecture**
- Modular components enable seamless integration into the UIDAI portal via RESTful APIs.
- Backend is built using Flask/Django for API handling.

### 6. **Privacy and Security**
- Strict adherence to UIDAI’s privacy policies.
- Ensures user data protection and encrypts sensitive information.

## Technology Stack
- **Frontend**: React
- **Backend**: Python, Flask, Django
- **ML Model**: Scikit-learn, NumPy, Joblib
- **Libraries**: Pandas, Faker, Plotly

## Impact and Benefits
- **Enhanced Security**: Protects the portal from automated attacks and data breaches.
- **Improved User Trust**: Increases confidence in the system by ensuring robust security measures.
- **Fraud Prevention**: Blocks bots from creating fake identities or accessing sensitive information.
- **Operational Efficiency**: Automates bot detection to reduce manual intervention and operational costs.

## Challenges and Strategies
- **Challenge**: Differentiating between sophisticated bots and human users.
- **Strategy**: Combining passive data analysis with fallback active CAPTCHA for comprehensive validation.

## Video Demonstration
Check out the video demonstration of the CAPTCHA solution:
[![Watch the Video](https://www.youtube.com/watch?v=v4o3KQ6hN1g)
