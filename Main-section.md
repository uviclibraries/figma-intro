---
layout: default
title: 4-Designing the Main (The Magic Button)
nav_order: 6
parent: Workshop Activities
---

### Section Preview
We have a header, but our page is empty. We are going to design the "Hero" section—the first thing people see. We will build a **Responsive Button** that expands automatically when you change the text.

<img src="images/home-final.png" style="width:60%;">

---

# Designing the Main Section

## 1. The "Hook" (Headline)
1.  Select your **Home** frame.
2.  Press **T** (Text) and click in the center of the page.
3.  Type: **"Designing with Purpose"**.
4.  **Style:**
    * **Font:** Noto Serif JP
    * **Size:** 64
    * **Color:** White
    * **Align:** Center
5.  Position it about **100px** below your Header.

## 2. The Sub-Headline
1.  Press **T** and click below your headline.
2.  Type:
    ```
    I am a researcher and designer focused on digital accessibility.
    ```
3.  **Style:** Noto Serif JP, Size 24, Regular, White, Center.
4.  **Align:** Select both text layers and click **Align Horizontal Centers** (at the top of the Right Sidebar).
<img src="images/text-hero.png" style="width:50%;">

---

# The "Magic" Button (Auto Layout)

> **💡 The Canva vs. Figma Difference:** In Canva, a button is a rectangle with text on top. If you add text, you have to stretch the rectangle manually. In Figma, we use **Auto Layout** so the button grows automatically.

## 1. Type the Text First
1.  Press **T** and type **"View My Work"**.
2.  **Style:** Size 18, Bold, White.

## 2. Add Auto Layout
1.  With the text selected, press **Shift + A**.
    * *Notice a frame appears around your text. This is the button container.*
2.  **Add Background:** In the Right Sidebar, click **Fill** (+) and choose a color (e.g., #4A90E2 Blue or Dark Grey).
3.  **Add Padding:** In the Auto Layout section (Right Sidebar), set:
    * **Horizontal Padding (↔):** 32
    * **Vertical Padding (↕):** 16
4.  **Round Corners:** Go to the **Corner Radius** setting (top right) and type **8**.

## 3. Test the Magic
1.  Double-click the text inside your new button.
2.  Type *"Check out my amazing portfolio"*
3.  *Watch the button stretch automatically.*
4.  Change it back to **"View My Work"**.
<img src="images/button-demo.gif">

---

# Organization

1.  Select the **Headline**, **Sub-headline**, and **Button**.
2.  Press **Shift + A** (Auto Layout) to group them in a vertical column.
3.  Set the spacing between items to **40**.
4.  Center this group in the middle of your page.

<script>
    function toggle(input) {
        var x = document.getElementById(input);
        if (x.style.display === "none") {
            x.style.display = "block";
        } else {
            x.style.display = "none";
        }
    }
</script>

[NEXT STEP: Building the Portfolio Grid](portfolio-page.html)
