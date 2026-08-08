# 💧 Hydra — Water Monitor

A personal hydration tracker that sets your daily water goal based on your age, gender, weight, activity level, and climate.

## 🔗 Live

**https://arecibo-sys.github.io/hydra-water-monitor/**

## ✨ Features

- **Personalized daily goal** — calculated from age, gender, weight, activity, and climate
- **Animated progress ring** — see your % of goal at a glance
- **Quick-log buttons** — tap 250 / 500 / 750 / 1000 ml in one tap
- **Today's log** — every drink recorded with a timestamp, deletable
- **Auto-resets daily** — fresh start each day, history persists in your browser
- **Edit profile anytime** — tweak your settings and the goal recalculates

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
