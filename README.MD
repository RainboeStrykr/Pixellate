# Pixellate
A pixel art Creation Tool Built using HTML5 Canvas.  
It is a Progressive Web App (PWA) with offline compatibility.  
It is mobile-friendly and is very easy to use.  

![Pixellate](icons/logo.png)

## Overview
This App is available at https:pixellate.netlify.app

## Usage
You can choose Any Dimensions for your Canvas, *16 X 16* is the default dimension.  
Dimensions below *128 X 128* are preferable for smooth operation.
## Toolbar
### Pencil

The Pencil tool is the most basic tool and is used to draw pixels Freehand

![Pencil Tool](https://user-images.githubusercontent.com/17960677/96023223-b83b8800-0e6f-11eb-8af1-0cfab42c19d7.png)

### Eraser

The Eraser tool is used to erase a given pixel 1 pixel at a time. It has dimensions *1 X 1* and is fixed.

![Eraser Tool](https://user-images.githubusercontent.com/17960677/96023372-f5077f00-0e6f-11eb-965f-815b37f0d7b2.png)

### Paint Tool

The Paint tool is used to Flood Fill a given color with a new color. It works smoothly for dimensions under 128 X 128.

![Paint tool](https://user-images.githubusercontent.com/17960677/96023668-66473200-0e70-11eb-81a2-9313b1580926.png)

![Paint tool](https://user-images.githubusercontent.com/17960677/96023679-6b0be600-0e70-11eb-8451-0d5955f2c8b4.png)

### Line Tool

The line tool is used to draw a line segment between 2 points using the Bresenham line drawing algorithm.  

Click on the tool and click on 2 points to draw a line segment between them. 

![Line Tool](https://user-images.githubusercontent.com/17960677/96023893-b625f900-0e70-11eb-9b16-ac0d68f9423c.png)

### Circle Tool

The Circle Tool is used to draw a circle with a given center and Radius using Midpoint Circle Algorithm.

![Circle Tool](https://user-images.githubusercontent.com/17960677/96024358-3d736c80-0e71-11eb-8c1a-acb528f027b6.png)

### Ellipse Tool

The Ellipse Tool is used to draw an ellipse with a given center and its radius along x-axis and y-axis.

![Ellipse Tool](https://user-images.githubusercontent.com/17960677/96024638-a0fd9a00-0e71-11eb-9171-16944bf95b40.png)


## Utility Tools

### Undo/Redo

The Undo/Redo Functionality is not very advanced and is only capable of undoing/redoing 1 pixel at a time.  
It is only useful for correcting small mistakes, hence, it is advised to draw with care, or, add a frame if doing a big change with chances of mistake.

### Clear Window

This Tool is used to clear the current Canvas window.

Before:  
![Clear Window](https://user-images.githubusercontent.com/17960677/96026664-73662000-0e74-11eb-8111-c46f54375056.png)  
After:  
![Claer Window](https://user-images.githubusercontent.com/17960677/96026681-7a8d2e00-0e74-11eb-9984-c267fb0290c9.png)  


## Advanced Tools

### Import image

This Tool is Used to import an image and convert it to Pixel Art of Given Dimensions.

![Mona Lisa](https://user-images.githubusercontent.com/17960677/96027216-2df62280-0e75-11eb-880d-c1eed2a21fd6.png)
![Mona Lisa Pixelated](https://user-images.githubusercontent.com/17960677/96027394-71509100-0e75-11eb-8260-c1ed426805bc.png)

## Saving Pixel Art and GIF Animation

Once you are done with making your pixel art or animation frames you can export it as a PNG or GIF to share it on other platforms. 

### Saving Image

Save Image option is available in the drop-down on the top left corner, It will download a file named *canvas.png* with dimensions *10 x width X 10 x Height*


## Color Palette & Transparency

The Following colors are available on the Color Palette.

![Color Palette](https://user-images.githubusercontent.com/17960677/96028508-fdaf8380-0e76-11eb-8502-18d49d96d059.png)

You can select any color by clicking on it.  

You can also set color Transparency to create translucent colors and create color combinations. This property can be used to create complex patterns with greater flexibility.

![Complex Pattern](https://user-images.githubusercontent.com/17960677/96028936-95ad6d00-0e77-11eb-8a8c-07caa0f2a8b5.jpg)

## PWA Support

This Web App is a Fully Compatible PWA and is installable.  

![PWA Support](https://user-images.githubusercontent.com/17960677/96029402-3ef46300-0e78-11eb-8a54-d54b6dff458a.png)

You can install it either from the Dropdown or using the "Add to Home Screen" Button From Options.  
