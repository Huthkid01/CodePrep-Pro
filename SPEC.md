# Technical Interview Prep - Specification

## Project Overview
- **Project Name**: CodePrep Pro - Technical Interview Prep Platform
- **Type**: Frontend-only Web Application
- **Core Functionality**: Practice coding challenges with timer, difficulty levels, and progress tracking
- **Target Users**: Software developers preparing for technical interviews

## Features (Minimum 3+)
1. **Coding Challenges** - 10+ algorithmic challenges across 3 difficulty levels
2. **Timer System** - Countdown timer per challenge with pause/resume
3. **Progress Tracking** - Track completed challenges, scores, time spent
4. **Code Editor** - Built-in code editor with syntax highlighting
5. **Difficulty Levels** - Easy, Medium, Hard categories
6. **Solution Reveal** - Show hints and final solutions
7. **Statistics Dashboard** - Overall progress, average time, success rate

## UI/UX Specification

### Layout Structure
- **Header**: Logo, navigation, stats summary
- **Sidebar**: Challenge list by difficulty
- **Main Area**: Code editor + problem description
- **Footer**: Timer, submit button, progress bar

### Visual Design
- **Color Palette**:
  - Primary: #0f172a (Dark navy)
  - Secondary: #1e293b (Slate)
  - Accent: #22d3ee (Cyan)
  - Success: #10b981 (Green)
  - Warning: #f59e0b (Amber)
  - Error: #ef4444 (Red)
  - Text: #f8fafc (Light)
- **Typography**:
  - Headings: 'Outfit', sans-serif
  - Body: 'Source Sans 3', sans-serif
  - Code: 'JetBrains Mono', monospace
- **Spacing**: 8px base unit
- **Effects**: Subtle glow on buttons, smooth transitions

### Components
- Challenge cards with difficulty badges
- Countdown timer with color changes (green→amber→red)
- Code editor with line numbers
- Progress charts
- Category tabs
- Modal for solutions

## Functionality
1. **Challenge Selection**: Browse by difficulty, select challenge
2. **Timer**: Start on challenge open, countdown, auto-pause on blur
3. **Code Editor**: Textarea with basic syntax highlighting
4. **Submit**: Check answer, show result
5. **Hints**: Progressive hints (costs time to use)
6. **History**: Store in localStorage
7. **Statistics**: Calculate and display metrics

## Acceptance Criteria
- [ ] Can browse and select challenges
- [ ] Timer works correctly (start, pause, reset)
- [ ] Can write and submit code
- [ ] Progress saved to localStorage
- [ ] Statistics displayed accurately
- [ ] Responsive on mobile
- [ ] Live deployment accessible
