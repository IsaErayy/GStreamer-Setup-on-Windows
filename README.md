# GStreamer-Setup-on-Windows

 1- First download necessary files. The installers are split into runtime and development packages. For development, you will want to install both packages.
 -> Choose one of the options from installer types which is shown below with respect to your software development environment.
 ![image](https://github.com/IsaErayy/GStreamer-Setup-on-Windows/assets/162883392/6cbea321-6f55-4ed6-95ac-f3a64042df17)

2- After installing packaging adjust the environment path for the compiler.
 -> Find "bin" file inside gstreamer where you locate it when installing.
 -> For example, for my file is located at "C:\1.0\mingw_x86_64\bin".
 -> Finally add the path to environment variables. 
 
3- To complete the set up, create a new variable and adjust its name as "GST_PLUGIN_SYSTEM_PATH" (the name is optional) and then add "C:\1.0\mingw_x86_64\lib\gstreamer-1.0" path.Aftert that,
you finally complete the set up of GStreamer for windows. 
![image](https://github.com/IsaErayy/GStreamer-Setup-on-Windows/assets/162883392/132cafd8-af8f-4073-97cf-299b157ef232)


