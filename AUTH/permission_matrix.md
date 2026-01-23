# Permission Matrix – VrudhSeva

This document defines **role-based access control (RBAC)** across the platform.
It serves as the single source of truth for permissions.

## Roles
- Elder
- Family (Primary)
- Family (Secondary)
- Caretaker
- Admin
- Developer

## Permission Matrix

| Feature / Action                     | Elder | Family (P) | Family (S) | Caretaker | Admin | Developer |
|-------------------------------------|:-----:|:----------:|:----------:|:---------:|:-----:|:---------:|
| Authentication / Login              | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| View Elder Profile                  | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Edit Elder Profile                  | ❌ | ✅ | ❌ | ❌ | ✅ | ❌ |
| Trigger Emergency (SOS)              | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Receive Emergency Alerts            | ❌ | ✅ | ✅ | ✅ | ✅ | ❌ |
| View Health Records                 | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ |
| Add / Update Health Data            | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ |
| Manage Care Schedule                | ❌ | ✅ | ❌ | ✅ | ❌ | ❌ |
| Assign / Remove Caretaker           | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| User Management                     | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| System Configuration                | ❌ | ❌ | ❌ | ❌ | ✅ | ❌ |
| Access Source Code                  | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |

## Notes
- Permissions are enforced at API and UI level
- Primary Family member has higher authority
- Developer has **no access to user data**
