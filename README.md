# RaktSetu — Backend (Aditya Branch)

This branch focuses on the **backend integration and database setup** of the RaktSetu project.

The goal of this branch is to convert the project from a UI-based demo into a **real data-driven system** using Firebase.

---

## What’s Implemented in This Branch

### Firebase Integration

* Connected project to **Firebase**
* Configured using Firebase SDK (API-based setup)
* Verified successful connection via console logs

---

### Firestore Database Setup

* Created `donor` collection
* Stored real donor data in Firestore

Example document:

```json
{
  "name": "Rahul Kumar",
  "blood": "O+",
  "city": "Delhi",
  "phone": "1234567890",
  "donations": 2
}
```

---

###  Data Fetching (API-based)

* Fetched donor data from Firestore
* Converted documents → usable JS objects
* Verified using console logging

```js
const snapshot = await getDocs(collection(db, "donor"));
const donors = snapshot.docs.map(doc => doc.data());

console.log(" Donors:", donors);
```

---

###  Branch-Based Development

* All backend work is isolated in **`aditya` branch**
* Main branch remains untouched and stable
* Enables safe experimentation and feature development

---

##  Tech Stack (This Branch)

* Firebase Firestore (Database)
* Firebase SDK (API integration)
* JavaScript (Async/Await for data handling)

---

##  Work in Progress

*  Rendering Firestore data directly in UI
*  User Authentication (Firebase Auth)
*  Location-
