# SimpleGrassTextured
This plugin for Godot 4 allows you to add grass and plants to your scene in a simple way
![Preview Image](https://github.com/IcterusGames/SimpleGrassTexturedPreview/raw/main/previews/preview_03.jpg)


## How to install

### Using the AssetLib on Godot
* Open the AssetLib tab on Godot and search "Simple Grass Textured"
* Install the Simple Grass Textured plugin
* Enable SimpleGrassTextured in `Project -> Project Settings -> Plugins`

### Manual installation
* Clone or download this repository
* Copy the folder 'addons/simplegrasstextured' in your 'res://addons/' folder
  - ![Preview folder](https://github.com/IcterusGames/SimpleGrassTexturedPreview/raw/main/previews/folder.png)
* Enable SimpleGrassTextured in `Project -> Project Settings -> Plugins`

## How to use

Add a SimpleGrassTextured node to your terrain scene
> Your terrain scene must have a StaticBody3D in order to draw grass on top of the terrain
> - ![Preview scene](https://github.com/IcterusGames/SimpleGrassTexturedPreview/raw/main/previews/simple_scene.png)

Select the SimpleGrassTextured node on your scene and draw on the terrain

### How to use a custom mesh

* Select the SimpleGrassTextured
* Using the inspector load your custom mesh on the mesh propierty
* On the Texture Albedo load your custom texture for the mesh

![Preview custom mesh](https://github.com/IcterusGames/SimpleGrassTexturedPreview/raw/main/previews/preview_04.jpg)

## Licence

MIT

### Assets Copyright/Attribution Notice:

Texture grassbushcc008.png, Licence CC0, by FabinhoSC https://opengameart.org/content/stylized-grass-and-bush-textures-0
