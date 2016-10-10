# Sketch Workshop
by Marcelo Paiva - UX-Dev Summit 2016

### Section: 1 - Introduction - 7 min

##### Lecture 1: Introduction - 01:02
- Official documentation
- design an app
- export
- download source files

##### Lecture 2: What is Sketch? - 02:23
- Vector Drawing Application intended for screen design
- Has a heavy biased towards user interface design
- Outputs pixel-based graphics, but it is not a pixel-based tool
- A vector-based tool with an infinite size canvas
- Create artboards for different screens;
- Pages for different workflows;
- Multiple fills for a single layer;
- Allow us to design different screens and states for a single application;
- Making it so easy to have every aspect of an application, conveniently in front of us, in a single document;
- Design screens indepentently from resolution;
- Export a single design for multiple devices and platforms;
- Vector-drawing application with Infinitely Scalable, Infinitely Precise;
- Strong API that allows community of designers and developer to create and share plugins that make will make you and your team very efficient and save you hundreds of hours;

##### Lecture 3: Vector vs Raster - 04:00
- raster graphics are made up of pixels
- vector graphics are made up of math
- squares are fine, circles and angled shapes suffer
- raster graphics has its use in photography
- bottom line is that if you will be editing, scaling, moving objects around, it's better to work with vector objects.

##### Lecture 4: Interface Tour - 01:24
- Sketch interface was designed to be streamlined and minimal.
- No floating panels;
- each document gets its own window
- all the tools are contained in each respective window
- **Toolbar** across the top
  - Secondary (right) click to customize
- **Layers List** holds all objects
  - At the bottom we have a **search filter - more later**
- **Inspector** is the most important part of the UI
	- It contains all the tools and properties that we need
	- If I select a vector, text or bitmap the inspector shows me the tool based on the selected object
- At last, we have a primary design surface, **The Canvas**

##### Lecture 5: The Anatomy of a Sketch Document - 03:04  

`Create a new document`

**The Canvas** - or Pages - is completely unconstrained, there's a tool to assist with creating boundaries for your design area, **but before...** Let's understand on the canvas for a moment:

- Let's hit `Ctrl+R` to show the **Rulers**
- The primary unit of measurement in Sketch is the `pixel`
- Starting at `0,0` negative pixels up and to the left

**How large is the canvas in Sketch?** > Answer: **Infinite**

- So as you design you dont have to worry about running out of space
- But you do need to worry about the size of the screen you are design for, which is why we have **Artboards**
- On the top left corner, you should see the `Insert` button;
- Select the **Artboard** tool or hit `letter A`
- On the right hand side, you'll find a list of popular screen sizes
- Let's select an `iPhone 6` artboard
- It's not uncommon to design all your screens in a single canvas with multiple artboards
- But sometime, you just want separate your screens by workflows or user stories
- `Pages` allow us to organize our screens design accordingly
- I can add as many pages I want
- I can drag or I can drop artboards from one page to another

##### Lecture 6: Save and Autosave - 03:05
- Autosave is a controversial feature
  - If I change something and close a document, Sketch doesn't ask me if I want to save the document, it simply saves it for me;
  - If I make a mistake, it autosave my mistakes
  - But the cool thing is that it saves my mistakes in different versions;
  - And we can access those via the `File` menu > `Revert to` then `Browser all versions...`
  - It brings up a miniture version of the Time Machine
  - You can browse your versions and even copy objects from it.
  - Sketch autosaves feature works per document.
- The **best practice** that I recommend is that you create your own versions, using `Save as...`
  - `File` menu then hold down the `Option` key to access the `Save as..` option.

### Section: 2 - Layer Basics - 20 min

##### Lecture 7: Types of Layers - 02:21
- Text, Image and Shape layers
- Group of objetcs (components) they a glued together
- Group Section for organizational purposes (can be selected)
- Check `Click-through when selecting`

##### Lecture 8: Interacting with Objects - 05:04
- `Bounding box` around any object
- bounding boxes have `handles` for scaling purposes
- by holding `shift` key you constrain the movement of the mouse
- by holding `command` key turns handles into `rotating` tool
- by holding `command + shift` constraints the angles by 15 degrees
- by holding `option` key scales `from center`
- by holding `option + selecting + dragging` **duplicates**

