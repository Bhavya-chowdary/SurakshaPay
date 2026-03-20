# Guidewire DEVTrails 2026 Submission
 # 1.Problem Statement 
 India’s gig delivery workforce (Zomato, Swiggy, Zepto, Amazon, etc.) faces income loss due to uncontrollable external disruptionssuch as:Heavy Rain,Floods ,Extreme Heat ,Severe Air Pollution ,Traffic Congestion Road Closures ,Curfews Zone Lockdowns Currently, there is NO income protection system for such disruptions. 
 # 2. Target Persona 
 We focus on Food Delivery Partners (Swiggy / Zomato) # Persona: 1.Works 8–10 hours/day 2.Earns ₹500–₹1200/day 3.Income directly depends on working hours 4.Highly affected by environmental disruptions # Example We will provide an example Ravi is a 26 year old food delivery partner working in a busy urban area. He works around 8–10 hours a day, completing multiple deliveries to earn between ₹500 and ₹1200 daily. His income is directly tied to the number of deliveries he completes. On normal days, he can maximize his earnings by working longer hours. However, his work is highly dependent on external conditions. For example: During heavy rain, fewer orders come in and travel becomes unsafe During extreme heat, working long hours becomes physically exhausting When pollution levels are high, outdoor work becomes risk During traffic congestion or curfews, deliveries may stop completely On such days, Ravi is forced to stop working or reduce his hours, leading to immediate income loss. He currently has no financial backup or insurance support to compensate for these disruptions.
# 3.Our Proposed Solution
 # Detailed Working of SurakshaPay 
SurakshaPay is designed to function as a fully automated income protection system for gig workers. The platform continuously connects real-world data with intelligent decision-making to ensure that workers receive compensation whenever they are unable to work due to external disruptions.
# End-to-End Working
When a worker registers on the platform, they provide basic details such as their delivery zone and platform (Swiggy, Zomato, etc.). Based on this information, the system begins analyzing the risk level of that area using historical and real-time data.
The AI engine evaluates multiple factors such as weather patterns, pollution levels, and traffic conditions to assign a risk score. This score is then used to calculate a weekly premium, ensuring that pricing is fair and aligned with the actual risk faced by the worker.
Once the worker selects a plan and activates their policy, the system starts monitoring real-time conditions through external APIs.
# Event Detection and Claim Triggering
The platform continuously tracks external disruptions such as:
- Heavy rainfall  
- Extreme temperatures  
- High pollution levels  
- Traffic congestion  
- Government restrictions or curfews  
Each of these disruptions has predefined thresholds. For example, if rainfall crosses a certain limit or AQI becomes unsafe, the system recognizes that delivery activity will be affected.
At this stage:
1. The system detects the disruption  
2. It verifies whether the worker is in the affected zone  
3. It checks if the worker has an active policy  
4. It estimates the potential income loss  
Once all conditions are satisfied, a claim is automatically triggered without requiring any action from the worker.
# Role of AI in Decision Making
AI plays a critical role in three areas:
**Risk Prediction:** Determines how likely disruptions are in a specific area  
 **Dynamic Pricing:** Adjusts weekly premium based on risk level  
**Fraud Detection:** Identifies suspicious activities like fake locations or repeated claims  
This ensures that the system remains fair, accurate, and secure.
# Payment and Payout Mechanism
The financial model of SurakshaPay is based on a weekly subscription system, which matches the earning cycle of gig workers.
# Premium Collection
Workers pay a small weekly amount to stay insured. This amount depends on their risk level.
For example:
 Low-risk area → lower premium  
High-risk area → slightly higher premium  
The payment is handled through integrated payment gateways like Razorpay or Stripe 
# Payout Calculation Logic
When a disruption occurs, the system calculates the payout based on estimated income loss during that period.
Instead of fixed compensation, SurakshaPay uses a smarter approach:
- It considers average daily earnings  
- It calculates how many working hours were lost  
- It converts that into a payout amount  
# Simple Example (Very Important)
Let’s consider a worker named Ravi:
- Daily earning: ₹800  
- Average working hours: 8 hours  
- Earnings per hour: ₹100  
Now suppose:
- Heavy rain occurs for 4 hours in his delivery zone  
- During this time, Ravi cannot work  
 Income loss = 4 hours × ₹100 = ₹400  
So, the system automatically:
1. Detects heavy rainfall  
2. Confirms Ravi’s active policy  
3. Calculates ₹400 as lost income  
4. Triggers payout  
 ₹400 is instantly credited to Ravi’s account  
# Instant Payout Flow

Once the claim is approved automatically:

- The payout request is sent to the payment gateway  
- The amount is processed instantly (simulated in test mode)  
- The worker receives confirmation on the dashboard  

There is no manual approval, no delay, and no paperwork involved.
# Fraud Prevention in Payouts
Before releasing any payment, the system ensures:
- The worker is actually present in the affected location  
- The event is genuine (verified via APIs)  
- No duplicate claims are being made  
This keeps the system reliable and prevents misuse.
# Final Outcome
SurakshaPay creates a seamless experience where:

- Workers are protected automatically  
- Claims are triggered without effort  
- Payments are processed instantly  
- Income loss is minimized  

In simple terms, the platform ensures that even if a worker cannot work due to external conditions, they are still financially supported.
# 4.Workflow 
   Worker Register/Sigin
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
5.Duplicate claims prevention 6.Location mismatch detection Algorithms used Isolation Forest,Pattern anomaly detection 
# 6. Unique Add on
 1. Micro-Time Insurance Instead of daily payouts, we calculate hour-level income loss More accurate, fair payouts.
 2.Behavior-Based Discounts Consistent workers get lower premiums Encourages platform loyalty.
 3.Silent Claims System Worker doesn’t even know claim is triggered Payout arrives automatically
# 7. APIs Used
1.WeatherAPI, OpenWeatherMapDetect rain, heatwaves 
2.Pollution API,AQICN OpenWeather Air API,Detect AQI spikes 
3.Traffic API,Google Maps ,Mapbox, Detect congestion & closures 
4.Location API,Google Geolocation,Used for fraud detection
5.Payment API,Razorpay (Test Mode),Stripe Sandbox
# 8. System Architecture
 Frontend (React) 
 Backend (Node.js API)
 AI Risk Engine (Python)
 Event Monitoring System 
 Claim Automation Engine
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
5.APIs-Weather API,Pollution API,Traffic APIPayment API
 # 11. Roles DashBoard Feature 
 1.Worker DashBoard-Active policy,Weekly premium,Claims history,Risk alerts Earnings protected 
 2.Admin DashBoard - Policy monitoring,Claims analytics,Fraud alerts,Risk heatmaps
  # 12. Development Plan 
week-1:Research + README + architecture
week-2:UI + basic backend
week-3: AI risk model week-4:API integrations week-5:Claim automation 
week-6:Dashboard and testing 
# This Overeview Development Cycle of our Project