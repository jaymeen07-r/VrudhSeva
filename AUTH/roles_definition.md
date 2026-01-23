# Roles Definition – VrudhSeva

This document defines each system role, its scope, and authority level.

## 1. Elder
- Core user of the system
- Limited access
- Can trigger SOS
- Can view own data only

## 2. Family Member
### Primary Family Member
- Main decision authority
- Can edit Elder profile
- Can manage care schedules

### Secondary Family Member
- Support role
- View-only permissions
- Receives alerts

## 3. Caretaker
- On-ground service provider
- Updates health and activity data
- Responds to emergencies
- No account management permissions

## 4. Admin
- Full system authority
- Manages users, roles, permissions
- Assigns caretakers
- Controls system configuration

## 5. Developer
- Maintains codebase
- No access to production data
- Uses staging/testing environments only

## Role Hierarchy (High → Low)
Admin  
↓  
Family (Primary)  
↓  
Caretaker  
↓  
Family (Secondary)  
↓  
Elder
