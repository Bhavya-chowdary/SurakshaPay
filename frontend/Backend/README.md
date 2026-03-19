# Guidewire DEVTrails 2026 Submission
# 1.Problem Statement 
 India’s gig delivery workforce (Zomato, Swiggy, Zepto, Amazon, etc.) faces income loss due to uncontrollable external disruptionssuch as:Heavy Rain,Floods ,Extreme Heat ,Severe Air Pollution ,Traffic Congestion Road Closures ,Curfews Zone Lockdowns Currently, there is NO income protection system for such disruptions.
# 2. Target Persona
We focus on Food Delivery Partners (Swiggy / Zomato) 
# Persona:
1.Works 8–10 hours/day
2.Earns ₹500–₹1200/day 
3.Income directly depends on working hours
4.Highly affected by environmental disruptions
# Example We will provide an example Persona
Ravi is a 26 year old food delivery partner working in a busy urban area. He works around 8–10 hours a day, completing multiple deliveries to earn between ₹500 and ₹1200 daily.
His income is directly tied to the number of deliveries he completes. On normal days, he can maximize his earnings by working longer hours. However, his work is highly dependent on external conditions.
For example:
During heavy rain, fewer orders come in and travel becomes unsafe
During extreme heat, working long hours becomes physically exhausting
When pollution levels are high, outdoor work becomes risk
During traffic congestion or curfews, deliveries may stop completely
On such days, Ravi is forced to stop working or reduce his hours, leading to immediate income loss.
He currently has no financial backup or insurance support to compensate for these disruptions.
# 3.Our Proposed Solution 
SurakshaPay is Our name of Web application, we thought of devloping a web application for Project, SurakshaPay is an AI driven parametric insurance platform designed to protect delivery partners (Swiggy, Zomato, Zepto, Amazon, etc.) from income loss caused by external disruptions such as extreme weather, pollution, and local restrictions. Unlike traditional insurance, SurakshaPay ensures: 
1.Zero paperwork 
2.Instant automated payouts 
3.Weekly affordable pricing 
4.AI driven risk & fraud detection SurakshaPay provides AI-powered parametric insurance that
5.Monitors real-world disruptions (via APIs) 
6.Detects income-impacting events 
7.Automatically triggers claims
8.Instantly pays workers
# 4.Workflow Worker 
    Register/Sigin 
        |
    Chooses Weekly Plan 
        |
    AI calculates Risk Score 
        |
    Policy Created 
        |
    System monitors disruptions (APIs) 
        |
    Event detected (e.g., heavy rain) 
        |
    Auto claim triggered  
        |
    Instant payout processed 
# 5.Project integration:
1.Risk Assessment it use Weather history,AQI trends,Traffic congestion, 
2.Dynamic Weekly Pricing Premium = Base Price × Risk Multiplier 
3.Fraud Detection Engine We use AI to prevent misuse 
4.Fake GPS detection 
5.Duplicate claims prevention 
6.Location mismatch detection Algorithms used Isolation Forest,Pattern anomaly detection 
# 6. Unique Add on 
1. Micro-Time Insurance Instead of daily payouts, we calculate hour level income loss More accurate, fair payouts.
2.Behavior-Based Discounts Consistent workers get lower premiums Encourages platform loyalty. 
3.Silent Claims System Worker doesn’t even know claim is triggered Payout arrives automatically.
# 7. APIs Used 
1.WeatherAPI, OpenWeatherMapDetect rain, heatwaves 
2.Pollution API,AQICN OpenWeather Air API,Detect AQI spikes 
3.Traffic API,Google Maps ,Mapbox, Detect congestion & closures 
4.Location API,Google Geolocation,Used for fraud detection
5.Payment API,Razorpay (Test Mode),Stripe Sandbox 
# 8. System Architecture Frontend (React) 
           ↓ 
 Backend (Node.js API) 
           ↓ 
 AI Risk Engine (Python) 
           ↓ 
 Event Monitoring System 
           ↓ 
  Claim Automation Engine 
           ↓ 
  Payment Gateway 
 # 9. Core Modules: 
1.User Interface (Worker + Admin) 
2.Backend API Server 
3.AI Risk Engine 
4.Event Monitoring System 
5.Claim Automation Engine
6.Payment System 
 # 10.Tech Stack 
1.Frontend-React.js,Tailwind CSS 
2.Backend-Node.js,Express.js 
3.Database-MongoDB
4.AI/ML-Python,Scikit-learn
5.APIs-Weather API,Pollution API,Traffic API,Payment API 
# 11. Roles DashBoard Feature 
1.Worker DashBoard-Active policy,Weekly premium,Claims history,Risk alerts Earnings protected 
2.Admin DashBoard - Policy monitoring,Claims analytics,Fraud alerts,Risk heatmaps 
# 12. Development Plan 
week-1:Research + README + architecture 
week-2:UI + basic backend 
week-3: AI risk model 
week-4:API integrations 
week-5:Claim automation
week-6:Dashboard and testing
  # This Overeview Development Cycle of our Project