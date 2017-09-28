# Lesson 1 - Introduction

## Install TouchDesigner
- Create an account at [derivative.ca](http://derivative.ca/Login/RegisterForm.asp "Register")
- Verify your email address.
- Download and install TouchDesigner 099 version 2017.10000 at [derivative.ca](http://www.derivative.ca/099/Downloads/Archive.asp "Download") for your OS (macOS, Windows).
- Launch TouchDesigner. Login to your account with your username and password. Create a non-commercial license for your computer.

## Concepts

### Perform and Design modes
- **Design mode** is used when creating your project
- **Perform mode** is used when running your project

### Player and Designer licenses
- The **Designer license** permits both **Design mode** and **Perform Mode**
- The **Player license** permits only **Perform mode**

### Real-time vs Rendered | Real-time vs Compiled
- TouchDesigner's **real-time perform environment** allows for *dynamic content* instead of static rendered content.
- TouchDesigner's **real-time design environment** allows for *fast prototyping* instead of a slow, compiled workflow.

## OPs
- **COMPs** are compositional operators. They are used to organize and give context to the networks you create.
- **TOPs** are 2D visual operators. They create and enhance images and videos.
- **CHOPs** are numerical operators. They are used to dynamically parameterize your application.
- **MATs** are material operators. They are used to colorize and texturize geometries.
- **SOPs** are surface operators. They create and modify geometries. They require Light, Camera, and Render OPs to be rendered.
- **DATs** are text elements. Text can be simple, in tabular form. Python scripts are stored in "Text" DATs.

## Converting OPs
- Use a **"CHOP to" TOP** to convert a CHOP to a TOP
- Use a **"DAT to" CHOP** to convert a DAT to a CHOP
- Use a **"CHOP to" DAT** to convert a CHOP to a DAT

Conversion Model:
**TOP** <-> **CHOP** <-> **DAT**

## Scripting
- **Python** scripting is used for creating complex logical structures around TouchDesigner OPs. Python scripting can be used lightly or heavily.
- **GLSL (OpenGL Shading Language)** is used for creating low-level graphics.
- **C++** code can be used to create low-level computing operators.

## Inputs
- **Sensors data** such as Microsoft Kinect, HTC Vive, and Video Inputs, or mouse and keyboard
- **Network data**  such as RSS or API endpoints or local streams

## Outputs
**Real-time graphics** are the most conventional output from TouchDesigner, but TouchDesigner can also be used for streaming data, creating and exporting geometries, or rendering video.

## Helpful Links
[TouchDesigner Wiki](http://derivative.ca/wiki099/index.php?title=Main_Page "Wiki")
[TouchDesigner Forum](https://www.derivative.ca/Forum/ "Forum")
[TouchDesigner Tutorials](https://matthewragan.com/teaching-resources/touchdesigner/ "Tutorials")
