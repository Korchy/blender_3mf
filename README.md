# Blender 3mf format Import/Export

Blender add-on for importing and exporting from/to *.3mf file format.

Add-on functionality:
-
**Import**

For importing 3D manufacture format files (*.3mf) to Blender scene use the Main menu - File - Import - 3D Manufacturing format (.3mf) command.  

Importing by operator call (from command line):

    bpy.ops.import_mesh.threemf(filepath="/path/to/file.3mf")

**Export**

For exporting meshes from Blender scene to 3D manufacture format (*.3mf) file use the Main menu - File - Export - 3D Manufacturing format (.3mf) command.  

Export by operator call (from command line):

    bpy.ops.export_mesh.threemf(filepath="/path/to/file.3mf")

Forked
-
This is the fork of the original [Blender3mfFormat](https://github.com/Ghostkeeper/Blender3mfFormat) add-on by Ghostkeeper to make it compatible with Blender 4.4. 

Current add-on version:
-
1.0.3.

Blender versions:
-
4.4, 4.5

Location and call:
-
Main menu - File - Import - 3D Manufacturing format (.3mf)

Main menu - File - Export - 3D Manufacturing format (.3mf)

Installation:
-
- Get *.zip archive with the add-on distributive.
- The “Preferences” window — Add-ons — Install from Disk... — specify the downloaded archive.

Version history:
-
1.0.3.
- Updated for Blender 4.4 compatibility
- Forked from the original repository

