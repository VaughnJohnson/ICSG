# ICSG
Improved version of the CSG module that is built with Godot game engine.

This project was built from the ground up based on my knowledge of geometry intersection. It is a bit more reliable in providing closed meshes than Godot's CSG. Computation time seems to be much longer than Godot's CSG because my implementation has almost no optimizations, everything done is more or less brute force. I originally built this for use of procedurally generating buildings, but the computation time became too great for meshes that were composed of hundreds of cubes.

Further work on this is not expected.
