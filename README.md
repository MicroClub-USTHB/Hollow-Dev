# Hollow Dev Hackathon Challenges

This repository contains backend/full-stack challenge statements for the **Hollow Dev Hackathon**, organized by difficulty.

## Repository Structure

- `1-Easy/` → beginner-friendly API challenges
- `2-Medium/` → intermediate real-time and system challenges
- `3-Hard/` → advanced full-feature application challenges
- `MustRead.md` → global hackathon rules and judging criteria

## Global Rules (Summary)

Participants should:
- Use any preferred tech stack.
- Return API responses in JSON.
- Store challenge data in a database.
- Keep a clean project structure (models, routes, middlewares, etc.).
- Keep a uniform response object format across endpoints.
- Store environment variables in `.env`.
- Host APIs for difficult challenges.
- Document each challenge solution.
- Submit a GitHub repository link for each challenge.
- Build only a basic frontend when required (design is not the focus).

See full rules in [`MustRead.md`](MustRead.md).

## Judging Criteria

Projects are evaluated on:
- Innovation
- Functionality
- Usability
- Scalability
- Code Quality

## Challenges

## 1-Easy

### 1) Game Characters CRUD API
File: `1-Easy/CrudApi.md`

Build a RESTful CRUD API to manage game characters, including pagination and middleware for not-found/internal-server errors.

**Bonus:** Add request validation middleware for POST/PUT.

### 2) File Uploading System
File: `1-Easy/fileUploader.md`

Build an API-driven file uploading system with file storage on server and metadata persistence in a database, including endpoints for create/read/update/delete and file retrieval.

**Bonus:** Upload a copy to cloud storage.

## 2-Medium

### 1) Online Form
File: `2-Medium/OnlineForm.md`

Develop a form platform similar to Google Forms with authentication, unlimited user forms, a basic frontend, and secure response storage/retrieval.

**Bonus:** Real-time collaborative editing via WebSocket.

### 2) Server Monitoring App
File: `2-Medium/ServerMonitoring.md`

Create a monitoring dashboard for CPU/RAM, directory browsing/management, and controlled server interactions (services/files/scripts) with strong security.

### 3) Voting System
File: `2-Medium/VotingSystem.md`

Implement a voting system with admin/user roles, admin-only candidate creation, anti-duplicate voting safeguards, server event logging, and secure authentication.

**Bonus:** Integrate Web3 for transparency/security.

### 4) Tic Tac Toe Game
File: `2-Medium/xoGame.md`

Create a real-time multiplayer tic-tac-toe app (frontend + backend) using websockets with server-side game event logging.

**Bonus:** Room system and user account system.

## 3-Hard

### 1) Chat App
File: `3-Hard/ChatApp.md`

Build a real-time chat app with authentication, rooms, frontend, GraphQL API, and CDN usage.

**Bonus:** Online/offline user status.

### 2) Learning Platform
File: `3-Hard/LearningPlatform.md`

Develop a secure learning platform with GraphQL, role hierarchy (admin/sub-admin), course management, admin dashboard, payment integration, progress tracking, certificates, and frontend.

**Bonus:** Quizzes and forums.

### 3) Meeting Application
File: `3-Hard/meeting.md`

Develop a meeting app with authentication, real-time chat, code-based meeting rooms, WebRTC communication, frontend, and camera support.

**Bonus:** Screen sharing.
