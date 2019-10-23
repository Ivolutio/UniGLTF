# UniGLTF

[glTF](https://github.com/KhronosGroup/glTF) 2.0 importer and exporter for Unity 5.6 or later

Improved material importer(UniGLTF-1.21) ! 

Below is imported from [DamagedHelmet](https://github.com/KhronosGroup/glTF-Sample-Models/tree/master/2.0/DamagedHelmet). Using unity standard shader.

![standard shader](doc/pbr_to_standard.png)

![animation](doc/animation.gif)

# License

* [MIT license](LICENSE)

# Usage

## Installation

Clone or download this repository in a folder within your assets folder from Unity.

## Loading GLB from Web (Runtime)

```csharp
ImporterContext importerContext /*= new ImporterContext()*/;

StartCoroutine(importerContext.LoadGLBFromWeb(url, callback)); //callback provides the instantiated GameObject as argument
```

## Editor mode
* menu [UniGLTF] - [Import] 
* open gltf file(gltf, glb, zip) from out of Asset Folder

## For more, see the API

* https://github.com/ousttrue/UniGLTF/wiki/Rutime-API

