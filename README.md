# Procrastination – The App That Ends It

> **Welcome to Procrastination. The app that ends it.**

A full-stack SaaS-style habit-tracking app that gamifies productivity and helps users turn procrastination into progress.

---

## 🚀 Overview

**Procrastination** is built to make self-improvement simple, emotional, and engaging. It uses humor, gamification, and sleek design to transform bad habits into lasting motivation.

* 🧭 **Mission:** Help people stop procrastinating by gamifying progress.
* 🎯 **Vision:** A personal SaaS that evolves into team-based productivity software.
* 💡 **Tagline:** *Welcome to Procrastination. The app that ends it.*

---

## 🧱 Tech Stack

| Layer        | Technology                                                      |
| ------------ | --------------------------------------------------------------- |
| **Frontend** | Next.js, TypeScript, Tailwind CSS                               |
| **Backend**  | Firebase (Auth + Firestore)                                     |
| **Hosting**  | Vercel                                                          |
| **Auth**     | Firebase Email/Password + Google OAuth                          |
| **Design**   | Dark mode, gradients, micro-animations, confetti, rounded cards |

---

## 🧩 Core Features

### 🎬 Onboarding

* 4–5 step guided intro flow:

  * Welcome → “What’s your goal?”
  * Select 1–3 habits
  * Set frequency & rewards
  * Preview dashboard
* Smooth micro-animations and progress visuals.

### 📊 Dashboard

* Progress bar for each habit
* Weekly streak chart + Monthly heatmap
* “Today’s Focus” prompt (AI-generated)
* Floating action button for quick-add
* Persistent bottom nav: Dashboard / Analytics / Add Habit / Explore / Profile

### 🔁 Habit System

* XP + streak system with Focus Coins to recover missed habits
* Habit categories: Mind, Body, Work, Financial, Relationships
* Personalized habit identities (“Your Reading habit is proud of you 😎”)
* Bad habit cooldowns (limit sugar, screen time, etc.)

### 🕹️ Gamification

* Leveling system (1–100) with perks & badges
* Achievement milestones (7-day, 30-day, 100 total)
* Time-limited challenges (e.g., “Finish all by 9PM for XP”)
* Weekly review modal with reflections & motivational quotes

### 🌐 Social Features

* Optional streak sharing (private)
* Send encouragement messages (e.g., post-gym check-in)
* Dynamic motivational toasts (“Consistency > perfection.”)

### 📈 Data Visualization

* GitHub-style weekly heatmap
* AI correlation insights (“You sleep 19% better on days you read.”)

### 🎨 Personalization

* Goal Grid with categories & guided paths:

  * Fitness, Reading, Mindfulness, Financial, Relationships
* Routine builder + Focus Mode (distraction blocker)

### 📱 Mobile UX

* Swipe gestures:

  * Left → edit / stats / skip
  * Right → complete / add streak multiplier
* Card-based layout with icons and emojis (🍎 Eat Clean, 💧 Drink Water, 📚 Study)

### 🤖 Automation

* Health app integrations (Apple Health, Fitness, Sleep)
* Future AI habit suggestions

---

## 🧠 Product Philosophy

* **Humor + Accountability = Retention**
* **Gamification = Long-term consistency**
* **Identity = Connection**

Every tap should spark delight — via motion, sound, or feedback.

---

## 🧭 Roadmap

### Phase 1: MVP

* Animated onboarding
* Progress tracking, heatmap, and badges
* Weekly review modal
* Core habit engine

### Phase 2: Social + Smart Features

* Friend encouragement, Focus Coin economy
* AI habit optimization & insights

### Phase 3: Enterprise Expansion

* *Procrastination for Teams* — productivity challenges, leaderboards, Slack integration

---

## ⚙️ Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/procrastination.git
   cd procrastination
   ```
2. **Install dependencies:**

   ```bash
   npm install
   ```
3. **Create `.env.local` file:**

   ```env
   NEXT_PUBLIC_FIREBASE_API_KEY=your_key_here
   NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_domain_here
   NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id_here
   ```
4. **Run the development server:**

   ```bash
   npm run dev
   ```
5. **Deploy to Vercel:**

   * Connect your GitHub repo to Vercel.
   * Add environment variables in Vercel dashboard.
   * Deploy 🚀

---

## 📜 License

MIT License — open for educational and portfolio use.

---

## ✨ Credits

Developed by **Rafael Valera** — empowering people to end procrastination and take action.


# Procrastination-App
Personal SaaS-like app.
