Universal Shading Language (USL) is new language for shading. `.usl` and `.us` extensions will be used for USL files. 
The main goal of USL is simplfy shaders, 
provide mixins (expecially for common tasks) and translate universal language to vendor specific shaders.

For instance, a simple shader that is written in USL can be compiled/translated to SpirV, GLSL, HLSL or Mesal Shading Language (MSL)... 
This will help to write platform independent portable shaders. 
This is the main goal of the USL language.

Also a VM will be provided, so shaders will be able to run on CPU or GPU (by translated to GLSL, HLSL, MSL, SPIR-V...). USL will also provide library machanizm like Metal or better than Metal. 

Shader caching will also be provided by utilities or Database. Shaders can also be ASCII or binary...

**-- Compiler Is In Progress --**