speaking of selecting...

- `select + shift` adds to selection
- alignment guides support manual placement
- `drag + shift` selects any object touched by the lasso
- `drag + option` selects only objects entirely inside the lasso area
- distributing > vertically / horizontally
- aligning > hor / ver / ctr / right / left
- `select + option` allows picking layer behind
- `select + shift` also deselect an object

##### Lecture 9: Easy Precision and Math - 04:42  

- select 3 objects
- `width` and `height` 1px at a time
- Keyboard `nudging shortcuts`
 - `Shift + arrow` nudges by 10px
 - it nudges the right and bottom edges only
- Math operations inside the inspector fields
- selecting and dragging the `inspector labels`   

##### Lecture 10: Guides and Grids -  03:23  
- `Ctrl + G` to show grid
- Grid Settings
- Smart guides
  - select and object
  - hold `option`
  - mouse over other object to see distance
- Ruler guides
- Remove guides

##### Lecture 11: Hiding, Locking, and Grouping Layers -  03:44
- Selecting overlaping shapes `select + option`
- hiding shapes`Shift + Cmd + H`
- locking shapes `Shift + Cmd + L`
- grouping shapes `Cmd + G`
- ungrouping shapes `Shift + Cmd + G`

### Section: 3 - Shapes

##### Lecture 12: Adding Shapes - 02:51
- **R - Rectangle** `shift` to constrain
- **O - Oval** `alt option` to build from center
- U - Rounded Rectangle - inspector `radius` property
- Star and Polygon - Radius and Points
- L - Line -
- Arrow

##### Lecture 13: Activity - Building the Outline - 09:56  
`Exercise to build an app screen`

##### Lecture 14: Editing Shapes - 04:44
Draw a rectangle shape and hit `Return` to get into editing mode

- `Straight` points - drag the selected point around
- `Mirrored` - symetric control handles to create **smooth** curves
- `Disconnected` - independent straight points
- `Asymetric` - independent curved points
- `Double click` to toggle between straight and mirrored points
- **Note - if you use straight points**, you'll get the bonus of the `Corners` slider
- Just below, you can select if you want the points to land on a `full pixel edge`
- Small `select points` button
- `Add a control point` by clicking on the path of a line

##### Lecture 15: Drawing Vector Shapes - 03:14
- V - `Vector` allows us to create custom paths and shapes
- `Click` to add straight lines
- `Click, Hold and Drag` to add mirrored points
- `Command` key will allow us to play with `Asymetric` control points
- `Close Path` by simply clicking on the origin point
- P - `Pencil` tool a a free-hand line drawer

##### Lecture 16: Activity - Drawing Vector Shapes - 00:25
`SKIP THIS LECTURE`
##### Lecture 17: Boolean Operations - 09:24
- `Union` - Football laces
- `Intersect` - Football
- `Subtract` - Moon
- `Difference` - DVD/TV - Deletes what's overlaping. Union doesn't work because of t=other boolean instructions in complex groups.
- `Flatten` - Rocket
  - `Intersect` rocket
  - `Subtract` tail
  - `Union` rocket+tail
  - **Houston, we have a problem**
  - Because the top circle is masking
  - Instead, we want to `flatten` both
  - Then `Unite` them
  - `Subtract` the tip - and voilá!

##### Lecture 18: Masking - 07:31  
- **Outline Mask**
  - Oval shape on the bottom
  - Select two layers
  - Mask with selected shape
  - Creates a group containing bitmap and shape
  - shape is renamed `mask`
  - Draw rectangle `inside` the group
  - Select `ignore the underlying mask`
  - Rectangle shows inside the masked group
- **Alpha Mask**
  - The `gradient opacity` dictactes the mask
  - We will talk about `Gradients` in the next session
  - Copy masked group
  - We can use a gradient to be `fade out`
  - Select the `mask` shape
  - Then go to `Layer > Mask Mode > Alpha Mask`
  - Select `Fill`, then `Gradient`

