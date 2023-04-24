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

| Command | Hot Key   |note|
| ------- |-----      |---|
| **Move Camera Back** |    |
| 6. Select Camera Frame |    | Notice in right hand view, camera turns orange |
| 7. Activate Grab Tool | G |
| 8. Enter Smooth Zoom Mode  | Depress MMB | In perspective view, we hold Ctrl + MMB to smooth Zoom |

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
| 9. Activate Grab Tool | G | With frame selected |
|10. Move Camera | LMB |    |
|11. Engage Smooth Zoom | G + MMB | We add a smooth zoom at the end |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/gzk0t3d25l4f7d1/02-Ec_Camera-G-Drag-to-Move.mp4?raw=1'>
</video>

---

| Command | Hot Key     | note |
| ------- | ------------|-----|
| 12. Render Camera View | F12 |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/9t42wevpkevzqt7/02-Ed_Render-Camera-View.mp4?raw=1'>
</video>

---

### Subdivision

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

## Part 04

### Snapping

|**Snapping**| | |
|------------|---|---|
| Incremental (temporary) | Ctrl | | 
| Toggle Snapping | Shift + Tab | ![Snapping Menu](Images/Donut_Tutorial_Part_04/04-B_Snap-Menu.jpg) |

<style>
  video {
    width: 100%;
  }
</style>
 
<video controls>
<source src='https://www.dropbox.com/s/kmc9unpb7nh8r50/04_A-Snap-Projected.mp4?raw=1'>
</video>

Snapping allows us to move a vertex along the face of the surface below.  




