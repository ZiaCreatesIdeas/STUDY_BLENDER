# Donut Tutorial

## Part 01

[Navigation and Hotkeys](Hotkeys.md)

**Object Mode, Edit Mode**  
Blender has two different modes to work in.  
Each mode has restrictions on what commands can be delivered.   
ie. 'X' to delete, works different in Object Mode vs. Edit Mode. 
Edit mode is only available when an object is selected.  

#### Change Resolution Scale of Interface.
* Edit > Preferences > Interface > Resolution Scale.

![Scale Resolution](Images/Donut_Tutorial_Part_01/Edit-Preferences-Interface-ScaleResolution.jpg)

---

#### Change Material Colors

Material color changes are not interactive and only show when rendered (F12).

% https://www.dropbox.com/s/d0tgmotsvrxbr4y/01_B-ChangeMaterialColors.mp4?raw=1

<style>
  video {
    width: 100%;
  }
</style>

<video controls>
  <source src="https://www.dropbox.com/s/d0tgmotsvrxbr4y/01_B-ChangeMaterialColors.mp4?raw=1" type="video/mp4">
</video>

---

```{note} **Collections** are the equivalent to Folders.
:class: warning

```  

% PART TWO--------------------------------------

## Part 02

**Object Editing**

| Command |  Hotkey      | 
| ------- | -----------   | 
|Add                 | Shift + A|
| Recall 'Operator Presets'| F9 | 

<style>
   video {
    width: 100%;
  }
</style>

<video controls>
<source src='https://www.dropbox.com/s/uqgtstm8ht4axa5/02_A-CreateTorus.mp4?raw=1'>
</video>

![Operator Presets](Images/Donut_Tutorial_Part_02/02-B_Menu-Operator-Presets.jpg "Operator Presets")

```{note}
:class: warning
- Having an even number seams can help when unwrapping for UV's or performing slices.  
- Odd may be helpful when trying to define the middle of an object.
```  

<style>
  video {
    width: 100%;
  }
</style>
 
 Here we learn to 'Apply Scale'.

| Command |  Hot Key   |
| ------- | -----------|
| Apply Scale | Ctrl + A  |
|Open Item Panel | N |

<video controls>
<source src='https://www.dropbox.com/s/8ky3l3e0t0lf6mp/02_B-Apply-Scale.mp4?raw=1'>
</video>

Here we scale the donut down from 3m to ~ 9 cm. 
The scale should always be near to 1, 1, 1. 

![Apply Scale](Images/Donut_Tutorial_Part_02/02-C_Menu-Apply-Scale.jpg)

