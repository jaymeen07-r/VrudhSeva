# VrudhSeva

## Overview

**VrudhSeva** is an intelligent elder-care platform designed to ensure the **health, safety, and well-being of senior citizens** through continuous monitoring and automated emergency response.

The system operates quietly in the background, reducing the need for constant manual interaction, while ensuring that **family members, caretakers, and administrators are notified instantly when attention is required**.

VrudhSeva is built with a strong focus on **reliability, accessibility, privacy, and real-world usability**.

---

## Vision & Purpose

The primary goal of VrudhSeva is to bridge the gap between elders and their caregivers by using technology that is:
- Simple for elders
- Informative for family members
- Actionable for caretakers
- Secure and manageable for administrators

The platform is designed to scale from a **personal care solution** to a **community-level elder-care system**.

---

## Key Features

### 🩺 Continuous Health Monitoring
- Tracks vital health parameters and daily activity
- Maintains historical health records
- Enables early detection of abnormal conditions

### 🚨 Intelligent Emergency Response (SOS)
- One-touch emergency trigger for elders
- Automatic alert escalation
- Simultaneous notifications to family, caretaker, and system logs

### 👥 Multi-Role System
The platform supports clearly defined user roles:
- **Elder** – Core user being monitored
- **Family Member** – Primary and Secondary roles with different permissions
- **Caretaker** – On-ground caregiver with health update responsibilities
- **Admin** – System and user management authority
- **Developer** – Codebase and infrastructure maintenance (no user data access)

### 🔐 Role-Based Access Control (RBAC)
- Permissions enforced at both UI and API level
- Strict separation of responsibilities
- Centralized permission matrix and role definitions

### 📡 Offline-First Capability
- Core actions work without internet
- Data stored locally and synced automatically
- Emergency events prioritized during sync

### 🔔 Smart Notifications
- Context-aware alerts
- Reduced false alarms
- Priority-based delivery

---

## Project Structure

```
VrudhSeva/
├── Assets/                          # Project-wide assets
│   └── images/                      # Diagrams, flowcharts, UI mockups
│       ├── .gitkeep                 # Ensures directory tracking
│       └── [architecture diagrams] # RBAC, data flow, sequence diagrams
│
├── AUTH/                            # Authentication & Authorization
│   ├── auth_structure.md            # Auth flow, RBAC, token strategy
│   ├── permission_matrix.md         # Centralized permission table
│   └── roles_definition.md          # Role hierarchy & scope
│
├── USERS/                           # User role documentation
│   ├── ELDER/                       # Core (Primary) user
│   │   ├── README.md                # Role overview (what & why)
│   │   └── DOCUMENT.md              # Detailed flows, APIs, permissions
│   │
│   ├── FAMILY/                      # Family members of Elder
│   │   ├── README.md                # Role overview
│   │   └── DOCUMENT.md              # Primary vs Secondary flow & access
│   │
│   ├── CARETAKER/                   # On-ground support user
│   │   ├── README.md                # Role overview
│   │   └── DOCUMENT.md              # Care workflows & accountability
│   │
│   ├── ADMIN/                       # System administrator
│   │   ├── README.md                # Admin responsibilities
│   │   └── DOCUMENT.md              # User mgmt, RBAC, system control
│   │
│   └── DEVELOPER/                   # Platform developer
│       ├── README.md                # Dev role & scope
│       └── DOCUMENT.md              # Dev workflow, CI/CD, security
│
├── FLOWS/                           # Application-level flows
│   ├── user_onboarding.md           # Elder → Family → Caretaker linking
│   ├── emergency_flow.md            # SOS & alert escalation
│   ├── health_data_flow.md          # Health data lifecycle
│   └── offline_sync_flow.md         # Offline-first sync logic
│
├── README.md                        # Project overview & vision
│
└── [Source_Code]                    # App, backend, configs, etc.(Not provided becuase of project is on Active Development)

```

## System Design Philosophy

- **Elder-first UX**: Minimal, accessible, and stress-free interaction
- **Fail-safe by design**: Emergency handling works in low-connectivity conditions
- **Security by default**: No unnecessary access to sensitive data
- **Documentation-driven development**: Every flow is clearly defined before implementation

---

## Authentication & Authorization

The system uses a **strict role-based access model** with clearly defined permissions.

Detailed documentation is available in:
- `AUTH/permission_matrix.md`
- `AUTH/roles_definition.md`

These documents define:
- Role hierarchy
- Allowed actions per role
- Security boundaries and restrictions

---

## Application Flows

Core system behavior is documented and standardized through dedicated flow documents:

- **User Onboarding Flow** – Elder → Family → Caretaker linking
- **Emergency Flow** – SOS triggering and escalation
- **Health Data Flow** – Collection, validation, alerts, and reporting
- **Offline Sync Flow** – Data consistency and conflict handling

These flows ensure predictable and reliable system behavior across all user roles.

---

## Technology Stack

### Frontend
- Flutter
- Figma (UI/UX design)

### Backend
- Python
- Java
- C++

### Database & Storage
- Firebase
- MongoDB
- Redis

### Communication & Realtime
- Custom backend services
- WebSockets
- Twilio (planned)

### Hardware Integration
- Fitness band / wearable devices (planned)

---

## Usage Overview

### For Elders
- Simple onboarding and login
- Minimal interaction required
- Emergency access always available
- View basic health summaries

### For Family Members
- Monitor elder’s health and activity
- Receive emergency alerts
- Manage care coordination (Primary member)

### For Caretakers
- Update health and activity data
- Respond to emergencies
- Follow assigned care schedules

---

## Documentation & Visual Assets

The project includes comprehensive documentation and visual references such as:
- System architecture diagrams
- Role-based user flows
- Emergency escalation diagrams
- Offline sync logic
- UI mockups and wireframes

These resources ensure clarity for developers, reviewers, and future contributors.

---

## Contribution Guidelines

Contributions are welcome and encouraged, provided they follow the project’s standards.

### How to Contribute
1. Fork the repository
2. Create a feature branch  
   ```bash
   git checkout -b feature/short-description
   ```

---

## Development Notes

- The project focuses on elderly care with emphasis on autonomous monitoring and emergency response
- Multi-role support ensures flexibility for different stakeholder needs
- Privacy and security are paramount in healthcare applications
- The system is designed to minimize user friction while maximizing safety

---

### Report Issues

For bug reports, feature requests, or general inquiries, please open an [Issue](https://github.com/jaymeen07-r/VrudhSeva/issues) on GitHub.

---

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## Contact & Support

* **Developer:** JAYMEEN N. VAGHELA
* **Email:** [jaymeenvaghela07@gmail.com](mailto:jaymeenvaghela07@gmail.com)
* **GitHub:** [github.com/jaymeen07-r](https://github.com/jaymeen07-r)

---
