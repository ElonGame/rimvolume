# Unity Rim Pseudo Volumetric Shader
A set of shaders for Unity which use the rim of a surface to suggest depth.

The rim is occluded using a texture or noise function to suggest that nothing was there prior. This package includes unlit, cutout, soft textured, textured, and cloud shaders as examples for usage of this method. Because it uses the rim of a surface, the best behaving geometries are spherical or continuously round. This method is useful for rendering clouds, fur, or more general non-photorealistic effects. 

![anim1](http://imgur.com/NqEgx95.gif)

Clouds in action using Inigo Quilez's image based noise https://www.shadertoy.com/view/4sfGzS

![anim2](http://imgur.com/slgumUO.gif)

Example textures, every surface is a perfect sphere.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License</a>.
