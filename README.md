# Volumetric Clouds

This is a demo implementing one way of drawing volumetric
cloudscapes in Godot sky shaders.

This demo uses animated clouds generated from ray marching
3D textures. It features automatic time of day adjustments
just by rotating the sun.

Renderer: Vulkan

Fork changes:

	- Clouds are calculated in half resolution pass
	
	- Additional optimization
	
	- Clouds don't reset after some time anymore
	
	- Organized parameters
	
	- Additional settings
	
	- Space emit
	
	- Clouds following camera


## Screenshots

![Screenshot](screenshots/Midday.png)

![Screenshot](screenshots/Dusk.png)

![Screenshot](screenshots/Sunset.png)

![Screenshot](screenshots/night.jpg)