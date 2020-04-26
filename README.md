# arma_3_substance_shader
A Substance Painter shader for Arma 3 super shader objects.


The channels used are:

 - Diffuse (_co) [sRGB]
 - Normal (_nohq) [L]
 - Specular level (_smdi) [L]
 - Glossiness (_smdi) [L]
 - User0 (Ambient Occlusion, _as green channel, Optional) [L]
 - User1 (Diffuse Occlusion, _as blue channel, Optional) [L]
 - User2 (Macro, Optional) [RGB]
 - User3 (Detail, Optional) [RGB]
 - User4 (Macro Alpha, Optional) [L]

The environment should also be set to a regular ARMA 3 environment map, not a third party HDR.

Use the env_co image for your environment map. It can be found in ‪P:\a3\data_f\env_co.paa.
You will need to convert the image into either a tga or png format.
