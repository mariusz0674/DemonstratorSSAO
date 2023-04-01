# DemonstratorSSAO

![Alt Text](https://github.com/mariusz0674/DemonstratorSSAO/blob/master/SSAO.gif)

SSAO (Screen Space Ambient Occlusion) is a lighting rendering technique that aims to simulate the shading of surfaces located close to each other and create more realistic visual effects. SSAO works based on the information contained in the rendered image, using the so-called screen space to detect areas where light is limited by other objects. Based on this information, an additional texture channel is generated, which is used in the final rendering process. SSAO is particularly useful in games and VR applications, where realistic lighting is crucial for user immersion in the virtual world.

This project demonstrates SSAO on a helicopter model placed in space with one light source. The user can freely move around the space and change the position of the light source.

The SSAO effect can be manipulated with three main parameters:

Bias - controls the sharpness and detail of the SSAO effect.
Sampling radius - determines the size of the area that is examined to find shaded fragments.
Sample kernel size - determines how many samples are taken into account at each point.
The project was created using the OpenGL environment and the menu was implemented using Dear ImGui library.

This project was inspired by and created with the help of the source: "Learn OpenGL Programming Language" by Joey de Vries.
