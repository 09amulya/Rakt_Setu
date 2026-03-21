## RaktSetu — Connecting Lives, One Drop at a Time

RaktSetu is a smart blood donation and request platform designed to bridge the gap between donors and patients in real-time. It leverages a clean UI, eligibility filtering, and simulated AI-like matching to ensure that only the most suitable donors are shown.

---
## Live Link
link - https://adityaupadhyay01.github.io/Rakt_Setu_AlgoMind/

##  Features

###  Smart Donor Matching

* Filters donors based on:

  * Blood group compatibility
  * Location proximity
  * Donation eligibility
* Prioritizes **best matches first**

###  Health-Aware System

* Each donor includes detailed health data:

  * Hemoglobin
  * Blood Pressure
  * Last Donation Gap
  * Diseases / Risk factors
* Automatically excludes **unsafe donors**

###  On-Demand Health Insights

* "View Health Details" button
* Clean dropdown panel for each donor
* Prevents clutter — shows info only when needed

###  Live Dashboard

* Real-time activity feed
* Blood availability chart
* Stats (donors, requests, matches)

###  Donor Report Download

* Generate PDF report of eligible donors
* Includes:

  * Name
  * Blood group
  * City
  * Contact

###  Authentication (Firebase)

* Email/Password login & signup
* User profile auto-population

### Donor Registration

* Register as donor
* Stored in Firebase Firestore

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Firebase (Auth + Firestore)
* **PDF Generation:** jsPDF
* **UI/UX:** Custom responsive design (no frameworks)

---

## ⚙️ How It Works

1. User logs in or signs up
2. User submits blood request
3. System filters donors:

   * Matches blood group
   * Checks eligibility
4. Displays best donors first
5. User can:

   * View health details
   * Call donor
   * Download report

---



---

## 📂 Folder Structure

```bash
RaktSetu/
│── index.html        # Main application
│── README.md         # Project documentation
```

---

##  Future Improvements

*  AI-based donor ranking (distance + urgency score)
*  Real-time location tracking
*  Push notifications for urgent cases
*  Mobile app version
*  Hospital integration APIs
*  Advanced health verification

---


## Team-
* Amulya Pratap Singh
* Ananya Rastogi
* Aashini Singh
* Aditya Upadhyay


---

## Mission

> “Every drop counts. Every second matters.”
> RaktSetu aims to ensure that no life is lost due to lack of timely blood availability.

---
