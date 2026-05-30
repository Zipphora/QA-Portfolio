# User Journey Stages: BeReal Core Product Lifecycle
**Date:** May 30, 2026  
**Author:** Zipphora Platania<br>
**Role:** Product Management Extern (Product Quality & UX Focus)

## Executive Summary
A comprehensive breakdown of the 5 fundamental user journey stages within the BeReal ecosystem. This map serves as the structural backbone for identifying user friction points, mapping out functional test cases, and evaluating system load constraints during synchronous app usage.

---

## The 5 Core Journey Stages

### 🎯 Stage 1: Core Onboarding & Activation
* **Description:** The user downloads the mobile application, completes registration, syncs device contacts to locate friends, and grants system-level permissions (Camera and Push Notifications).
* **Quality Assurance Impact:** High-stakes entry point. Testing must validate phone number authentication loops, API response latencies during contact syncing, and permission prompt behavior across various iOS/Android versions.

### 🔔 Stage 2: The Trigger Event (Notification Retrieval)
* **Description:** The user encounters the unpredictable, global, and synchronous "⚠️ It's Time to BeReal ⚠️" push notification while interacting in the real world.
* **Quality Assurance Impact:** System performance and edge-case testing. Engineers must validate push notification reliability across global time zones and stress-test the backend architecture for the sudden influx of millions of concurrent user sessions within a 120-second window.

### 📸 Stage 3: Content Capture & Creation
* **Description:** The user initializes the app, triggering a real-time 2-minute countdown timer. They utilize the dual-camera interface to capture a simultaneous front-and-back, completely unedited image.
* **Quality Assurance Impact:** Core business logic verification. Critical testing scripts must evaluate the countdown timer's accurate degradation, hardware-level camera toggle behaviors, and precise calculation of the "Late Post" metadata timestamp if the window is missed.

### 💬 Stage 4: Social Discovery & Engagement
* **Description:** Once the user uploads their content, the global feed unlocks. The user scrolls through their network's updates, crafts custom "RealMoji" reactions, and interacts via discussion threads.
* **Quality Assurance Impact:** Dynamic data rendering and UI/UX validation. Testers verify real-time state synchronization (e.g., instant emoji rendering), lazy loading behavior for images, and edge-case rendering of comments under high-traffic network constraints.

### 🚪 Stage 5: Session Termination & Retention
* **Description:** The user completes their social consumption loop, closes the application, and resumes daily routines until the push notification loop resets the following day.
* **Quality Assurance Impact:** Long-term product health metrics. QA monitors application background behavior, caching efficiency to optimize battery/data drainage, and verification that notification tokens remain active to secure long-term user retention (DAU/MAU).
