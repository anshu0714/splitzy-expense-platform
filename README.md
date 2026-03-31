# 🚀 Splitzy — Real-Time Expense Sharing Platform

## Overview

Splitzy helps users:

- Track shared expenses across groups (travel, rent, events)
- Automatically split bills with flexible logic
- View real-time balances across all members
- Receive AI-powered monthly financial insights

The application is built as a modern full-stack system with real-time synchronization and automated workflows.



## ✨ Key Highlights

- Built a **real-time expense tracking system** using Convex for instant data sync across users
- Designed **automated calculation engine** for equal & custom expense splitting
- Implemented **event-driven workflows** (Inngest) for reminders and background processing
- Integrated **AI-powered monthly insights** to analyze spending behavior
- Solved real-world problems like:
  - inconsistent balances across users
  - delayed settlements
  - lack of transparency in shared expenses
- Built a **scalable architecture** supporting multi-group expense tracking
- Ensured **data consistency across concurrent users**



## 🛠️ Tech Stack

### Frontend:
- Next.js (App Router)
- Tailwind CSS
- shadcn/ui

### Backend:
- Convex (real-time backend & database)

### Auth:
- Clerk

### Workflows:
- Inngest

### Email:
- Resend

### Deployment:
- Vercel



## 🌐 Live Deployment

🔗 Live App: https://splitzy-woad.vercel.app/



## 📁 Project Documentation

📦 Full Project: This repository  
(If you later split frontend/backend, you can add separate READMEs like HireMind)


## 🚀 Features

### 👥 Group & Expense Management
- Create and manage multiple groups  
- Add expenses with payer, participants, and categories  
- Support for equal and custom splits  



### 🔄 Real-Time System
- Instant balance updates across all users  
- No manual refresh required  
- Consistent shared state using Convex  

### 📊 Analytics & Insights
- Monthly spending visualization  
- Clear breakdown of group expenses  

### 🤖 AI Features
- AI-generated monthly summaries  
- Insights into spending patterns  

### 📧 Notifications System
- Automated payment reminders  
- Email-based alerts for due balances  

### 📱 User Experience
- Fully responsive design  
- Clean and minimal UI  
- Optimized for mobile and desktop  

## ⚙️ Architecture & Engineering

- Real-time backend using Convex (no traditional REST polling)
- Event-driven workflows for async processing (Inngest)
- Separation of UI and business logic
- Scalable structure for future features (payments, analytics)

## 📌 Project Status

### Backend
Production-ready for core features

Handles:
- Real-time sync
- Expense calculations
- Group management
- Workflows & notifications

### Frontend
Feature-complete for main flows

Includes:
- Expense tracking UI
- Group management
- Analytics dashboard
- Responsive design

### Overall

Production-ready for core workflows with scope for scaling and feature expansion

## 🧠 Engineering Learnings

- Designing **real-time systems** instead of traditional request-response APIs  
- Handling **shared state consistency across multiple users**  
- Building **event-driven workflows** for background processing  
- Integrating AI features into real-world applications  
- Solving UX problems related to financial transparency and trust  

## 📌 Future Improvements

- Integrate payment gateways (UPI / Stripe) to enable direct settlement within the app  
- Add recurring expense support for rent, subscriptions, and utilities  
- Enhance analytics with per-user spending patterns and anomaly detection  
- Explore mobile app version for improved accessibility  
