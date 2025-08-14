# NagarSetu_Web

**Nagar Setu** is a public grievance redressal platform that bridges the gap between citizens and administrative authorities.  
It enables **citizens** to raise complaints, **officers** to address them, and **admins** to oversee the process — all secured with **JWT authentication** and automated complaint routing.

---

##  Features

###  User
- Secure registration & login
- Submit complaints with:
  - Category (e.g., Development, Sanitation, Water Supply)
  - Location (pincode)
- Track complaint status in real-time

###  Officer
- Register & await **admin approval**
- Automatically receive complaints based on:
  - Department
  - Location
- Update complaint status & resolution notes

###  Admin
- Approve/reject officer registrations
- Manage all complaints & users
- Monitor complaint resolution timelines

---

##  Automated Complaint Routing
Nagar Setu uses a **DSA-based routing algorithm**:
1. Each complaint has a **type** (e.g., Development, Sanitation).
2. Based on the type → routed to the corresponding **department**.
3. Within that department → complaint goes to the **officer serving the given location**.
4. Officer gets notified instantly.

Example:
- Complaint: "Streetlight not working" → Category: Development → Department: BDO → Officer at pincode `713101`.

---

##  Tech Stack

| Layer          | Technology Used           |
|----------------|---------------------------|
| Backend        | Spring Boot (Java)        |
| Security       | Spring Security + JWT     |
| Database       |  PostgreSQL               |
| Frontend       | React.js                  |
| Build Tool     | Maven , Docker            |
| Authentication | Token-based (JWT)         |
<img width="1440" height="900" alt="Screenshot 2025-07-10 at 11 49 56 PM" src="https://github.com/user-attachments/assets/5abaafbc-8cb4-43bf-8503-b2b22727df85" />
<img width="1440" height="900" alt="Screenshot 2025-07-10 at 11 50 31 PM" src="https://github.com/user-attachments/assets/d1a5b821-05a2-4caf-9023-42c720cdd0e4" />
<img width="1440" height="900" alt="Screenshot 2025-08-14 at 12 04 54 PM" src="https://github.com/user-attachments/assets/7edcd44e-e416-41dd-a74f-1ecf1c869815" />
<img width="1440" height="900" alt="Screenshot 2025-07-10 at 11 51 13 PM" src="https://github.com/user-attachments/assets/f88ba68a-65ed-42c9-b94a-ae27cc6f5ed7" />
<img width="1440" height="900" alt="Screenshot 2025-08-14 at 12 09 45 PM" src="https://github.com/user-attachments/assets/584f6e97-143f-45cf-b642-8a08af38379f" />


---

