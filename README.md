# Pomodoro Timer

A beautiful, minimal Pomodoro timer with two modes: **Work** (traditional Pomodoro) and **Quinlan Travels** (YouTube creator workflow).

## Features

### Timer Modes

**Work Mode**
- Flexible work durations: 15, 20, or 25 minutes
- 5-minute rest periods
- Traditional Pomodoro workflow

**Quinlan Travels Mode**
- 20-minute sessions per production phase
- 8 video phases: Idea, Outline, Script, Edit, Retention pass, Intro build, Packaging, Upload
- Project and session tracking
- Saved intro lines per project

### Visual Design

- Animated gradient backgrounds that shift based on time of day (morning, afternoon, evening)
- Subtle floating particle effects
- Smooth transitions between work and rest states
- Breathing animation and progress ring during active sessions

### Session Tracking

- Tracks completed sessions per day
- Separate tracking for Work and Quinlan Travels modes
- Project-level session counts with phase breakdown
- All data persisted in localStorage

### Dashboard & Stats

- Days active count
- Today's sessions
- Total sessions (all-time)
- Visual chart showing session history over the past 30 days
- Filter by mode: Combined, Work only, Quinlan Travels only, Priorities, or Gratitude
- Project breakdown for Quinlan Travels sessions
- Progress River visualization showing 30-day consistency

### Opt-in Panels (hidden by default)

Click the menu icon (top-left) to reveal:

- **Priorities** — Set and track 3 daily priorities with completion progress
- **Gratitude Journal** — Record 3 daily gratitude items with streak tracking

These panels highlight based on time of day (priorities in the morning, gratitude in the evening) and have their own dashboard views.

### Other Features

- Browser notifications when sessions complete
- Session context display (current project and phase)
- Project autocomplete from history
- Keyboard accessible
- Responsive design (mobile, tablet, desktop)
- Single HTML file — no build process or dependencies

## Usage

1. Open `pomodoro.html` in a web browser
2. Select your mode (Work or Quinlan Travels)
3. For Work mode: choose duration and click Begin
4. For Quinlan Travels: enter project name, select phase, then click Start
5. Click "Stats" (top right) to view your session history
6. Click the menu icon (top left) to show/hide Priorities and Gratitude panels

## Data Storage

All data is stored in the browser's localStorage:
- `pomodoro_session_data` — Daily session counts
- `pomodoro_projects` — Project lists and intro lines
- `pomodoro_priorities` — Daily priority tracking
- `pomodoro_gratitude` — Gratitude journal entries
- `pomodoro_river` — Progress river visualization data
- `pomodoro_preferences` — Saved duration preferences

## Tech Stack

- Vanilla HTML, CSS, and JavaScript
- No external dependencies (except Google Fonts)
- Single-file architecture for simplicity
