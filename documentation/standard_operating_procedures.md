[comment]: # (develop_godot\documentation\standard_operating_procedures.md)
# Godot Standard Operating Procedures
## Using 3d and 2d in Node Names
Only the top-most node needs 3d or 2d

For example,
    At the root node of a scene would put _main3d at end and child nodes would be assumed 3d
    
    If you had a 2d canvas as a child of the _main3d would add _canvas2d at the end