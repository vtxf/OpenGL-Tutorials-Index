#OpenGL教程集合

> 对GitHub库中和OpenGL相关的一些资料的总结。2016.7.3

##教程

**Anton's OpenGL 4 Tutorials**  
https://github.com/capnramses/antons_opengl_tutorials_book  
http://antongerdelan.net/opengl/

**tutorials for OpenGL 3.3 and later**  
https://github.com/opengl-tutorials/ogl  
http://www.opengl-tutorial.org/  
中文翻译：https://github.com/cybercser/OpenGL_3_3_Tutorial_Translation  
中文电子书：https://www.gitbook.com/book/andyque/opengl-tutorials/details

**LearnOpenGL**  
https://github.com/JoeyDeVries/LearnOpenGL  
http://learnopengl.com/
这个教程现在还有两个中文版：  
https://learnopengl-cn.github.io/  
http://bullteacher.com/category/zh_learnopengl_com  
源码可以用cmake配置，比较方便。  

**shader-school**  
https://github.com/stackgl/shader-school

**glslcookbook**  
https://github.com/daw42/glslcookbook  

##参考资料
**cg函数查询**  
http://http.developer.nvidia.com/Cg/index_stdlib.html

**包含OpenGL各版本的规范和扩展**  
https://www.opengl.org/registry/  

OpenGL registry：包含OpenGL各版本的规范和扩展

**opengl官方文档**  
https://www.opengl.org/sdk/docs/

##例子

**GameWorks cross-platform graphics API samples**  
https://github.com/NVIDIAGameWorks/GraphicsSamples  
The GameWorks Graphics Samples pack is a resource for cross-platform Vulkan, OpenGL 4 (GL4) and OpenGL ES 2 and 3 (ES2 and ES3) development, targeting Android, Windows, Linux x86/x64 and Linux for Tegra. It is an expansion and continuation of the longstanding OpenGL Graphics and Compute Samples, adding full support for and samples of the Vulkan 3D API.

**OpenGL SuperBible 7th Edition Source Code**  
https://github.com/openglsuperbible/sb7code

**A collection of simple single file OpenGL examples**  
https://github.com/progschj/OpenGL-Examples  
The build system is cmake (only tested on my linux box...).

**Example code from the OpenGL Shading Language Cookbook**  
https://github.com/daw42/glslcookbook  

**OpenGL 3 and OpenGL 4 with GLSL**  
https://github.com/McNopper/OpenGL  
http://nopper.tv/  
依赖GLUS库（https://github.com/McNopper/GLUS），没有cmake配置文件。官方要求安装Eclipse进行编译。  
例子很全面，包含ray-tracing、BRDF、Computer Shader、Shader Volumes等。  

**OpenGL Samples Pack**  
https://github.com/g-truc/ogl-samples  
The OpenGL Samples Pack is a collection of OpenGL samples based on the OpenGL "core profile" specifications.    
The project aims to promote the new OpenGL features making easier version transitions for OpenGL programmers with a complementary documentation for the OpenGL specification. Despite the fact that the OpenGL Samples Pack provides as simple (and dumb) as possible samples, it's not a tutorial for beginner but a project for programmers already familiar with OpenGL. The OpenGL Samples Pack is also a good OpenGL drivers feature test.    
These samples use FreeGLUT to create window and an OpenGL context, GLEW to load OpenGL implementations, GLM as math library and to replace OpenGL fixed pipeline functions and GLI to load images.    
可以使用cmake配置工程，VS2015配置没有问题。例子很全面。

##封装

**glbinding**  
A C++ binding for the OpenGL API, generated using the gl.xml specification.  
https://github.com/cginternals/glbinding

**OGLplus**  
https://github.com/matus-chochlik/oglplus  
OGLplus is a collection of open-source, cross-platform libraries which implement an object-oriented facade over the OpenGL® (version 3 and higher) and also OpenAL® (version 1.1) and EGL (version 1.4) C-language APIs. It provides wrappers which automate resource and object management and make the use of these libraries in C++ safer and more convenient.

**glium**  
OpenGL的Rust封装 https://github.com/tomaka/glium  

