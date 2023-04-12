# Mesh Align Plus [Blender Addon]

Mesh Align Plus helps you place geometry precisely where it needs to go in your scene. You pick surface features that you want to align, and the addon moves your geometry according to your specifications.

Mesh Align Plus can move objects and leave the underlying mesh data unmodified, or it can move mesh fragments during the modeling process. You can also use measurements from your scene like angle differences, lengths, average positions, normals and other imaginary geometry like an implicit axis, projected points of intersection, etc.

Mesh Align Plus is designed to provide precision modeling capabilities, especially for hard surface modelers, mechanical, architectural and CAD/CAM users. See the simple demo clips below for a general sense of what the addon can do, read the <a href="https://github.com/egtwobits/mesh_mesh_align_plus/wiki">Wiki</a> above (with tons of GIF's), or watch the video tutorials on <a href="https://youtu.be/VBoic2MIC8U">YouTube</a>.

## Quick Examples

![easy_apl_frontpage2](https://user-images.githubusercontent.com/15041801/231297281-8ac7eca9-74a1-4e25-817c-ed612c0dc317.gif)
![basics](https://user-images.githubusercontent.com/15041801/231297300-6877026b-0da3-4586-b259-9b5a99829c0e.gif)
![alt](http://i.imgur.com/JOa7Fcd.gif)

# Installation

Mesh Align Plus should only be installed from the `mesh_mesh_align_plus.zip` files found on the [releases page](https://github.com/egtwobits/mesh_mesh_align_plus/releases), attached to the end of each release announcement (don't zip and download the repo). These zip files are specifically formatted to work with Blender's addon system.

Once you have the right file, use Blender's addon installation feature to load it (`Edit` > `Preferences` > `Addons` > `Install`), and check the checkbox next to the addon name to enable and use it.

Open the sidebar (N) in the 3D View, go to the "Align" tab, and you will find panels for all the Mesh Align Plus tools (each panel name has `(MAPlus)` at the end):

![The addon tab in the 3D View](https://user-images.githubusercontent.com/15041801/231289939-af304ee9-40e8-4143-bcbf-0b6c84ad6738.png)

# Basic Usage

*Note: See the [wiki (above)](https://github.com/egtwobits/mesh_mesh_align_plus/wiki) for more in-depth tutorials and reference info*

![panelinfo2](https://user-images.githubusercontent.com/15041801/231296982-6c4c8367-c67d-4e28-a9c6-7d5cfe18b95d.png)

Mesh Align Plus has both **Easy Mode** tools, and **Expert Mode** tools. **Easy Mode** provides the fastest, easiest workflows for common use cases, and as such should suit most people's needs most of the time. **Expert mode** is available for especially complex cases, and for those who need more options, flexibility and control over their transformations.

In both cases, Mesh Align Plus tools will operate on surface features that you pick. Typical workflows usually look something ROUGHLY like this:

- Pick a surface feature by selecting some geometry as an alignment key (the source key) and hit grab
- Pick another surface feature by selecting some other geometry (the destination key) and hit grab
- Select some object(s) or mesh fragments to apply the motion to and hit apply

![usage_diagram3](https://user-images.githubusercontent.com/15041801/231455238-682280a1-bac6-4cc6-a9d3-74e972b82897.png)

Here's what aligning faces looks like with easy mode:

- Select three verts on an object you want to move and hit "Start Alignment" to designate the source key
- Select another three verts (same object, different object, whatever) and hit "Apply to Active" to designate a destination key and auto-align your source object from the first step

<GIF>

So, easy mode is faster and takes out some steps, but also isn't as flexible.

Expert mode gives you extra options and control over all parts of the transformation.


With expert mode, the source key and destination key can be grabbed from 

Expert mode lets you independently define the source key, the destination key, and what the alignment gets applied to (plus additional options and controls for each of those steps). TODO

TODO (because sometimes you want to move an object using a source key from a different object).
