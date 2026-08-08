# 💧 Hydra — Water Monitor

A personal hydration tracker that sets your daily water goal based on your age, gender, weight, activity level, and climate.

## 🔗 Live

**https://arecibo-sys.github.io/hydra-water-monitor/**

## ✨ Features

- **Personalized daily goal** — calculated from age, gender, weight, activity, and climate
- **Animated progress ring** — see your % of goal at a glance
- **Quick-log buttons** — tap 250 / 500 / 750 / 1000 ml in one tap
- **Custom amount** — log any ml with a custom input
- **Today's log** — every drink recorded with a timestamp, deletable
- **Auto-resets daily** — fresh start each day, history persists in your browser
- **Edit profile anytime** — tweak your settings and the goal recalculates
- **⏰ Reminders** — configurable nudge every 30/60/90/120 min via browser notifications + in-app toast
- **📊 Weekly chart** — last 7 days of intake vs goal as a bar chart
- **🔥 Streak & history** — consecutive days meeting goal, best streak, and a recent-days heatmap
- **🎉 Milestone messages** — encouraging notes at 25/50/75/100% of goal
- **🔔 Sound on goal** — optional chime when you hit 100% (Web Audio, no files)
- **Stats row** — today's total, glasses count (250 ml = 1), and % of goal

## 🧮 How the goal is calculated

- Base: 35 ml/kg (male) or 31 ml/kg (female)
- Age adjustment: −5% at 40+, −10% at 55+
- × activity multiplier (sedentary → very active)
- × climate (hot/humid adds 10%)

## 🛠 Tech

- Single-file HTML + CSS + vanilla JS
- No dependencies, no build step
- Data stored locally in `localStorage`

## 🎨 Design

- Beige + black palette, warm and minimal
- Smooth ring animation, clean cards
- Mobile-first, works great on iPad

---

*Built with Hermes Agent.*
