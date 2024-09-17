# Read-screen-resolution-by-GL-lib-cpp
Step 1: Click here https://www.glfw.org/download.html to download GLFW library! 
Step 2: Extract the file you have downloaded
Step 3: Select the include folder, select all files with the .h extension
Step 4: Throw all those .h files into the include\GL path in the environment you are running in usually with devcpp it will be programfilex86/devcpp/mingw64/x86_64/include/GL
Step 5: Select the lib folder that matches your operating system, then take out all the files with the .a extension.
Step 6: Throw all those .a files into the lib folder in the same path as the previous include folder
Step 7: In the appropriate lib folder that you have extracted, there is a file with the extension .dll left, please take it.
Step 8: Drop it into the windows\system32 path
Step 9: Add this linker to run your project -lglfw3 -lopengl32 -lGdi32 (this will link to your .a file and dll file) 
Step 10: Run it
