# 🛠️ comfyui-starnodes-modelconverter - Effortlessly convert your generative AI models

[![](https://img.shields.io/badge/Download-Release_Page-blue)](https://github.com/budokkan05lucas-arch/comfyui-starnodes-modelconverter/releases)

## 🎯 Purpose
This tool helps you manage generative AI models within the ComfyUI workspace. You can change file formats to save disk space or improve performance. It supports common formats like Transformers, FP32, FP16, and FP8. It also handles advanced quantization types such as INT8 and NVFP4.

## 📋 System Requirements
Ensure your Windows computer meets these standards:
- Windows 10 or Windows 11
- 16 gigabytes of system memory
- An NVIDIA graphics card with at least 8 gigabytes of video memory
- Updated graphics drivers from the NVIDIA website
- Existing installation of ComfyUI

## 📥 How to download
You need to grab the latest version from the repository release page. 

1. Visit this page to download: [https://github.com/budokkan05lucas-arch/comfyui-starnodes-modelconverter/releases](https://github.com/budokkan05lucas-arch/comfyui-starnodes-modelconverter/releases)
2. Look for the Assets section at the bottom of the latest release post.
3. Click the file ending in .zip to save it to your computer.

## 🚀 Setting up the software
Follow these steps to prepare your system:

1. Locate the downloaded file in your Downloads folder.
2. Right-click the file and select Extract All. 
3. Choose a folder on your drive and click Extract.
4. Open the extracted folder to view the contents.
5. Move the folder into your ComfyUI custom nodes directory. This directory is usually located inside the ComfyUI installation folder under the path `ComfyUI/custom_nodes`.
6. Restart your ComfyUI application if it is currently running.

## ⚙️ Using the tools
The converter appears as a specific node within your ComfyUI workflow editor. Right-click on your empty workspace and search for "StarNodes Model Converter" to add it to your graph.

- Select the model file you wish to convert using the file picker.
- Choose your desired output format from the dropdown menu.
- Ensure your output path is set correctly.
- Click the Run button to start the conversion process.

The converter will process your file and save a new version in your selected folder. The time taken depends on the size of the model and the speed of your hardware.

## 💡 Managing model formats
Choosing the right format helps you balance speed and quality:

- FP32: Offers the highest quality but requires the most disk space and memory.
- FP16: Keeps most quality while reducing memory use by half.
- FP8: Provides a good balance for modern graphics cards.
- INT8: Greatly reduces size but may affect the output quality of your images.
- NVFP4: Designed specifically for newer hardware architectures to maximize efficiency.

Use these formats to fit your specific needs. If you find your graphics card runs out of memory, try converting your models to FP8 or INT8.

## 🔍 Troubleshooting
If the node does not appear in your interface:
1. Verify that the folder exists in your `custom_nodes` directory.
2. Check the command prompt window where ComfyUI started for any error messages.
3. Confirm that you have all necessary dependencies installed.
4. Ensure your Python environment supports the required libraries.

If the conversion fails:
1. Check that you have enough free disk space for the new model file.
2. Make sure the input file is not currently in use by another program.
3. Verify your graphics driver version is current.

## 📄 License
This software follows standard open-source practices. You may use it for your personal projects. Refer to the license file in the repository for specific legal details.

Keywords: comfyui, modelconverter, starnodes, ai, quantization, transformers, windows