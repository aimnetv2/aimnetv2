# 🎮 aimnetv2 – AI Fortnite 1v1 Learning

**aimnetv2** is a personal project aiming to develop an artificial intelligence capable of learning Fortnite 1v1 mechanics by observing real players and then improving through self-play reinforcement learning.

---

## 🚀 Project Goal

The mission is to build an AI that can:

- 🧠 Learn advanced Fortnite mechanics (edits, builds, aim...) from real gameplay
- 📈 Improve by training against itself (AI vs AI self-play)
- 🤖 Simulate human-like decisions in competitive 1v1 scenarios

---

## 🧩 What's already done

- ✅ Full keyboard/mouse input logging (`inputs.txt`)
- ✅ 1v1 gameplay recordings with OBS
- ✅ Inputs displayed in sync with gameplay
- ✅ First logs structured as clean, timestamped data for AI training

---

## 📦 Sample input log

Example of `inputs.txt` data:

2025-07-14 15:23:01.123 | KEY_PRESS | w
2025-07-14 15:23:01.456 | MOUSE_DOWN | Button.left | x:1250 | y:710
2025-07-14 15:23:01.720 | KEY_PRESS | space


This allows us to transform gameplay into data readable by machine learning models.

---

## 🛠️ Next Steps

- 🔄 Synchronize dual-player logs (inputs + positions)
- 📚 Build the first training dataset
- 🤖 Develop a simple prototype AI for 1v1 situations
- 📹 Launch a public demo video to attract collaborators & supporters

---


🧠 Learning Phases of aimnetv2 AI
Phase 1 – Observation Learning (Supervised Learning)
In this initial stage, the AI passively observes gameplay from professional 1v1 Fortnite fights.
Using structured logs (inputs, timings, positions), the model learns to recognize and replicate human behavior and mechanical patterns such as:

Edit + Shot sequences

Wall takes

Build-and-replace moves

General movement and rhythm

📌 Approx. 10 hours of pro gameplay are used to train the model in this phase.

🔸 Goal: Give the AI a mechanical and tactical foundation
🔸 Expected Skill Level: Creative Newbie → Low Arena tier

Phase 2 – Self-Play Reinforcement (3 Months)
Once the AI has learned the basics, it enters a self-play loop where it trains by fighting against copies of itself — up to 50 simultaneous 1v1s in a custom environment.

Each match produces rewards, failures, and feedback that help it improve over time.

🧠 Over 3 months of continuous training, the AI evolves through:

Week 1: Learns basic defense and rush strategies (Arena Silver)

Week 2: Begins using boxfights and edit-peeks (Arena Gold)

Week 4: Adapts to different opponents and meta (Arena Platinum)

Month 2: Consistently wins against earlier versions of itself (Champion League)

Month 3: Shows emergent behavior and high-level play (Top Creative Warrior)


## 🤝 Looking for contributors

I’m currently looking for:

- 👨‍💻 AI / Reinforcement Learning developers
- 🎮 Pro/semi-pro players willing to share POV + logs
- 💰 Funding to build the first prototype (~€800 target)

➡️ **Contact**: [discord : flynx83 mail : aimnetv2@gmail.com]  

---

## 📺 Demo Video

> 🔗 Watch the showcase here: [(https://youtu.be/I5IRE8fC2_Q)]

---

## 👤 About me

I’m Quentin, a Fortnite player passionate about both competitive mechanics and AI systems.  
I started this project to explore how far an AI can go when trained like a human player — with real input data and thousands of 1v1s.

---

## 📄 License

MIT License – Free to use, modify, and contribute with credit.
<!--
**aimnetv2/aimnetv2** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
