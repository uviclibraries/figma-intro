---
layout: default
title: 6-Prototyping & Interactions
nav_order: 7
parent: Workshop Activities
---

### Section Preview

This is the moment your design becomes an **App**. We are going to "wire up" the buttons so they actually work. We will use a special feature called **Smart Animate** to make the navigation feel smooth and professional.

<img src="images/prototype-final.gif" style="width:60%;">

---

# Prototyping: Making it Clickable

> **💡 The Mode Switch:** So far, we have been in **Design Mode**. Now, look at the top of the Right Sidebar and click the **Prototype** tab. You will see your element outlines turn from Blue to **Purple**.

## 1. Connecting the "Home" Link
Let's make sure that when users are on the Portfolio page, they can get back Home.

1.  Go to your **Portfolio Frame**.
2.  Double-click to select the **"Home"** text inside your Header.
3.  **The Noodle:** You will see a small circle with a `+` sign appear on the edge of the text box. Click and drag that circle over to the **Home Frame**.
4.  **The Interaction Menu:** A menu will pop up. Configure it like this to make it look pro:
    * **On Click**
    * **Navigate to:** Home
    * **Animation:** Change "Instant" to **Smart Animate**.
    * **Ease In/Out:** 300ms (Default).

    > **Why Smart Animate?** Because you have a "Header" on both pages, Figma is smart enough to keep the header still while changing the page content. This prevents the screen from "flashing."

    <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/link-home.gif">
    </div>

## 2. Connecting the "Portfolio" Link
Now let's do the reverse.

1.  Go to your **Home Frame**.
2.  Select the **"Portfolio"** text in the Header.
3.  Drag the noodle connection to the **Portfolio Frame**.
4.  **Settings:** Ensure it is set to **Smart Animate**.

    <button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/link-portfolio.gif">
    </div>

## 3. Connecting the Hero Button
We built that "View My Work" button for a reason. Let's make it functional.

1.  On the **Home Frame**, select your **"View My Work"** button (the whole button, not just the text).
2.  Drag the noodle connection to the **Portfolio Frame**.
3.  **Settings:** Keep it on **Smart Animate**.

    <button onclick="toggle('gif3')">Show/Hide Animation</button>
    <div id="gif3">
    <img src="images/link-button.gif">
    </div>

## 4. The Grand Finale: Present Mode
This is what you came here for.

1.  Click the **Home Frame** (click the name "Home" in the top left corner of the frame) to tell Figma where to start.
2.  Look at the very top right of your screen. Click the **Play Icon** (▶) to "Present".
3.  A new tab will open with your live website.
4.  **Test it:**
    * Hover over your buttons (notice the cursor changes).
    * Click "Portfolio".
    * *Watch closely:* Did the header stay perfectly still while the content changed? That is the power of Smart Animate.

    <button onclick="toggle('gif4')">Show/Hide Animation</button>
    <div id="gif4">
    <img src="images/present-mode.gif">
    </div>

---

# Workshop Complete! 🚀

**You have successfully:**
1.  Built a layout using **Frames**.
2.  Created responsive navigation with **Auto Layout**.
3.  Built a reusable **Component System** for your projects.
4.  Created a live, interactive **Prototype**.

### Where to go from here?
You can now share this prototype link with anyone (even if they don't have Figma). Click the **"Share Prototype"** button in the presentation view.

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

[NEXT STEP: Designing the About Me Page](about-page.html){: .btn .btn-blue }  
