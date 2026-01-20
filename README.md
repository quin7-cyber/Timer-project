# Pomodoro Timer

A beautiful, minimal Pomodoro timer with two modes: **Work** (traditional Pomodoro) and **Quinlan Travels** (YouTube creator workflow).

## Features

### Timer Modes

**Work Mode**
- Flexible work durations: 25, 45, or 60 minutes
- 5-minute rest periods
- Traditional Pomodoro workflow

**Quinlan Travels Mode**
- 20-minute editing sessions
- 2-minute intro work sessions
- Project and session tracking
- Saved intro lines per project

### Visual Design

- Animated gradient backgrounds that shift based on time of day (morning, afternoon, evening)
- Floating particle effects
- Smooth transitions between work and rest states
- Breathing animation during active sessions

### Session Tracking

- Tracks completed sessions per day
- Separate tracking for Work and Quinlan Travels modes
- Project-level session counts for Quinlan Travels
- All data persisted in localStorage

### Dashboard & Stats

- Days active count
- Today's sessions
- Total sessions (all-time)
- Visual chart showing session history over the past 14 days
- Filter by mode: Combined, Work only, or Quinlan Travels only
- Project breakdown for Quinlan Travels sessions

### Other Features

- Browser notifications when sessions complete
- Session context display (current project and next action)
- Project autocomplete from history
- Single HTML file - no build process or dependencies

## Usage

1. Open `pomodoro.html` in a web browser
2. Select your mode (Work or Quinlan Travels)
3. For Work mode: choose duration (25/45/60 min) and click Start
4. For Quinlan Travels: enter project name, then click "Start Editing" or "Start Intro"
5. Click the stats icon (top right) to view your session history

## Data Storage

All session data is stored in the browser's localStorage:
- `pomodoro-session-data` - Daily session counts
- `pomodoro-projects` - Project lists and intro lines

## Tech Stack

- Vanilla HTML, CSS, and JavaScript
- No external dependencies (except Google Fonts)
- Single-file architecture for simplicity
