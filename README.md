# Clutter 
<a href="http://clutter-project.org">Clutter</a> is a GObject based library for creating fast, visually rich, graphical user interfaces.

Clutter works by manipulating a scene-graph of 2D surfaces, or 'actors', inside a 3D space.

ClutterActor is the base class for such surfaces. All ClutterActors can be positioned, scaled and rotated in 3D space. In addition, other properties can be set, such as 2D clipping, children and opacity. Tranforms applied to a parent actor also apply to any children. Actors are also able to receive events.

Subclasses of ClutterActor include ClutterStage, ClutterTexture, ClutterLabel, ClutterRectangle, ClutterEntry and ClutterGroup. ClutterActors are added to a parent, transformed and then made visible.

ClutterStage is the top level ClutterActor - it's the representation of a window, or framebuffer. It is created automatically when Clutter is initialised. ClutterStage is a ClutterGroup, a class implementing the ClutterCointainer interface.

ClutterTimelines provide the basis for Clutter's animation utilities. Multiple timelines can be synchronised using ClutterScore, and ClutterBehaviour and ClutterEffect allow for the creation of animation effects such as transitions.

Clutter further contains a number of utilities, including; ClutterScript - for loading 'UI definition' files formatted in JSON, ClutterShader - a class for applying GPU shaders to actors, ClutterModel - a utility class for MVC list type implementations, and fixed point math utilities.

For detailed docs, see <a href="http://clutter-project.org/docs/clutter/stable/">clutter-project</a>.

# Installation

Clutter library should be installed and foundable in your system. Then:
```
eerie install https://github.com/IoLanguage/Clutter.git
```
