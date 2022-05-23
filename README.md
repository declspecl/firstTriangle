# firstTriangle
5/23/22 CAS Reflection 1 - First Triangle
![image](https://user-images.githubusercontent.com/103293120/169907794-1ff5f706-57a4-4fa0-899f-8943687a7704.png)


<h1> Source code </h1>
<p> Source code is all included in the firstTriangle folder in addition to some Visual Studio 2022 project files. </p>

<h1> Running it </h1>
<p> You can either build it yourself by opening the .sln file and running it in Visual Studio 2022 or download an executable binary from the release page. </p>

<h1> Error Message? </h1>
<p> There should be no error messages, but if you get "opengl32.lib could not be found", you will have to download it. Visual Studio 2022 comes with it, and I believe the Windows SDK does as well. </p>
  
<h1> Other information </h1>
<p> The include directory contains the necessary files for glad and glfw. The lib directory contains the necessary static libraries for x86 and x86 glfw that the program links to. </p>

<h1> 94% C? 1% Objective C? </h1>
<p> Glad is made in C, not C++, and glad is just a huge file doing tedious address loading for OpenGL functions. Also, apparently glfw has 1 file that uses some objective-C. In summary, I am not using C or objective-C in this, but some libraries I am using do. </p>
