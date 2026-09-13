Healthy Body: Offline-First Fitness & Habit Tracker

Healthy Body is a lightweight, Progressive Web App (PWA) designed for private, high-performance fitness and habit tracking. Built entirely with vanilla web technologies (HTML, CSS, JavaScript), it operates as a "local-first" application, utilizing the browser's localStorage for database-free, instant data persistence. The architecture ensures complete offline functionality, rapid load times, and absolute data privacy.

Core Features

Template Builder & Split Manager: A dedicated library to design, nest, and modify multi-day training splits (e.g., 4-day hypertrophy programs) without cluttering the daily execution interface.

Active Workout Engine: An execution-focused tracking board featuring automatic volume calculation (Sets × Reps × Weight), a floating 90-second rest timer, and a "Ghost Set" mechanism that auto-fills the previous week's performance to enforce progressive overload.

Dynamic Daily Goals: A gamified habit tracker for daily objectives (e.g., 7k steps, Dead Hangs, Mobility Routine) with an interactive progress bar, motivational prompts, and automatic midnight resets.

Dedicated Mobility Board: An isolated interface for daily stretching routines, supporting embedded local media (MP4/JPG) for form reference.

Health Metrics Tracking: A restricted daily weight log that prevents future-date entries and calculates a rolling 7-day average.

Secure Local Environment: Hardcoded authentication for private, invite-only access, complemented by a JSON export/import system to backup and restore user data manually across devices.