##库
**NanoGUI**  
Minimalistic GUI library for OpenGL  
https://github.com/wjakob/nanogui  
NanoGUI is a a minimalistic cross-platform widget library for OpenGL 3.x. It supports automatic layout generation, stateful C++11 lambdas callbacks, a variety of useful widget types and Retina-capable rendering on Apple devices thanks to NanoVG by Mikko Mononen. Python bindings of all functionality are provided using pybind11.  

**kiUi**  
Auto-layout Ui library, lightweight, skinnable and system agnostic, with an OpenGL backend  
https://github.com/hugoam/kiui  

**glfw**  
https://github.com/glfw/glfw  

**magnum**  
https://github.com/mosra/magnum  
Its goal is to simplify low-level graphics development and interaction with OpenGL using recent C++11/C++14 features and to abstract away platform-specific issues.

##WebGL  
**Babylon.js**  
https://github.com/BabylonJS/Babylon.js

**PlayCanvas WebGL Game Engine**  
https://github.com/playcanvas/engine

**WebGL Globe** 
https://github.com/dataarts/webgl-globe  
WebGL Globe is a platform for visualizing latitude longitude based information using WebGL.  

**Mapbox GL JS**  
Mapbox GL JS is a Javascript & WebGL library that renders interactive maps from vector tiles and Mapbox styles.  
https://github.com/mapbox/mapbox-gl-js  

**webgl-lessons**  
https://github.com/gpjt/webgl-lessons  

**webgl-workshop**  
https://github.com/stackgl/webgl-workshop  

**gl-react**  
https://github.com/ProjectSeptemberInc/gl-react  
http://stack.gl/  
http://glsl.io/  

**webgl-sample-pack**  
https://github.com/WebGLSamples/WebGL2Samples  
WebGL2.0的例子，目前Chrome稳定版打不开。需要下载专门的Chrome Canary版才可以使用。  

**WebGL101**  
https://github.com/emoller/WebGL101  
WebGL基本使用范例。  

##其他

**ANGLE - Almost Native Graphics Layer Engine**  
https://github.com/google/angle  

**Tools for tracing OpenGL, Direct3D, and other graphics APIs**  
https://github.com/apitrace/apitrace  
http://apitrace.github.io/  
类似的软件有RenderDoc、vkTrace、Visual Studio Graphics Debugger、Nvidia的Nsight、AMD的CodeXL、废弃了但是还很好用的gDebugger(被CodeXL取代)、PIX(被Visual Studio Graphics Debugger取代)

**Dead Simple OpenGL (Graphics)**  
https://github.com/Polytonic/Glitter  
http://polytonic.github.io/Glitter/  
Glitter is a dead simple boilerplate for OpenGL, intended as a starting point for the tutorials on learnopengl.com and open.gl. Glitter compiles and statically links every required library, so you can jump right into doing what you probably want: how to get started with OpenGL.

**TwinklebearDev-Lessons SDL 2.0 Lessons**  
https://github.com/Twinklebear/TwinklebearDev-Lessons  
http://www.willusher.io/pages/sdl2/index.html  

**awesome-opengl**  
https://github.com/eug/awesome-opengl  
A curated list of awesome OpenGL libraries, debuggers and resources. Inspired by awesome-... stuff.

**shadertoy**  
https://www.shadertoy.com/

**FFTOcean**
Ocean Simulation Using FFT — C++, OpenGL, glut
https://github.com/CSWest/FFTOcean

**OpenGL 4.5 Reference Pages**
https://www.opengl.org/sdk/docs/man4/index.php

**glm**
https://github.com/g-truc/glm

**gli**
https://github.com/g-truc/gli

**opengl wiki**
https://www.opengl.org/wiki/Getting_Started

**nvidia gameworks**
https://developer.nvidia.com/gameworks
https://developer.nvidia.com/gameworks-vulkan-and-opengl-samples  各种特效集合

**songho**
http://www.songho.ca/opengl/index.html

**glintercept**
https://github.com/dtrebilco/glintercept opengl调试工具，好像只有windows版本，安装文件只有1M左右，很小。需要注意的是64位安装程序只能用于64位opengl程序的调试，32位的用于32位OpenGL程序。最好还是直接用zip包。

**zwqxin**
http://zwqxin.com/

**ocean**  
https://github.com/jbouny/ocean

**shadertoy创始人的个人网址**
http://www.iquilezles.org/www/index.htm
