# Blender Hotkeys

Blender has a different workflow from traditional 3D graphics suites. Typically in a program such as Maya, or even a game engine such as Unreal Engine or Unity 3D, you'd press `Q`, `W`, `E`, or `R` to make one of the manipulation tools as your active tool, then click and drag the gizmo that pops up to manipulate your object, vertices, edges, or faces. Blender works radically different, not only with a different keymapping standard which throws people off, but also with a completely different functionality when a hotkey is pressed. In Blender, instead of the above happening, pressing "G" for instance, which is the hotkey to translate an object, will cause the object to become attached to your mouse so you can move it around without having to point at and click a gizmo manipulator. Then, you can press `X`, `Y`, or `Z` to snap the movement to that axis, or `Shift+X`, `Shift+Y`, or `Shift+Z` to exclude that axis from the transformation. You can probably paint the picture how this drastically improves the speed in your pipeline.

Because of this Blender is viewed as difficult to learn and use It also doesn't help the fact that Blender's UI used to be an atrocious mess, which was addressed in version 2.8. I believe this is why many people do not give Blender a fair chance and instantly dismiss it. The hotkeys are strange to a professional used to industry standard software and since they didn't understand the hotkeys it left them with using the UI, which was an absolute mess.

Once you master the shortcuts you really see where the power behind Blender's hotkey-driven workflow. A lot of people are moving to Blender from industry standard software especially now given Autodesk's new Student licensing. I've taken the liberty in compiling a list of essential shortcuts. It's a lot, but you're not meant to know them **all**. You're just meant to know the essential ones. I tried to move those to the top of the list, but keep in mind the entire list isn't in any particular order other than maybe the first 25 hotkeys. Believe me, once you download Blender, install it, start up a new Blender scene and start learning it doesn't take any time to familiarize yourself with the shortcuts. _It just takes persistence and practice, just like learning Maya or 3ds Max did!_ Remember, you're just learning the hotkey and GUI. The principles that you learned previously in other software still applies.

>The `.` key on the keypad and the `.` key to the left of the shift key performs different operations! The `.` key next to the shift key (that most of us use as the full stop key) brings up the pivot translate menu, where the `.` key on the keypad that most of us use when typing decimals in numbers will frame the selected object(s). The `/` key next tothe `Shift` key and the `/` on the keypad perform the **same** operation.
  
>The 'M' key does different things depending on the mode you're in. While in object mode, it will populate the `Move to Collection` menu, while in edit mode it will populate the `Merge` menu.

Key|Action|Notes
:---:|---|---
G|Translate|Grabs object, vertex, edge, or face and moves it around
R|Rotate|Rotates object
S|Scale|Scales object
B|Box Select|Click and drag to box select
C|Circle Select|Click and drag to select objects, verticies, edges, or faces within the selection circle
E|Extrude|Extrudes vertex, edge, or face
1|Vertex Selection|Click vertices to select
2|Edge Selection|Click edges to select
3|Face Selection|Click faces to select
I|Inset|Insets an edge around a vertex, edge, or face
J|Vertex Connect Path|Used to create a line that draws a line between selected vertices
K|Knife Tool|Used to draw out vertices to create geometry
Y|Split
H|Hide Object|Hides object from viewport
L|Select Linked|Selects linked objects
M|Move to Collection Menu|Brings up collection menu that allows you to add an object to a collection
M|Merge Menu|Brings up merge menu with different merge operations
N|Toggle Sidebar|Toggles the sidebar on and off that has different transformation tools
T|Toggle Toolbar|Toggles the toolbar on and off that has different tools
P|Separate Menu|Brings up separate menu that includes different separate operations
X|Delete Menu|In object mode, deletes selected object; in edit mode, brings up contexual menu that includes different delete operations
Z|Shading Menu|Brings up shading pie menu with the four different viewport shading modes
Q|Quick Favorites|Brings up quick favorites menu that has different tools that has been added to favorites
.|Transform Pivot Point Menu|Brings up pie menu with different ways to manipulate the pivot point
/|Local Mode Toggle|Isolates the selected object from the rest of the scene
F9|Operator Panel|Brings up operator panel that exposes extra options from the previous operation
Tab|Editing Mode Toggle|Toggles between edit and object mode, in sculpting toggles between sculpting and object mode
Alt+E|Extrude Menu|Brings up menu with various extrude operations
Alt+S|Shrink/Flatten|Shrinks or flattens an object
Alt+H|Unhides hidden objects from viewport
Alt+N|Normals Menu|Brings up normals menu that includes different operations for managing normals
Alt+D|Link Duplicate|Creates a linked duplicate that replicates changes
Alt+Z|Toggle X-Ray|Activates x-ray shading mode that makes objects semi transparent
Alt+J|Tris to Quads|Converts triangular topology to quad topology
Alt+LMB|Loop Select|Selects vertices, edges, or faces along a loop given there is a complete loop of even geometry
Ctrl|Snapping Modifier|During a transformation operation (translate, rotate, scale), snaps the operation to the grid whilst key is held down
Ctrl+R|Loop Cut|Inserts loop rings around even geometry
Ctrl+B|Bevel|Creates rounded faces around edges
Ctrl+F|Faces Menu|Brings up menu with different operations that can be applied to faces
Ctrl+L|Select Link All|Selects all linked objects
Ctrl+J|Combine Mesh|Combines multiple loose objects into one
Ctrl+LMB|Path Select|Selects edges along a path
Ctrl+RMB|Extrude to Pointer|Extrudes a vertex, edge, or face to the mouse pointer
Ctrl+Shift+LMB|Region Selection|Selects faces within a region of specified vertices or edges
Shift+D|Duplicate|Duplicates object(s), vertex(vertices), edge(s), or face(s)
Shift+N|Recalculate Normals|Recalculates normals so all normals are facing the proper direction
Shift+Z|Toggle Wireframe|Toggles wireframe mode on and off
Shift+W|Bend Tool|Tool that allows you to bend objects around the 3D cursor and mouse cursor
Shift+G|Select Similar|Opens menu with a variety of select similar operations
Shift+RMB|Move 3D Cursor|Moves the 3D cursor to the mouse pointer
Shift+Tab|Toggle Snapping|Toggles snapping on and off
Shift+Space|Toolbar Menu|Brings up menu that has all the tools from the tools panel
Shift+Alt+S|To Sphere|Attempts to translate a cube shaped object to a sphere shaped object
Ctrl+Alt+Shift+S|Shear|Skews an object along the X, Y, or Z axis
Numpad 1|Front Orthographic
Numpad 3|Right Orthographic
Numpad 7|Top Orthographic
Numpad 9|Bottom Orthographic
Numpad 5|Orthographic/Perspective Toggle|Toggles between orthographic and perspective modes
Numpad 2|Rotate Camera Down|Rotates camera down
Numpad 4|Rotate Camera Left|Rotates camera left
Numpad 6|Rotate Camera Right|Rotates camera right
Numpad 8|Rotate Camera Up|Rotates camera up
Numpad -|Zooms Camera Out|Zooms the camera out on the dolly
Numpad +|Zooms Camera In|Zooms camera in on the dolly
Numpad 0|Activates Camera View|Activates the camera view so you can see the perspective if the scene were rendered
Numpad .|Frame Selected|Frames selected object(s) in the scene to be visible
Home|Frame All|Frames all objects to appear in the middle of the scene
