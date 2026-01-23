# Family Member – Detailed Documentation

## 1. Role Description
Family members remotely monitor and support the Elder.
Primary and Secondary roles differ in permission levels.

## 2. Role Types
### Primary Family Member
- Full monitoring access
- Decision-making authority

### Secondary Family Member
- View-only access
- Receives alerts

## 3. Functional Flow
1. Login
2. Select linked Elder
3. View dashboard:
   - Health reports
   - Care status
4. Communicate with caretaker
5. Receive alerts

## 4. Permissions
| Action | Primary | Secondary |
|------|---------|----------|
| View Health Data | ✅ | ✅ |
| Edit Elder Info | ✅ | ❌ |
| Manage Care Schedule | ✅ | ❌ |
| Receive Alerts | ✅ | ✅ |

## 5. API Interaction
| API | Method | Purpose |
|----|-------|--------|
| /family/dashboard | GET | Overview |
| /elder/health | GET | Health reports |
| /alerts | GET | Emergency notifications |
| /caretaker/message | POST | Communication |

## 6. Security
- Role-based access enforcement
- Audit logs for primary member actions

## 7. Diagram
[Family App]
   ↓
[RBAC Layer]
   ↓
[Data Services]
