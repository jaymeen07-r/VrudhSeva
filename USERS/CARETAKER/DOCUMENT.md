# Caretaker – Detailed Documentation

## 1. Role Description
Caretaker provides daily physical and medical assistance to the Elder.

## 2. Functional Flow
1. Login
2. View assigned Elder(s)
3. Update:
   - Health metrics
   - Daily activity logs
4. Respond to alerts
5. Report to family

## 3. Permissions
- Write access to health and care data
- No authority over user accounts

## 4. API Interaction
| API | Method | Purpose |
|----|-------|--------|
| /caretaker/assignments | GET | Assigned elders |
| /health/update | POST | Submit health data |
| /alerts/respond | POST | Emergency response |
| /reports | POST | Care reports |

## 5. Security & Accountability
- Every action logged
- Time-stamped updates
- Admin-reviewable logs

## 6. Diagram
[Caretaker App]
   ↓
[Health Service]
   ↓
[Family Dashboard]

## 7. Notes
- Offline-first capability recommended
- Mandatory daily sync
