# WOS-Model-Blender-Addon
Blender addon to import and export Spider-Man: Web of Shadows models

# Important
I tested the importer, exporter and their compatibility with each other on some meshes, skinned and non-skinned, and it looked fine. If you encounter issues, feel free to report them.

This addon is designed on Blender 4.5.0

The model importer allows multi-file import, through Blender File View, or drag-and-drop. It creates a new mesh collection for each model.

The importer can import the following attributes:
- Positions (Basic)
- Indices (Basic, Triangle Strips converted to Triangle List for Blender to consume)
- Normals
- Tangents (Recalculated automatically by Blender)
- Binormals (Recalculated automatically by Blender)
- UVs (Flips the V to match Blender's bottom-to-top)
- Colors
- Blend Indices
- Blend Weights

The exporter allows exporting multiple collection at the same time, each to their own file, it calculates the filename hash (hash of the model name) and prepends it to the final filename.

The exporter can export the following attributes:
- Positions
- Indices (Triangle List converted to Triangle Strips for the game to consume)
- Normals
- Tangents
- Binormals
- UVs
- Colors
- Blend Indices
- Blend Weights