[Blender Guru: Tutorial 02, Apply Scale](https://youtu.be/imdYIdv8F4w?t=454)

We can change the shading of our object by **Selecting** the object and right clicking over the background.  
"Smooth shade is an illusion. It does not add any geometry."

 | Mouse |  Smooth Shade      |
 | ------- | -----------   | 
 |**RMB over background** |![Flat Shade](Images/Donut_Tutorial_Part_02/02-D_RMB-Object-Context-Menu.jpg) |


### Camera Lessons

| Command | Hot Key   |note|
| ------- |-----      |---|
|1. Look Thru Camera| Numpad - 0   | toggles between camera and perspective view |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/537qup8eaq9e2t7/02-E_Camera-Look-Through.mp4?raw=1'>
</video>

---

| Command | Hot Key     | note |
| ------- | ---------- |----  |
| 3. Select Donut| |
| 4. Frame Selection | Press Numpad - Period ' . ' |
| 5. Move Camera to Perspective View  | Ctrl + Alt + Numpad - 0 | _**Extremely Useful Hot Key**_ |


<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/cs84e7iomn36d1c/02-Eb_Camera-Ctrl-Alt-Num-0.mp4?raw=1'>
</video>

The camera snaps to the donut's position. 

---
**Simple Way to Frame a Shot**

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Side Menu  | N |
| View | Select |
| Activate 'Camera to View'  | Blue Checkbox |
| Set Desired Camera Frame | Pan, Rotate, Zoom |
| Deselect 'Camera to View' | | Or we can leave on and press Numpad '0' to exit |

![Camera to View](./Images/Donut_Tutorial_Part_04/04-C3_Camera_to_View_ShortVersion.gif)

---

**Complex Way to Frame a Shot**
| Command | Hot Key   |note|
| ------- |-----      |---|
| **Move Camera Frame** |    |
| 1. Select Camera Frame |    | Notice in right hand view, camera turns orange |
| 2. Activate Grab Tool | G |
| 3. Enter Smooth Zoom Mode  | Depress MMB | In perspective view, we hold Ctrl + MMB to smooth Zoom |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/kach3hb5jypsj2i/02-Eb-ii_Camera-G-MMB-Drag-to-Zoom.mp4?raw=1'>
</video>

---

| Command | Hot Key     | note |
| ------- | ---------- |----|
| 4. Activate Grab Tool | G | With frame selected |
|5. Move Camera | LMB |    |
|6. Engage Smooth Zoom | G + MMB | We add a smooth zoom at the end |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/gzk0t3d25l4f7d1/02-Ec_Camera-G-Drag-to-Move.mp4?raw=1'>
</video>

| Command | Hot Key     | note |
| ------- | ------------|-----|
| 7. Render Camera View | F12 | Check view by rendering |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/9t42wevpkevzqt7/02-Ed_Render-Camera-View.mp4?raw=1'>
</video>

---

<div class="subd">

### Subdivision
Also known as "subd's, subds, subsurf, subsurfaces". 
- Subdivisions are a way to smooth our models while still maintaining control over their base wire frame / cage.  
- Subdivisions are typically added in object mode, but we can select the option to view the results in Edit mode.  
- We can toggle the visibility of the Subd's for the viewport and the render.

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/57d6ugx6nsab8pj/02-F_Subdivision-Catmull.mp4?raw=1'>
</video>

---
| Hot Key | Pie Menu |
| ------ | -------- |
| <td style="text-align: center">Select **Mode** </td> | | 
|  Ctrl + Tab |  ![Select Mode](Images/Donut_Tutorial_Part_02/02-G_Pie-Menu_Select-Mode.jpg)   |   

---

### Proportional Editing

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Proportional Grab | Select ( Vertice, Edge, Face ) + O + G + Scroll MMB Up | Activate 'O' Before 'G' |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/o9hojjowi7o20hx/Hot_Key_O-Proportional-Edit.mp4?raw=1'>
</video> 

---

### Scale Along Normals

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Move Along Normals | Alt + S |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/7s8pohvu2id511u/Hot-Key_Alt-S-Scale-Along-Normals.mp4?raw=1'>
</video>

---

% PART 03 ---------------------

## Part 03

Create a Layer for Icing.

### Separate by Selection

| Command |  Hot Key    | note |
| ------- | -----|--|
| Wireframe | Alt + Z | | Select backfacing vertices |
| Duplicate | Shift + D| 'esc' to drop selection back in place |
| Separate | P [Selection] | A Separate Layer Occurs |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/62n03gmfmbmhio2/03-A_Duplicate-Separate-P.mp4?raw=1'>
</video>

---

### Modifier: Solidify

Apply a the Solidify modifier from Object Mode.
<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/8xm1k24nw41gxhf/03-B_Modfier-Soldify.mp4?raw=1'>
</video>

Smooth Offset with Shift + Drag

---

The order of modifiers matters.

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/5jugt3ondosrxto/03-C_Modifier-Order-Matters.mp4?raw=1'>
</video>

---

### Apply Subdivision

```{admonition} Warning
:class: warning

Applying subdivision's is destruction and cannot be undone.  
- Save Unmodified Blender Project.
- Duplicate Objects into Separate Layer before applying Subdivisions.

```
**Perpare by Duplicating Object and Saving File > As Copy**

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Select Object | | Object Mode |
| Duplicate Object | Shift + D | The object (prim) will appear temporarily large. |
| Drop Selection | RMB | 
| Save Project | File > Save As Copy |  |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/jjh84minlo5h1uy/04-F2_Save-Project-Duplicate-Prim.mp4?raw=1'>
</video>
<p></p>


We apply our Subdivision with a level of 1. 

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Move Subdivision Modifier to Top |  |
| Apply Modifier | Ctrl + A while hovering over Modifier | Only Object Mode |
|       | Select Drop Down Arrow | Only Object Mode |
<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/rxyur403uv45u6j/03-D_Apply-Subdivision.mp4?raw=1'>
</video>

- What is applied is what was in the viewport, not the render level.
<p></p>

---


## Part 04

### Snapping

Snapping allows us to move a vertex along the face of the surface below. 

|**Snapping**| Hot Keys | |
|------------|---|---|
| Incremental (temporary) | Ctrl | | 
| Toggle Snapping |  Shift + Tab | |
| | | Button to the Right of 'Snap'  |
|  | | ![Snapping Menu](Images/Donut_Tutorial_Part_04/04-B_Snap-Menu.jpg) |


- ( Project Individual Elements ) allows nearby vertices to also conform to the surface below.  
This acts like a radius falloff. Very important to activate.

|**Snapping**| Hot Keys | |
|------------|---|---|
| Over Background | RMB |![RMB Snapping Menue](Images/Donut_Tutorial_Part_04/04-B2_Snap_Menu_RMB.jpg)|

<p></p>

**Deformation with Snapping Activated**  
Deform the Icing to adhere to the faces of the donut.
<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/kmc9unpb7nh8r50/04-A_Snap-Projected.mp4?raw=1'>
</video>

<p></p>

When wire frames do not appear as expected, when can go to Edit mode, toggle keys [ 1, 2, 3 ]  
We can also toggle the ( Display Modifier in Edit Mode ) button.

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/5bxq8bdhhvza3rl/04-E2_Wireframe-Toggle.mp4?raw=1'>
</video>
<p></p>

---

```{admonition} Select through MESH error
:class: warning

When selecting a vertex, it is possible to select points on the backside.  
Shift + Z for X-Ray, or Z + Swipe Left to see that no other points are selected.
```  

[ Select Through Bug in Blender ](https://youtu.be/R1isb0x4zYw?list=PLjEaoINr3zgFX8ZsChQVQsuDSjEqdWMAD&t=557)

---

### Fixing Mesh Occlusion

The mesh for the icing will be occluded by the base.  
So we pull the mesh forward by activating Snap, Proportional Editing and pressing 'G'   
then drop the selection.
<p></p>

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Activate Snapping | Ctrl + TAB |
| Activate Proportional Falloff | O | |
| Move | G |
| Drop Selection | [Esc, LMB ] | Drop Selection without moving vertexes. |
| Repeat Where Needed |||

<p></p>

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/u7jtarq084wuysd/04-E3_Bring-Mesh-Through.mp4?raw=1'>
</video>
<p></p>

[Donut Tutorial: Pull Mesh Forward ](https://youtu.be/R1isb0x4zYw?list=PLjEaoINr3zgFX8ZsChQVQsuDSjEqdWMAD&t=512)

---

### Camera Repositioning

Here we re-position the camera for a render. 

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/oqb2ef4v49aio4j/04-C_Camera-Movement-Practice.mp4?raw=1'>
</video>

<style>
  video {
    width: 100%;
  }
</style>
The method above involves using 'G' to manipulate the camera.  
<p></p>
Instead, we can easily manipulate the camera from the viewport.
<p></p> 

 **Simple Way to Frame a Shot**

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Side Menu  | N |
| Select | View |
| Checkbox   | Activate 'Camera to View' |
| Choose the Camera Frame | Pan, Rotate, Zoom | Normal navigation |
| Deselect 'Camera to View' | | Or leave on and press Numpad '0' to exit |

![Camera to View](./Images/Donut_Tutorial_Part_04/04-C3_Camera_to_View_ShortVersion.gif)

**Cons**: Typically we can leave the camera view by pressing the MMB to escape, now we need to press 'Num pad 0' or uncheck 'Camera to View'.

### Render Visibility

<div class="admonition note" name="html-admonition" style="background: lightyellow; padding: 10px">
<p class="title"> </p>
We observe that we are accidently rendering the original cube placed our scene and not our current view. 
</div>

<video controls>
<source src='https://www.dropbox.com/s/0p6gxxu5n28abil/04-D_Render-Not-Visibility-Dependent.mp4?raw=1'>
</video>
<p></p>

```{note} 
:class: warning
A layer can be invisible in the viewport but will still appear in the render.
```    
---

### References

:::{card}

"_I want to get a T-Shirt that says, 'Reference, Reference, References'.. It is my biggest piece of advice for artists whenever they ask for feedback._" 
\- Blender Guru
:::

<style>
  video {
    width: 100%;
  }
</style>
 
 It is critical to switch to **Object** mode to enable the Add > Image > Reference option.

| Actions |  Hot Key    | 
| ------- | ------------|
| Switch to Object | [ Tab, Pie: Ctrl + Tab ] |
| Add Image to Current Viewport | Shift + A |
|  ![Add Image](Images/Donut_Tutorial_Part_04/04-E2_Object-Mode.jpg)  |  ![Add Image](Images/Donut_Tutorial_Part_04/04-D2_Add-Image.jpg) |


<video controls>
<source src='https://www.dropbox.com/s/tk4186vkm96qg85/04-E_Switch-to-Object-Mode-for-References.mp4?raw=1'>
</video>

<p>  </p>

Here we show three different ways of adding references.

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/hi75ve7i1l9g6dm/04-F_Add-References-3-Ways.mp4?raw=1'>
</video>
 
<p></p>

- | **Add > Image > Background** | is best used when in Front, Top, or Right viewports.  
- The background image is only visible from the chosen viewport. 
- | **Add > Image > Reference** | projects an image onto a plane (card) from the current view. 
- Add [ Reference, Background ] are identical if performed from the perspective or camera views. 

---

### Apply Subdivisions

Here we add additional detail by applying the Subdivision surface.

```{admonition} Apply Subdivison Surface
:class: warning 

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/f4gpunxxhwhtdcc/04-G_Apply-Subdivision.mp4?raw=1'>
</video>
<center> Place Subdivision Modifier at top of Stack and Apply 
 
```

 - Moves Edges and Apply Second Sub Division Modifier.

![Apply Second Subdivision](./Images/Donut_Tutorial_Part_04/04-G2_Apply-Second-Subdivision.gif)

---

### Extrude Edges

Make drips by extruding.

  | Command | Hot Key     | note |
  | ------- | ------------|-----|
  |  Extrude |  E | Edit Mode |
<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/3e3xf8llqrwfj6z/04-H_Extrude.mp4?raw=1'>
</video>
<p></p>

### Select Edges

Shrink the middle of the donut.

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Select Edges | Alt + LMB | Edit Mode [ Vertices, Edges, Faces ] |
| Contract Edge | Alt + S | Scale Along Normals |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/1jw0zka24uhvjvm/04-I_Select-Edges.mp4?raw=1'>
</video>
<p></p>

### Shrink Wrap Modifier

This is a second way to match the icing to the Donut.

| Command | Hot Key     | note |
| ------- | ------------|-----|
| Shrink Wrap  | Modifier | Use Eye Dropper to Pick Target |
| Move Modifier to top of Stack | |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/g331i8pdh7j2h2b/04-J_Shrink-Wrap.mp4?raw=1'>
</video>
<p></p>

[Blender Tutorial Part 4: Shrinkwrap Modifier.](https://youtu.be/R1isb0x4zYw?t=920)

