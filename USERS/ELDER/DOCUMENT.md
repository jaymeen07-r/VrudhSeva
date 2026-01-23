# Elder – Detailed Documentation

## 1. Role Description
The Elder is the central user of the VrudhSeva platform.  
All services are designed to ensure safety, health, and ease of use.

## 2. Functional Flow
1. Elder logs into the application
2. Dashboard displays:
   - Emergency button
   - Health overview
   - Messages from family/caretaker
3. Elder performs limited actions
4. System notifies family/caretaker as required

## 3. Permissions
- Read-only access to personal data
- Can trigger emergency alerts
- Cannot modify system or user settings

## 4. API Interaction (Logical)
| API | Method | Purpose |
|----|-------|--------|
| /auth/login | POST | Authenticate Elder |
| /elder/profile | GET | Fetch profile data |
| /elder/sos | POST | Trigger emergency |
| /elder/health | GET | View health data |

## 5. Security Constraints
- No write permissions on critical data
- SOS API has highest priority
- Session timeout shorter for safety

## 6. Diagram (Conceptual)
[Elder App]
   ↓
[API Gateway]
   ↓
[Notification Service]
   ↓
[Family & Caretaker Devices]

## 7. Design Notes
- UI must be minimal
- Large buttons and clear labels
- Fail-safe emergency handling
