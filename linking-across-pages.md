---
layout: default
title: 6-Adding Page Transitions with Smart Animate
nav_order: 7
parent: Workshop Activities
---

### Section Preview

This is where your design stops being a picture and starts behaving like a real UI.
We will switch to **Prototype mode** and use **Smart Animate** so transitions look smooth instead of cheap.

<div style="display:flex; gap:16px; flex-wrap:wrap; align-items:flex-start;">
  <img src="images/prototype-mode.png" style="width:48%; min-width:260px; border:1px solid #e5e7eb; border-radius:10px;" alt="Prototype tab location">
  <img src="images/smart-animate.png" style="width:48%; min-width:260px; border:1px solid #e5e7eb; border-radius:10px;" alt="Smart Animate option">
</div>

---

# Prototyping: Making it Clickable

> **Mode switch:** On the right sidebar, click the **Prototype** tab.

## 1) Connect “Home” (from Portfolio → Home)

1. Go to your **Portfolio** frame.
2. Click the **Home** text in the header (select the text layer).
3. In **Prototype** mode, drag the small connector (the little circle) to the **Home** frame.
4. Set:
   - **On Click**
   - **Navigate to:** Home
   - **Animation:** **Smart Animate**
   - **Duration:** 300ms

<img src="images/smart-animate.png" style="width:70%; max-width:820px; border:1px solid #e5e7eb; border-radius:10px;" alt="Smart Animate setting">

## 2) Connect “Portfolio” (from Home → Portfolio)

1. Go to your **Home** frame.
2. Select the **Portfolio** text in the header.
3. Drag the connector to the **Portfolio** frame.
4. Use the same settings:
   - **On Click**
   - **Navigate to:** Portfolio
   - **Smart Animate**
   - 300ms

## 3) Connect the main button (Home → Portfolio)

1. On the **Home** frame, select your **My Portfolio** button (the whole group/frame).
2. Drag the connector to the **Portfolio** frame.
3. Again:
   - **On Click**
   - **Navigate to:** Portfolio
   - **Smart Animate**
   - 300ms

---

# Present Mode (the test)

1. Select your **Home** frame.
2. Click the **Play (Present)** button (top right).
3. Click around:
   - Header links
   - Button
4. Watch for this: the header should feel consistent and transitions should be smooth (Smart Animate doing its job).

---

# Workshop Complete

You now have:
- Frames for structure
- Auto Layout for clean spacing
- Components for repeatable content
- A clickable prototype with Smart Animate

[NEXT STEP: Designing the About Me Page](about-page.html){: .btn .btn-blue }
