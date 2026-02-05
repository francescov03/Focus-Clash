# FocusClash ⏱️🏆

FocusClash is an iOS app built with **SwiftUI** that helps users stay focused using timed focus sessions, while adding a light **gamification layer** through points, badges, and a leaderboard.

The app is designed to be clean, modern, and scalable, with a clear separation between UI, state, and business logic.

---

## ✨ Features

### ⏱️ Focus Timer
- Customizable focus and break durations
- Focus / break modes with smooth transitions
- Anti-distraction logic: leaving the app during a focus session resets progress
- Points are awarded every **5 minutes of focus**

### 🏆 Points & Leaderboard
- Points are persisted locally
- Global leaderboard (currently frontend-mocked)
- Podium view for top 3 users
- Dynamic ranking updates
- User rank is recalculated automatically based on points

### 🏅 Badges
- **Top 10 badge** for users ranked in the top 10
- Badge logic is data-driven (no fake or hardcoded badges)
- UI is ready for future real streak and achievement logic

### 👤 Profile & Game Center
- Game Center authentication
- Displays Game Center avatar and display name
- Profile summary with:
  - Badges
  - Total focus time
  - Current leaderboard rank
- Confetti animation on successful login

### ℹ️ Info & UX
- Clear explanation of how points work
- Examples of focus time → points conversion
- Haptic feedback for key actions
- Shimmer loading placeholders

---

## 🧠 Architecture

The project follows a **clean MVVM (plus Service folder) architecture**:
