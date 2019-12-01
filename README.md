# GodotPulseGlow

Pulsating light shader for Godot 3.0+ (using GLES3)
Apply only to meshes with rounded corners!

Author:
	Fernando Cosentino
	
Usage:
	Albedo: base object color. Albedo's alpha channel works, 
	        but avoid using it for transparency
			
	Albedo Texture: texture for albedo
	
	Saturation: higher values cause a flat color in the middle with fast alpha edges
	            lower values cause blurred, softer gradient
	
	Pulse Rate: how many times the light pulses per second
	
	Pulse Intensity: how big the light becomes during pulses, 
	                 relative to original object size
	
	Opacity: alpha. Use this in animations to make objects fade in or out

