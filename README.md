# Ataraxia
be serene

**A Gamified, Offline-First Progressive Web App (PWA) for Inner Peace and Self-Improvement**

Ataraxia is a gamified, offline-first Progressive Web App (PWA) that empowers users to achieve inner peace and self-improvement through structured progress tracking, habit building, and reflective journaling. Whether you’re working on personal goals, breaking bad habits (e.g., irregular sleep or excessive habits), or reflecting on your growth, Ataraxia is your companion for finding peace through progress—infused with a nostalgic, 90s video game vibe.

---

## Overview

Ataraxia combines mindfulness, productivity, and gamification to create a seamless and motivating experience. With its retro-GTA-inspired interface (featuring neon pink, green, and yellow text, pixelated fonts, and calming palm tree visuals), Ataraxia transforms self-improvement into an exciting yet serene journey. Perfect for college students or anyone seeking balance, it helps you track major goals, set daily/weekly objectives, and visualize your growth—all while working seamlessly offline and syncing online when available.

---

## Core Features

### 1. Major Goals
- Set long-term goals like skills you want to learn (e.g., "Learn Python"), bad habits you want to lose (e.g., "Reduce irregular sleep," "Stop fapping"), or good habits you want to develop (e.g., "Meditate daily," "Wake up on time").
- Short, concise descriptions for each goal to keep focus clear.

### 2. Minor Daily/Weekly Goals
- Break down major goals into smaller, actionable daily or weekly tasks (e.g., "Meditate for 10 minutes daily" for the "Meditate daily" major goal).
- Track progress toward major goals with these bite-sized objectives.

### 3. Instant Notes and Goals
- Quickly jot down thoughts, ideas, or goals on the go.
- Unfinished goals automatically roll over to the next day/week, ensuring nothing is forgotten.

### 4. Offline-First Design
- Works seamlessly offline using IndexedDB and service workers.
- Syncs data to the cloud when online, ensuring your progress is always saved and secure.

### 5. Calming Reminders
- Receive gentle, non-intrusive notifications to stay on track with your goals and habits.
- Designed to promote mindfulness and reduce stress, with soothing visuals and sounds.

---

## Technology Stack

- **Frontend**: Angular (with Clarity UI for a clean, professional design, or Tailwind CSS for customizable, minimalist styling).
- **Storage**: IndexedDB for local, offline data storage.
- **Offline Support**: Service workers (via Angular PWA) for offline functionality and caching.
- **Backup/Restore**: Export/import data as JSON files for easy backup and restoration.

---

## Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm (comes with Node.js)
- Angular CLI (`npm install -g @angular/cli`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ataraxia.git
   cd ataraxia
