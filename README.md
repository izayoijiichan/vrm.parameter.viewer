# VRM Parameter Viewer
This is a viewer that displays the parameters in the VRM file.

![image1](https://github.com/izayoijiichan/vrm.parameter.viewer/blob/master/images/screenshot_1.png)
![image2](https://github.com/izayoijiichan/vrm.parameter.viewer/blob/master/images/screenshot_2.png)
![image3](https://github.com/izayoijiichan/vrm.parameter.viewer/blob/master/images/screenshot_3.png)

## Description
Reads the specified VRM file and displays glTF and VRM extended information.

## Requirement
- Windows 10
- .NET Core 3.0
- Newtonsoft.Json.dll 12.0

## Installation
Download exe and place it anywhere.

## Usage
1. Launch exe.
2. Specify VRM file.
    - Press the 'Open File' button and select the file in the dialog.
    - Drag and drop the VRM file onto the form.
    - Specify the path to the VRM file with command line arguments at startup.

## Specification Version
- UniVRM: v0.53.0 (5 Jun, 2019)
- UniVRM JSON Schema: [0.0](https://github.com/vrm-c/UniVRM/tree/master/specification/0.0/schema)
- glTF JSON Schema: [2.0](https://github.com/KhronosGroup/glTF/tree/master/specification/2.0/schema)

## Implementation
- VRM
    - meta
    - humanoid
    - firstPerson
    - blendShapeMaster
    - secondaryAnimation
    - materialProperties (uncompleted)
        - Standard (unimplemented)
        - VRM/MToon
        - VRM/UniUnlit
- glTF
    - accessors
    - animations (unimplemented)
    - asset
    - buffers
    - bufferViews
    - cameras (unimplemented)
    - images
    - materials
    - meshes
    - nodes
    - samplers
    - scene
    - scenes
    - skins
    - textures

## Link
- [VRM](https://github.com/vrm-c/UniVRM)
- [Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)
