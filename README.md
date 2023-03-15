![Unreal Engine](https://img.shields.io/badge/unrealengine-%23313131.svg?style=for-the-badge&logo=unrealengine&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
# Unreal Engine Asset Organizer
# ue-asset-folder-organizer

The Unreal Engine Asset Organizer script allows you to quickly and easily organize your assets by moving them to the correct folder based on their class type.

# Requirements
* Unreal Engine 4.26 or later installed
* Python 3.7 or later installed
* unreal Python module installed

# Installation:

1. Clone this repository or download the ZIP archive and extract its contents.
2. Copy and paste the script file into your Unreal Engine project's script folder.

# Usage 

1. Open your Unreal Engine Project
2. Select the assets you want to organize.
3. In the main menu, select **File > Execute Python Script**
4. Locate the script in your project's script folder and run it!.

# Notes

* The script only moves assets that are selected at the time of exeution
* The script will not overwrite any existing assets.
* The script will not move any assets that are not supported by Unreal Engine's EditorAssetLibrary.
* The script logs the results of its actions to the Unreal Engine output log.
