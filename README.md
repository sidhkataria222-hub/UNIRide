# UNIRide
A student-only cab booking and ride-sharing platform designed for affordable, convenient, and safer travel across India. Features include college ID verification, professional cab booking, student carpooling, live tracking, female-driver preferences, women-only rides, late-night event bookings, emergency SOS, trusted contacts, and secure trip 



# 🚕 CampusGo — Student Mobility Platform

### Your Campus. Your People. Your Ride. 🎓

CampusGo is a student-focused mobility platform designed to make transportation more affordable, convenient, and safer for college students across India. It combines professional cab booking with student ride-sharing, allowing verified students to travel together while enjoying features designed around trust, convenience, and personal safety.

---

## 🌟 Key Features

- 🎓 **Student Verification:** College ID verification to restrict student services to eligible users.
- 🚖 **Professional Cab Booking:** Book professional drivers with fare estimates and trip details.
- 🤝 **Student Ride-Sharing:** Find compatible rides and share eligible travel costs.
- 📍 **Live Tracking:** Monitor active rides and share trip details with trusted contacts.
- 💜 **SafeHer — Women's Safety:** Dedicated safety features for female students.
- 👩‍✈️ **Female Driver Preference:** Request a female professional driver when available.
- 🌸 **Women-Only Rides:** Opt-in shared rides for eligible, verified women.
- 🎉 **Late-Night Event Booking:** Plan return journeys from college fests, concerts, and events.
- 🆘 **Emergency SOS:** Quick access to emergency assistance and trusted contacts.
- 🔐 **Secure Authentication:** Protected accounts and role-based access.
- ⭐ **Ratings & Reviews:** Share feedback after completed trips.
- 🏙️ **Multi-City Support:** Architecture designed to support expansion across India.

---

## 💜 SafeHer — Women's Safety

CampusGo includes a dedicated women's safety section focused on helping female students travel with greater confidence, especially during late-night journeys.

**Safety features include:**
- Female-driver preference, subject to availability.
- Opt-in women-only ride-sharing.
- Live trip sharing with trusted contacts.
- Emergency SOS and support workflows.
- Driver and vehicle identity checks.
- Trip-start PIN verification.
- Safer event pickup-point guidance.
- Late-night return ride scheduling.
- Safety incident reporting.
- Safe-arrival confirmation.
- Privacy controls for personal information and location sharing.

*Safety features depend on implementation, provider availability, and operational support. Emergency assistance must be connected to a real response process before being advertised as operational.*

---

## 🛠️ Technology Stack

| Component | Technology |
|---|---|
| Mobile Application | React Native + TypeScript |
| Backend | Java + Spring Boot |
| Database | PostgreSQL + PostGIS |
| Authentication | Spring Security + OTP |
| Maps & Location | Google Maps Platform or an alternative |
| Real-Time Updates | WebSockets |
| Notifications | Firebase Cloud Messaging |
| Payments | Compatible payment gateway |
| Admin Dashboard | React + TypeScript |
| Deployment | Docker + Cloud Hosting |

*The final stack may change during development.*

---

## 🏗️ Project Architecture

```text
CampusGo/
│
├── mobile-app/
│   ├── src/
│   │   ├── screens/
│   │   ├── components/
│   │   ├── navigation/
│   │   ├── services/
│   │   └── features/
│   │       ├── authentication/
│   │       ├── student-verification/
│   │       ├── cab-booking/
│   │       ├── ride-sharing/
│   │       └── safeher/
│   │
├── backend/
│   └── src/main/java/
│       └── com/campusgo/
│           ├── auth/
│           ├── users/
│           ├── verification/
│           ├── providers/
│           ├── vehicles/
│           ├── bookings/
│           ├── carpool/
│           ├── matching/
│           ├── payments/
│           ├── tracking/
│           ├── safety/
│           └── admin/
│
├── admin-dashboard/
├── database/
├── docs/
└── README.md
```

---

## 🔄 How It Works

1. **Register:** Create an account using supported authentication methods.
2. **Verify:** Submit a college ID for verification.
3. **Choose:** Select professional cab booking or student ride-sharing.
4. **Book:** Enter pickup and destination, compare available options, and confirm.
5. **Travel:** View trip details and use available tracking and safety features.
6. **Arrive:** Complete the journey, provide feedback, and report any concerns.

---

## 🚀 Development Roadmap

- [ ] Authentication and user profiles.
- [ ] College ID verification workflow.
- [ ] Admin dashboard.
- [ ] Professional cab booking.
- [ ] Student ride-sharing and matching.
- [ ] Maps and location integration.
- [ ] Booking and cancellation management.
- [ ] Payment integration.
- [ ] SafeHer women's safety module.
- [ ] Live trip tracking and notifications.
- [ ] Testing and deployment.
- [ ] Pilot launch and multi-city expansion.

---

## 🔒 Security & Privacy

CampusGo aims to protect users through secure authentication, role-based permissions, private document storage, controlled location sharing, and appropriate data-retention policies.

Student verification does not automatically authorize a user to provide passenger transport. Driver eligibility, vehicle requirements, insurance, transport regulations, and applicable Indian data-protection requirements must be addressed before launch.

---

## 🎯 Vision

Our vision is to build a trusted student mobility community that connects verified students with convenient transportation options while prioritizing affordability, accessibility, and personal safety.

**CampusGo — Moving Students Forward.** 🚀

---



Contributions, suggestions, and feedback are welcome!

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Submit a pull request with a clear description.

---

## 📌 Project Status

**Status:** In Development 🚧

CampusGo is a proposed student mobility platform. Features should be considered operational only after their implementation, testing, and required integrations are complete.
