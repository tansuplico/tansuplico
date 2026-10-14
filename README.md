# Tristan Suplico

Full-stack developer in Cebu City, Philippines. I build offline-first software for places where the internet comes and goes.

[LinkedIn](https://www.linkedin.com/in/tansuplico/) · [Email](mailto:tsuplico772@gmail.com)

## APIIS LMS

A learning management system for rural Philippine communities. It started as a Tauri desktop app, and I'm moving it to a Railway-hosted web app.

- **Offline use:** students can keep learning without a connection, and progress syncs when it comes back.
- **Security audit:** I went through every backend controller and fixed missing ownership checks, race conditions, and a path traversal bug.
- **Video streaming:** each stream uses a short-lived JWT instead of one long-lived token.
- **Scope:** I cut a half-finished video download feature and per-user thumbnails because the complexity wasn't worth it.

Stack: React, TypeScript, Tailwind, Zustand, Node.js, Express, PostgreSQL, SQLite.

## Learning

React Native, to see how far the offline sync patterns from APIIS carry over to mobile.
