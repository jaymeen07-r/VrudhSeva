# Health Data Flow

This document describes how health data is collected and used.

## Data Sources
- Caretaker (manual entry)
- Elder (basic input)
- External devices (future scope)

## Flow
1. Caretaker records health data
2. Data validated and stored
3. Family notified if abnormal values
4. Elder can view summary

## Access Rules
- Only Caretaker can write data
- Family and Elder can read data
- Admin can audit

## Flow Diagram

[Caretaker]
   ↓
[Health API]
   ↓
[Database]
   ↓
[Family & Elder Dashboards]

## Data Integrity
- Time-stamped entries
- Immutable history
