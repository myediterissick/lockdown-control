# Lockdown Control

**Lockdown Control** is a tense control-room survival game where you don’t fight enemies directly — you **manage information and containment** in real time. You’re stationed in a central room with **five surrounding sections** and limited resources. Your goal is to stay alive by making smart decisions under pressure.

This project is currently an early prototype meant to be **small, playable, and expandable**.

---

## Core Idea

You are in a secure room with **five sections around you**:

**S1 · S2 · S3 · S4 · S5**

Enemies approach through these sections. You can’t freely see what’s happening — the facility is dark and visibility is limited. Survival is about:

- **Finding threats**
- **Stopping threats**
- **Not draining your resources too early**

---

## How You Survive

### 🔦 Flashlight Scanning (Battery 1)
Your flashlight is your only reliable way to locate enemies.

- You must **aim the flashlight** and **search** sections.
- Enemies are not automatically revealed — you need to **find them individually**.
- While the flashlight is on, it drains battery over time:
  - **0.1% battery per second**
- If your flashlight battery runs out, you lose your main source of information.

**Important:** Enemies **stop moving when directly illuminated**.

---

### 🚪 Doors / Traps (Battery 2)
Each section has a door/trap you can activate to slow or stop enemies.

- Doors use a completely **separate battery** from the flashlight.
- Doors only drain power **while closed** and **only when holding enemies**.
- Drain rate:
  - **0.2% door battery per second per active door**
- If door battery hits 0%, doors can no longer protect you.

---

## Difficulty Modes (Locked Per Run)

Difficulty is chosen in the main menu and cannot be changed mid-game.  
Each difficulty changes **enemy count** and **movement speed**.

- **Easy**
  - Fewer enemies
  - Slow movement speed
- **Medium**
  - More enemies
  - Normal movement speed
- **Hard**
  - High enemy pressure
  - Medium-to-fast movement speed
- **Nightmare**
  - Maximum enemy pressure
  - Fast movement speed

Enemies can stack in sections on higher difficulties, forcing tighter control and better scanning.

---

## Controls

- **F** — Toggle flashlight on/off
- **Mouse Move** — Aim flashlight beam
- **Mouse Click** — Toggle doors/traps (click the door bar area)

---

## Tips (No Spoilers)

- Don’t keep the flashlight on constantly — information has a cost.
- You can’t check everything at once. Prioritize based on pressure.
- Doors are powerful but expensive when used at the wrong time.
- Higher difficulties punish hesitation — staying calm matters.

---

## Project Status

This is an early-stage prototype focused on building a strong foundation:
- core systems
- difficulty scaling
- resource balancing
- real-time enemy pressure

Future updates can expand this into a full game with additional systems, behaviors, and progression.

---

## Run It Locally

1. Download or clone the repo
2. Open `index.html` in your browser  
   *(No install required.)*

---

## License

This project is for learning, testing, and future expansion.  
Feel free to fork and build on it.
