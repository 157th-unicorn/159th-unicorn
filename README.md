# Live Streaming Website

A website where an admin can live stream to over 25,000 viewers. The admin streams via WebRTC with Firebase signaling, and viewers watch via HLS. Features a modern, responsive design with CSS styling.

## Repository Structure

- `index.html`: Client-side HTML with embedded CSS and JavaScript
- `server.js`: Server-side JavaScript
- `package.json`: Server dependencies
- `README.md`: Project instructions

## Prerequisites

- Node.js and npm installed
- Firebase project with Realtime Database enabled
- A server capable of transcoding WebRTC to HLS (e.g., OvenMediaEngine) for production

## Setup

### 1. Firebase Configuration
- Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
- Enable Realtime Database.
- Download your service account key JSON and place it beside `server.js` as `serviceAccountKey.json`.
- The Firebase config is already in `index.html`.

### 2. Server Setup
- Install dependencies:
  ```bash
  npm install
