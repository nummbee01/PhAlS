# PhAlS - Phishing Alert System

[![Made with JavaScript](https://img.shields.io/badge/Made%20with-JavaScript-yellow)](#)  

**PhAlS** is a lightweight, client-side phishing alert tool that helps users quickly identify suspicious links and emails. It evaluates input for common phishing signs and assigns a color-coded risk score to help users stay safe online.

---

## Features
- Check any URL or email for phishing indicators.
- Assigns a **risk score** based on:
  - Suspicious domains (`.tk`, `.biz`, `.ru`)
  - Common phishing keywords (`login`, `verify`, `account`, etc.)
  - Presence of `http://` instead of HTTPS
  - Unusual patterns like multiple consecutive dots
- Provides **instant feedback**:
  - Low (Green)  
  - Medium (Yellow)  
  - High (Red)
- Optional test mode for guessing safe vs. phishy links.
- Fully **client-side**: no backend required.

---

## How It Works
1. User inputs a URL or email.
2. JavaScript runs a series of checks and increments a `riskScore` for each red flag.
3. Feedback is displayed with clear color-coded alerts and tips.
4. Users can optionally test their knowledge on phishing links.

---

## Screenshot

!(screenshot.png)

---

## Installation

1. Clone the repository:  
```bash
git clone https://github.com/nummbee01/PhAlS.git
