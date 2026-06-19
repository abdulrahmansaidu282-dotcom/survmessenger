# Architecture

## Overview

SurvMessenger is designed using a modular architecture that supports scalability, reliability, and future ecosystem integration.

---

# Client

Flutter

Supports Android and iOS from one codebase.

---

# Backend

Node.js

REST APIs

WebSocket Server

---

# Database

PostgreSQL

Stores:

- Users
- Messages
- Projects
- Files
- Permissions
- Notifications

---

# Cache

Redis

Used for:

- Sessions
- Rate limiting
- Caching
- Presence status

---

# File Storage

Secure cloud object storage

Stores:

- Images
- PDFs
- Drawings
- Videos
- Documents

---

# Authentication

- Email
- Phone
- JWT
- Refresh Tokens
- Multi-factor authentication

---

# Integration

Designed to integrate with:

- SurvPay
- SurvPrice
- SurvMarket

using shared authentication and APIs.

---

# Scalability

Future infrastructure includes:

- Load balancing
- Auto scaling
- CDN
- Containerization
- Distributed services
