# Assets – Images Documentation

This directory contains all visual assets used in the **VrudhSeva** project.  
These images support system documentation, architecture explanation, user flows, and evaluation.

All diagrams are referenced across:
- Project `README.md`
- `USERS/*/DOCUMENT.md`
- `AUTH/` and `FLOWS/` documentation

---

## 📁 Directory Structure

```text
Assets/
└── images/
    ├── .gitkeep
    │
    ├── architecture/
    ├── user_flows/
  Assets/
└── images/
    ├── .gitkeep
    │
    ├── architecture/             # High-level system design
    │   ├── system_overview.png
    │   ├── rbac_architecture.png
    │   └── client_server_flow.png
    │
    ├── user_flows/                # Role-wise application flows
    │   ├── elder_flow.png
    │   ├── family_flow.png
    │   ├── caretaker_flow.png
    │   └── admin_flow.png
    │
    ├── auth/                      # Authentication & authorization
    │   ├── login_flow.png
    │   ├── token_lifecycle.png
    │   └── permission_matrix.png
    │
    ├── emergency/                 # SOS & alert handling
    │   ├── emergency_flow.png
    │   ├── escalation_chain.png
    │   └── retry_mechanism.png
    │
    ├── health/                    # Health data visuals
    │   ├── health_data_flow.png
    │   ├── vitals_tracking.png
    │   └── abnormal_alerts.png
    │
    ├── offline_sync/              # Offline-first logic
    │   ├── offline_queue.png
    │   ├── sync_process.png
    │   └── conflict_resolution.png
    │
    ├── ui_mockups/                # App screens (optional but powerful)
    │   ├── elder_dashboard.png
    │   ├── sos_screen.png
    │   ├── caretaker_entry.png
    │   └── family_dashboard.png
    │
    └── diagrams_source/           # Editable source files
        ├── rbac.drawio
        ├── system_architecture.drawio
        └── flows.excalidraw