##### Lecture 19: Resizing vs Scaling - 04:21
- `Borders` and `Shadows` need special attention when designing shapes
- Sketch treats `borders and shadows` differently if an layer is `resized` or `scaled`
  - resize circle to `250px`
  - scale circle to `250px`
- Sometime, resizing and keeping the border-witdh intact makes sense - i.e. `button`
- If you are designing `line icons`, I'd recommend using `boolean` shapes
- Often times, we use UI kits that need to be resized for whatever reason
- See iPhone 5 keyboard

##### Lecture 20: Make Grid - 03:37
- The `Make Grid` tool under the `Arrange` menu is very helpful for a number of repetitive situations.

##### Lecture 21: Importing from Adobe Illustrator - 02:29  
`Skip Lecture?`
- Copying and pasting works fine
- However, there are some imcompatibility with the way objects are handled
- AI handles gradients fill and stroke the Adobe way
- AI gradients are not compatible with SVG standards
- Text outlines need to be `united` after pasting
- Sketch follows strict Web / SVG standards

### Section: 4 - Styling

##### Lecture 22: Fills - 08:44  
- Color picker `Control + C`
- `saturation` is vertical, `brightness` is horizontal
- top slider is `hue`
- on the bottom you have the `alpha` slider to control transparence
- Click on `HSB` or `RGB` to toggle color modes
- Global Color palette - Corporate colors, Material, Bootstrap, etc
- Document Palette - create palettes specific to the document
- click the `+` sign to add a color to your palettes
- There's a **plugins** that allows us to load and export palettes
- OS X Dock Commands
  - Hide Dock `option + command + D`
  - Slide Separator to resize Dock
- `Linear Gradient`
- `Radial Gradient`
- `Angular Gradient`
- `Image Fill` - patter, texture, image
- `Noise Fill` - footbal green grass
- Thanks to SVG standards, Sketch has `Multiple Fills`
- Click the `+ sign` to add a fill
- Drag up and down to `arrange fills`
- Turn `on/off fills`
- To delete fill, simply drag the fill off the inspector panel

##### Lecture 23: Activity - Fills - 03:06
- `Skip` 

##### Lecture 24: Borders - 06:14
- Sketch can apply borders on masks
- Gradient on borders
- Position (center, inside, outside)
- `cog` icon gives you access to end-point and gap options

##### Lecture 25: Blending Modes and Opacity - 03:35
- Blend modes don't
 export, so becareful on how you choose to use and export your assets
- I personally use blending modes only to give a bitmap some effect

##### Lecture 26: The Magic of Shadows - 03:23
- Multiple shadows
- Inner Shadow
- Gausian Blur
-
-
##### Lecture 27: Activity - Adding the Icons - 07:30  
`Skip`

##### Lecture 28: Blurs - 06:21
-
-
##### Lecture 29: Borrowing Style - 01:49
- `Option + Command + C` to copy style
- `Option + Command + V` to paste style

##### Lecture 30: Shared Styles - 02:41
- DRY - Don't Repeat Yourself! Create Shared Styles.

##### Lecture 31: Finishing Touches - 08:59
- `Skip this`

### Section: 5 - Text
This is pretty straight forward.

##### Lecture 32: Basics of Text Editing - 07:15
- Typeface vs Font-family
- `shift + enter` for line break

##### Lecture 33: Area Text and Styling - 12:20  
- No Shared Character Styles

##### Lecture 34: Text on a Path and Outlines - 02:24


### Section: 6 - Images

- ##### Lecture 35: Image Adjustments - 01:15
- ##### Lecture 36: 9-Slice Images - 02:50  

### Section: 7 - Symbols

- ##### Lecture 37: Symbols - 06:08  

### Section: 8 - Workflow Pro Tips

- ##### Lecture 38: Pixel Preview - 03:16
- ##### Lecture 39: Presentation Mode - 00:45
- ##### Lecture 40: Managing Tons of Layers - 07:51

### Section: 9 - Exporting

- ##### Lecture 41: Exporting Artboards - 07:54
- ##### Lecture 42: Exporting Layers and Slices - 11:31

### Lecture 43: Plugins
- Color Palettes
- Data
- [Long Shadow](https://github.com/JayHoltslander/Sketch-Make-Long-Shadow)

