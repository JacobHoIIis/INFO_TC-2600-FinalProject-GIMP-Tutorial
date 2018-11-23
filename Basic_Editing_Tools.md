# GIMP Tutorial - Part 2
## Basic Editing Tools
---
#### Table of contents:   
-[Layout and Tool Windows](#layout-and-tool-windows)   
-[Creating/choosing a file](#creating-choosing-a-file-to-edit)    
-[Painting, Pencil, and Text Tools](#painting-pencil-and-text-tools)    
-[Selection Tools](#selection-tools)     
-[Move and Scaling Tools](#move-and-scaling-tools)       
-[Blur and Smudge Tools](#blur-and-smudge-tools)    
-[Saving and Exporting a File](#saving-and-exporting-a-file)    

---

#### Layout and Tool Windows

In GIMP, there are three main windows/toolbars you will use.

The far left window, the ***Toolbox***, contains the main editing tools and their options.
![editing pic 1](/Pictures/editing_1.png " ")   

The middle window contains 1. the editing canvas,   
![editing pic 2](/Pictures/editing_2.png " ")

and 2. the main navbar.   
![editing pic 3](/Pictures/editing_3.png " ")

The right window, ***Layers and Brushes***, contains image layers (beyond the scope of this tutorial, but important for advanced editing) in the upper half, and various types of brushes used for the Paintbrush and Pencil tools (discussed later in this tutorial) in the lower half.
![editing pic 4](/Pictures/editing_4.png " ")

---

#### Creating/Choosing a File to Edit   

With GIMP, you can create a new image file or edit an existing image.   

*To edit an existing file:*
1. Go to the navbar.
2. Select **File -> Open**
3. From here, you can navigate to the image you want to edit.
4. Select **Open**
5. Now the file is ready to be edited   

*To create a new file:*

1. Go to the navbar
2. Select **File -> New**
3. From here, you will get this window:   
![editing pic 5](/Pictures/editing_5.PNG " ")
4. Choose the image width and height. **Templates** will also give you preset sizes for quick creation.
  * **Advanced Options** will give you more extensive options, but is beyond the scope of this tutorial.
5. Once the size is set, select **Ok**.   

At this point you should see a blank white image on the canvas. We can now begin editing.

---

#### Painting, Pencil, and Text Tools

1. Paintbrush ![paintbrush](/Pictures/paintbrush.PNG " ")      
 The paintbrush tool can be used like just like name implies.     
It will "paint" a stroke with blurred edges.   
![editing pic 6](/Pictures/editing_6.PNG " ")   

2. Pencil  ![pencil](/Pictures/pencil.PNG " ")   
 The pencil tool works the same way as the paintbrush tool.   
   However, it will "draw" a stroke *without* blurred edges.   
   ![editing pic 7](/Pictures/editing_7.PNG " ")   

3. Text Tool   ![texttool](/Pictures/texttool.PNG " ")   
The text tool will allow you to type text anywhere on the canvas.   
The color, text size, font type, and other style options can be changed in the **Toolbox** on the left under **Tool Options**.   
![editing pic 8](/Pictures/editing_8.PNG " ")   

---

#### Selection Tools   

There are multiple selection tools that can be used for certain scenarios.    


1. Rectangle Select Tool  ![rectangleselect](/Pictures/rectselect.PNG " ")   
Selects a rectangular area.   
![editing pic 10](/Pictures/editing_10.PNG " ")    

2. Ellipse Select Tool ![ellipseselect](/Pictures/ellipseselect.PNG " ")     
Selects a circular/oval area.    
![editing pic 11](/Pictures/editing_11.PNG " ")   

3. Free Select Tool  ![freeselect](/Pictures/freeselect.PNG " ")    
This tool can select in any shape you want it to select.    
![editing pic 12](/Pictures/editing_12.PNG " ")   

4. Fuzzy Select Tool   ![fuzzyselect](/Pictures/fuzzyselect.PNG " ")  
Selects an area based off of color. Click a part of your image with a certain color, and it will select the surrounding area *as long as it is the same color*. For example, in the following picture we selected a black part of the image, and it selected any part that was black.   
![editing pic 13](/Pictures/editing_13.PNG " ")   

There are other select tools to choose from; however the ones above are the most commonly used and will suffice for most basic editing purposes.

**Copying and Pasting:** To copy/paste selections, use the key combination *Command(for Mac users) or Control(for Windows users) + C* to copy a selection.    
To paste it's a little more complicated. Use *Command/Control+V* to paste a selection. Once you've pasted the selection, will need to anchor it to the current layer. Navigate to the layers window on the right, and select the anchor icon on the bottom.   
![editing pic 9](/Pictures/editing_9.png " ")   

**Deleting:** To delete what you have selected, the easiest way is to use the key combination *Control+X*.

---

#### Move and Scaling Tools

1. Move Tool ![movetool](/Pictures/movetool.PNG " ")   
By clicking and holding, the tool will move a selection anywhere on the canvas.   

2. Transform Tools   
 * Rotate Tool ![rotatetool](/Pictures/rotatetool.PNG " ")   
 Rotates a selection by increments or by manual rotation.

 * Scale Tool ![scaletool](/Pictures/scaletool.PNG " ")   
 Resizes a selection by a certain amount.

 * Flip Tool ![fliptool](/Pictures/fliptool.PNG " ")   
 Flips a selection either vertically or horizontally.


---


#### Blur and Smudge Tools

1. Blur/Sharpen Tool ![blurtool](/Pictures/blurtool.PNG " ")    
This tool can blur the edges of sharp parts of images. Likewise, the sharpen tool can do the opposite, although with less impact. The amount of blur or sharpness applied can be changed by adjusting the **Rate** at the bottom of the **Tool Options** window.   
![editing pic 14](/Pictures/editing_14.PNG " ")   

2. Smudge Tool ![smudgetool](/Pictures/smudgetool.PNG " ")   
Similar to the blur tool, the smudge tool can also be used to blur edges. Additionally, it can also be used to "blend" or mix colors, extending it's usefulness beyond blurring.   
![editing pic 15](/Pictures/editing_15.PNG " ")   

---

#### Saving and Exporting a File   

***Saving***   

Initially, you will need to save your file with a name, so that it can be editable later on.   
To do so, navigate on the navbar to **File -> Save**.
Here, you can choose a name and location to save your file.    
![editing pic 16](/Pictures/editing_16.PNG " ")    
Upon selecting **Save**, the image will save as an **.xcf** file, which is GIMP file extension for editable files.   

After you have saved your image initially, you can save your changes periodically either by choosing **File -> Save** or by the key combination *Command/Control+S*. Saving your image file should be done as often as possible. This will prevent the loss of changes to your image should something happen between saves.   

***Exporting***   
You can export your finished images after you are done editing. Unlike **.xcf** files which are only viewable in GIMP, exporting to an image format will allow other users to view your image without GIMP.   

To do so, navigate to **File -> Export As...**   
Here, you can choose a name for your finished image.   
![editing pic 17](/Pictures/editing_17.png " ")   

After you have chosen a name, you can choose a file extension for your image.    
![editing pic 18](/Pictures/editing_18.png " ")  
The most commonly used extensions for viewable images are JPEG and PNG, and for the purposes of this tutorial either will suffice.

When you have both the name and extension set, go ahead and select **Export**.   

You now have a finished image, edited in GIMP. You can always go back and edit the *.xcf* file, and export again if you make changes.


---

#### Where to go from here...

This tutorial briefly covered very basic elements of GIMP. If you want to expand beyond the scope of this tutorial, below are some other great tutorials/how-to's that helped me back when I started with GIMP, and will hopefully help you.

1. [Color and Brightness in GIMP](https://howtogimp.com/fix-brightness-and-color-in-gimp)
2. [Layers in GIMP](https://google.com/amp/s/opensourceforu.com/2009/08/gimp-for-beginners-part-2-understanding-layers/amp/)
3. [Filters/Effects in GIMP](https://quackit.com/web_graphics/gimp/tutorial/gimp_filters.cfm)    

Additionally, while the above tutorials are great for mastering concepts, the GIMP website also has tutorials that tend to be more up-to-date visually.
You can find them [here](https://gimp.org/tutorials).   

Try all the tools, mess with the colors, and don't be afraid to try a filter or two.   
Because, after all, the best way to learn is to experiment.   
Happy editing!


---
