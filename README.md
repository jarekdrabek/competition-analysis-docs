# 🕵️ Competition & Industry Insights – Social Media Tracker

A SaaS tool that analyzes public Facebook posts from your competitors and delivers simple, digestible summaries daily.

Our mission is to help businesses stay ahead of the competition by monitoring key social media activity across their industry — automatically, and without the noise.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Tech Stack](#tech-stack)
- [Legal Documents](#legal-documents)
  - [Privacy Policy](privacy-policy.md)
  - [Terms of Service](docs/terms-of-service.md)
  - [User Data Deletion Instructions](docs/data-deletion.md)
- [Deployment Notes](#deployment-notes)
- [Contact](#contact)

---

## 📝 Overview

Clients provide links to 3–5 of their competitors’ public Facebook Pages. Our platform uses the Facebook Graph API to analyze and summarize public posts, identify trends, and deliver clear, actionable insights in a daily email report.

This gives businesses a competitive edge without the time-consuming manual monitoring.

---

## 🚀 Features

- ✅ Track public Facebook Page activity
- ✅ Summarize competitor posts and campaigns
- ✅ Identify trending keywords and content types
- ✅ Receive daily email updates
- ✅ GDPR-compliant & privacy-focused

---

## ⚙️ How It Works

1. **User Onboarding**  
   Clients input links to competitors' public Facebook Pages.

2. **Data Collection**  
   We use Facebook’s Graph API (with `Page Public Content Access`) to pull public post data.

3. **Analysis & Reporting**  
   Our backend analyzes patterns, engagement, and post frequency, and generates summaries.

4. **Delivery**  
   Clients receive formatted reports via email or web dashboard.

---

## 🛠️ Tech Stack

- **Backend**: Python / Node.js
- **API**: Facebook Graph API
- **Frontend**: Simple dashboard (optional)
- **Notifications**: Email delivery (Postmark, SendGrid, or similar)
- **Hosting**: GitHub Pages (for public legal docs), AWS/Render/Vercel (app backend)

---

## 📄 Legal Documents

This project complies with Facebook’s Platform Policy and App Review requirements.

- [Privacy Policy](privacy-policy.md)
- [Terms of Service](terms-of-service.md)
- [User Data Deletion Instructions](data-deletion.md)

All data collected is public, and the app does **not** access personal Facebook user data.

---

## 📦 Deployment Notes

- This repository is private.
- Legal documentation is hosted publicly using **GitHub Pages** from the `/docs` folder.
- Access tokens are stored securely and refreshed periodically.
- Facebook App Review includes this GitHub Pages site to verify public links.

---

## 📬 Contact

Have questions, feedback, or a deletion request?  
Reach out at **jarekdrabek@gmail.com**

---

> © 2025 Competition Analysis SaaS – All rights reserved.