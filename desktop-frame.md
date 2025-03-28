---
layout: default
title: Working with Frames
nav_order: 3
parent: Workshop Activities
---

### Section Preview  

Before you begin, take a look at the **final result** you’ll be working towards in this section:  

<img src="images/desktop-frame-final.png" style="width:50%;">  

---

# Working with Frames  

If you and your group have any questions or get stuck as you work through this in-class exercise, please ask the instructor for assistance. Have fun!  

## 1. Creating a Desktop Frame  

In Figma, **Frames** act as containers for your designs and help structure your layout. Let’s start by adding a **Desktop Frame** to your canvas.  

1. In the **bottom toolbar**, click on the **Frame Tool** (Shortcut: Press **F**).  
<img src="images/frame-icon.png" style="width:100%;">  

2. On the **Right Sidebar**, a list of preset frame sizes will appear.  
3. Scroll down and click on the **Desktop** dropdown, then select the **Desktop** option to create a standard desktop-sized frame.  
<img src="images/desktop-frame-option.png" style="width:200px;"> 
4. Your new frame will appear on the canvas. Make sure it is selected before moving to the next step.  

    <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/desktop-frame.gif">
    </div>

5. With the frame selected, go to the **Layers Panel** on the left.  
6. Double-click on the frame name (default should be "Desktop - 1") and rename it to **"Home"** (see image on the right)
 
    <button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/layers.gif">
    </div>
## 2. Applying a Linear Gradient Background  

Now, let’s style the frame with a **linear gradient background**.  

1. In the **Layers Panel** (on the left sidebar), find and select the "Home" Frame to ensure it's active.  
2. In the **Right Sidebar**, locate the **Fill** section under **Design**.  
3. Click on the **color box** to open the color picker.  
4. In the color picker, click on the **square icon with dots within** to switch from a solid color to a gradient fill.
5. Two color stops will appear on the gradient bar: The color stops are the arrows on each end of the color bar. The left color stop is for the color at the top of the object (here, the Frame), and the right color stop is for the color at the bottom of your object. Each corresponds to a row beneath the color bar, titled Stops, ordered left to right. 
<img src="images/linear-gradient-fill.png" style="width:300px;">   
   - Click on the **first color stop** (top of the gradient) and enter the HEX code: **#5A452D**.  
   - Click on the **second color stop** (bottom of the gradient) and enter the HEX code: **#C4A484**. 

    <button onclick="toggle('gif3')">Show/Hide Animation</button>
    <div id="gif3">
    <img src="images/layer-2.gif">
    </div>
    
### Next Steps  
In the next step, we will **design the header** for our project, including adding a title, logo, and navigation elements.  

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

[NEXT STEP: Building the Header](building-header.html){: .btn .btn-blue }   
