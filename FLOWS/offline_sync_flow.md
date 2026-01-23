# Offline Sync Flow

This document defines offline-first functionality.

## Purpose
Ensure continuity when internet is unavailable.

## Offline Behavior
- Actions stored locally
- Queue maintained on device
- Read-only mode for Elder

## Sync Process
1. Device detects connectivity
2. Local queue prepared
3. Data synced to server
4. Conflict resolution applied

## Priority Order
1. Emergency events
2. Health data
3. Messages
4. Logs

## Flow Diagram

[Offline Device]
   ↓
[Local Storage Queue]
   ↓ (Internet Available)
[Sync Engine]
   ↓
[Server]

## Conflict Handling
- Server timestamp has priority
- Admin notified for critical conflicts
