<h1 align="center">io_scene_mw_mwv - Morrowvis Blender Import Scripts</h1>

<p align="center">
  <a href="https://morrowvis.com/documentation/tools/io-scene-mw-mwv/">Documentation</a>
</p>

These are modified import scripts for the Morrowind Blender Plugin. Several additional nodes are included, and the defaults include all handled nodes and otherwise match the original plugin. Ignore settings can be set to filter the nodes. There are also several safeguards that aim to minimise errors. These modifications are designed to be non destructive additions, and also take advantage of Blender 5's longer data-block names.

[Morrowind Visusalisation Project](https://morrowvis.com/documentation/) is reliant on these scripts.

To install, overwrite files in: `AppData\Roaming\Blender Foundation\Blender\5.0\scripts\addons\io_scene_mw`

* `scripts\import_simple.py` can be used for a quick start import, opened in the Scripting tab of Blender.<br>
* `nif_folder` can be pointed to the output of Export Cells or any other folder containing NIF files.
* The import will usually require further merging and hierarchy simplification to make it more usable.

### Prerequisites

* [Blender 5](https://www.blender.org/)
* [Morrowind Blender Plugin](https://github.com/Greatness7/io_scene_mw)
