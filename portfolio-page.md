---
layout: default
title: Portfolio Page - Setting Up the Structure
nav_order: 6
parent: Workshop Activities
---

### Section Preview  

Before you begin, take a look at the **final result** you’ll be working towards in this section:  

<img src="images/portfolio-final.jpg" style="width:50%;" alt="Final Portfolio Page Design">  

---

# Setting Up the Portfolio Page  

The **Portfolio Page** showcases featured projects in a clean and structured layout. To begin, we will duplicate the **Home Page** frame and modify it to fit the portfolio content.  

## Create the Portfolio Page Frame
1. In the layers panel, select the **Home** frame and duplicate it using Command + D on Mac or Control + D on Windows.
2. Clear all its content asides from the Header
3. Double-click on the frame name (default should be "Desktop - 1") and rename it to **"Portfolio"** 
4. On the **Right Sidebar**, increase the height of the frame to 1520 to allow more content to fit onto the Portfolio frame.<br>
<img src="images/incr-height.png" style="width:50%;">  

## Adding a Divider Line  

To separate the navigation from the portfolio content, we will add a **thin white line** below the header.  

1. Select the **Portfolio Frame**.  
2. Press **L** to activate the **Line Tool**, or click the **Line** icon from the bottom toolbar.  
3. Click and **drag** to draw a horizontal line under the header.  
4. In the **Right Sidebar**, adjust the line properties:  
   - **Color:** White (#FFFFFF)  
   - **Stroke Weight:** 1px  
   - **Length:** Stretch it from the **left edge of "Home"** to the **right edge of "Contact Me"**.  

   <button onclick="toggle('gif1')">Show/Hide Animation</button>
    <div id="gif1">
    <img src="images/line-portfolio.gif">
    </div>

## Grouping the Header and Divider  

To keep the header and the new divider aligned properly, we will apply **Auto Layout**.  

1. Select both the **Header Group** and the **White Line** in the **Layers Panel**.  
2. **Right-click** and choose **Add Auto Layout** from the menu.  
3. In the **Right Sidebar**, under **Auto Layout Settings**, set the **Vertical Spacing** to **21**.  

 <button onclick="toggle('gif2')">Show/Hide Animation</button>
    <div id="gif2">
    <img src="images/head-div.gif">
    </div>

## Adding the "My Portfolio" Title  

Now, we will add a **title** to introduce the portfolio section.  

1. Ensure the **Portfolio Frame** is selected in the **Layers Panel**.  
2. Press **T** to activate the **Text Tool**, or click the **Text** icon in the bottom toolbar.  
3. Click inside the **Portfolio Frame** and type: "My Portfolio"  
4. In the **Right Sidebar**, set the typography properties:  
- **Font Family:** Noto Serif JP  
- **Font Size:** 48  
- **Font Weight:** Roman
- **Text Color:** White (#FFFFFF)  
- **Text Alignment:** Center  
5. Position the title **below the divider**, ensuring it is centered using the **alignment guides**.  
<img src="images/portfolio-title.png" style="width:50%;">  

## Creating a Single Project Card  

In our design, a **Project Card** consists of an image, a title, and a short description.  

### Creating the Card Structure  

1. Press **R** to activate the **Rectangle Tool**, or click the **Rectangle** icon in the bottom toolbar.  
2. Click and **drag** to create a rectangle that will serve as the **image container**.  
3. In the **Right Sidebar**, set the image dimensions to:  
- **Width:** 519  
- **Height:** 338  
4. In the **Fill** section of the right sidebar, click the **color box**, then select the **Image** icon and upload the image that is titled "people-fashion-show".  
<img src="images/rect-image.png" style="width:100%;">  
5. Press **T** to add a text layer below the image and type a **project title**, such as: "Paris Fashion Week"
6. Adjust the text properties:  
- **Font Family:** Noto Serif JP 
- **Font Size:** 20  
- **Font Weight:** Roman  
- **Text Color:** White (#FFFFFF) 
- **Text Case:** Uppercase  
  
7. Add another text layer below for the **project description**, keeping it to **two lines max**: 
  ```
Styled a statement runway show featuring bold silhouettes and intricate textures, celebrating modern couture in the heart of Paris.
  ```
8. In the **Layers Panel**, select the **image, title, and description**, and use the shortcut **Shift + A** to create an **Auto Layout**. 
9. Adjust the vertical spacing between elements to 16

10. In the layers panel, select the auto layout we just created and add a bottom border by heading over to the right sidebar to configure the following settings:
<img src="images/bottom-border.png" style="width:300px;">  

## Duplicating and Replacing Content  

Now, let's create another project card by duplicating the current one and replacing the content.  

1. In the layers panel, select the auto layout that we recently created.  
2. **Right-click** and select **Duplicate**.  
3. Replace the **image, title, and description** with the following:  
- **Title:** Styling Celebrities, Fall 2024
- **Image:** the image titled "hanging-brown-clothes"
- **Description:**  
  ```
  Curating chic and cozy looks for A-list clients for simple everyday outings in the Fall.
  ```  

Ensure that all project descriptions fit into **two lines max** for consistency.  


## Adding a Quote  

Now, let’s add a fashion-related quote after the second project card.

1. Press **T** to create a new text layer.  
2. Type the following quote:  
  ```
“Style is a way to say who you are without having to speak.” – Rachel Zoe
  ```

3. In the **Right Sidebar**, set the typography properties:  
- **Font Family:** Noto Serif SP
- **Font Size:** 16  
- **Font Weight:** Roman  
- **Text Color:** White (#FFFFFF)  
- **Text Alignment:** Left  
4. Adjust the width of the text layer to 214 so that it fits into about three lines
5. Position the quote **to the right of the project cards**.  
<img src="images/right-quote.png" style="width:60%;">  


## Creating a Horizontal Auto Layout  

Now, we will **group the two project cards and the quote** into a horizontal Auto Layout.  

1. Select the **two project cards and the quote**.  
2. **Right-click** and choose **Add Auto Layout**.  
3. In the **Right Sidebar**, set the **direction to horizontal** and adjust the **spacing** to 30


## Duplicating the Horizontal Auto Layout  

Now, let’s create the second row of projects by duplicating the first horizontal Auto Layout and placing it below.  

1. Select the **Horizontal Auto Layout** in the **Layers Panel**.  
2. **Right-click** and choose **Duplicate**.  
3. Drag the new Auto Layout **below the first one**.  
4. **Rearrange the quote** so that it is placed **first** in this row. You can do this easily by selecting the text layer and hitting the left arrow key on your keyboard.
5. Replace the quote in this new Auto Layout with:
 ```
“Fashion is the armor to survive the reality of everyday life.” – Bill Cunningham
  ```
6. Replace the **images, titles, and descriptions** with the remaining content:
<br/>
- **Title:** Bridal Elegance at Mumbai 
- **Image:** the image titled "standing-lady-fashion-show"
- **Description:**  
  ```
  Designed a regal bridal look blending delicate embroidery and contemporary tailoring for a runway showcase in India.
  ```  
  
<br/>

- **Title:** Vogue Italia
- **Image:** the image titled "woman-in-black-and-white"
- **Description:**  
  ```
  Created a striking high-fashion editorial look, playing with curls, contrast, and avant-garde styling for a bold magazine spread.
  ```  

Ensure that each project description is **no longer than two lines** for a clean look.  

<img src="images/left-quote.png" style="width:100%;">  

## Creating the Footer  

To complete the **Portfolio Page**, we will add a simple footer with a copyright notice and a horizontal line for separation.  

### Copying the Header Line  

1. Select the **Portfolio Frame**.  
2. Press **L** to activate the **Line Tool**, or click the **Line** icon from the bottom toolbar.  
3. Near the bottom of the frame, click and **drag** to draw a horizontal line. Ensure that the line **stretches across the same width** as the one in the header.
4. In the **Right Sidebar**, adjust the line properties:  
   - **Color:** White (#FFFFFF)  
   - **Stroke Weight:** 1px  

### Adding the Copyright Text  

1. Press **T** to activate the **Text Tool**, or click the **Text** icon in the bottom toolbar.  
2. Click below the newly placed line and type:  
```
 © Copyright <insert current year> - Evelyne Stark
```

3. In the **Right Sidebar**, set the typography properties:  
- **Font Family:** Noto Serif SP 
- **Font Size:** 16  
- **Font Weight:** Roman  
- **Text Color:** White (#FFFFFF)  
- **Text Alignment:** Center  
<img src="images/copyright.png" style="width:100%;">  
---

Now that the **footer is complete**, the Portfolio Page is fully designed! The next step is **adding an animation** to link the **Portfolio navigation link** and the **"My Portfolio" button** on the Home Page to the Portfolio Page

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

[NEXT STEP: Adding Page Transition Animations](linking-across-pages.html){: .btn .btn-blue }  
