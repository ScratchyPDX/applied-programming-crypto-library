# Overview

This project was created as a stretch challenge to a .NET Maui project. (See the [frontend project](https://github.com/ScratchyPDX/applied-programming-encrypt-decrypt-frontend) here for a description.) The stretch was to take a cryptography class written in C#, build it as a class library (DLL), and then use the DLL in the .NET Maui project.

This project was created using .NET v8.0 and Visual Studio Code. The steps for creating a Class Library project are fairly simple:

1. Start VS Code
2. Open a terminal
3. Navigate to the directory where you want to create the project
4. run the following command to create a new class library project
    > <span style="font-family: 'Courier New', Courier, monospace;">dotnet new classlib -n YourLibraryName</span>
5. Switch to the new project directoy
6. Add the class(es) needed (i.e. Crypto.cs)
6. Build the project using 
    > <span style="font-family: 'Courier New', Courier, monospace;">dotnet build</span>
7. This will build the class library (DLL) the can then be copied to the consuming project


# Is there a demo video?
Not for this project specifically. Check out the documentation for the frontend project. There you'll find link to the demo which includes a quick mention of this stretch project.

For a demo of the cryptography code, see the documentation here:

[applied-programming-encrypt-decrypt](https://github.com/ScratchyPDX/applied-programming-encrypt-decrypt)

# Useful Websites

- [Tutorial: Create a .NET class library using Visual Studio Code](https://learn.microsoft.com/en-us/dotnet/core/tutorials/library-with-visual-studio-code?pivots=dotnet-8-0)

# Future Work

- Had time permitted, it would have been good to publish the class library to NuGet gallery instead of copying the DLL to the consuming project.
