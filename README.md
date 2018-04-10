# Unity-Deferred-Lighting-Model
Optimized lighting processing shaders for deferred rendering path
## Features:
* The default Unity's deferred lighting shader is optimizable and inefficent. Thus, the optimized GGX shader and blinn phong shader are provided.
* If you are building project for High-end platform, please use GGX shader with better lighting quality, if you are building project for low-end platform, please use Blinn phong shader for performance.
* The Deferred reflection shader has also been optimized.
## Tutorial:
* Drag the code into (your project folder)/Assets, Open Edit/Project Settings/Graphics, in the built-in shader settings, change the deferred shading and deferred reflection into custom shader.
* replace the built-in "deferred shading" shader and "deferred reflection" shader.
* Enjoy a better lighting performance!
