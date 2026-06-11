---
title: "Pomora"
description: "A unified productivity ecosystem combining a sophisticated Discord Bot and a synchronized Next.js Web Dashboard. Features real-time voice channel tracking, gamified focus sessions, and a robust hybrid database architecture."
date: 2026-02-04
tags: ["Bun","PosgreSQL","Next.js","Discord.js"]
featured: false
image: "https://raw.githubusercontent.com/sirrryasir/Pomora/main/web/public/images/logo-bg.png"
url: "https://pomora.yaasir.dev/"
github: "https://github.com/sirrryasir/Pomora"
---

# Pomora

Pomora helps you stay focused with a gamified study timer that seamlessly bridges your community and personal dashboard.

## The Problem
Maintaining focus during long study or work sessions is challenging, especially in isolation. While many productivity tools exist (timers, to-do lists, music bots), they are often disconnected from where communities actually interact—Discord. Users frequently switch between a timer app, a music bot, and a web dashboard, breaking their flow state and accurate time tracking becomes a manual burden.

## The Solution
**Pomora** is a unified productivity ecosystem designed to integrate deep work with community accountability. It consists of two synchronized applications sharing a **Hybrid Database Architecture**:

1.  **The Discord Bot**: An intelligent agent that manages real-time voice channel interactions. It automatically tracks focus/break intervals when users join "Study Rooms," enforcing accountability through smart inactivity checks (e.g., the "Lazy Check-in" system).
2.  **The Web Dashboard**: A visual interface providing detailed analytics, leaderboards, and task management. It allows users to visualize their productivity trends over time without leaving the ecosystem.

## The Impact
*   **Seamless Synchronization**: Data written by the bot (via **PostgreSQL/Neon**) is instantly available on the web dashboard, providing real-time feedback loops.
*   **Community Engagement**: Gamified leaderboards and voice-based attendance drive server activity and healthy competition.
*   **Resilient Architecture**: Leverages a robust hybrid approach—**Supabase** for secure web authentication (OAuth) and **Neon (Postgres.js)** for high-performance, low-latency bot data operations.

## Key Features
*   **Voice-Based Passive Tracking**: Automatically logs study hours when users join specific voice channels, removing manual start/stop friction.
*   **Smart Inactivity Logic**: Intelligent filters distinguish between accidental disconnects and true inactivity, ensuring fair tracking.
*   **Review & Analytics**: Comprehensive dashboards to review past sessions, analyze peak productivity times, and set future goals.
