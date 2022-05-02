# How to use this template

1.  First, we are going to install NodeJS in our computer. 
    1.  Windows/Mac: Go to url [nodejs.com](https://nodejs.org/es/)
    2.  Linux:
        1.  Ubuntu: sudo apt install nodejs
        2.  Ohter: Search in google sorry.
2.  When the software is installed, proceed to open a blank project with your developer tool, in my case, Visual Studio Code.
3.  Open a terminal:
    1.  Install typescript with node:
        1.  Local -> npm i typescript
        2.  Global -> npm i -g typescript
    2.  Check that the installation creates 2 files in your directory: __package.json__ and __package-lock.json__. They are VIF for the project. And the directory __node_modules__ when it installs dependencies.
4.  Create a __.gitignore__ files and add __node_modules__ and __package-lock.json__ inside the file.
5.  Create 2 directories: __public__ and __src__.
6.  Configure our project by default with the command: npm init -y. This is only necesary if you need include any package with __Node Package Manager__.
7.  For manage properties of our typescript, we need the configuration file __tsconfig.json__. We can created with the command tsc --init.
8.  Check the followed properties in tsconfig.json
    1.  __target__: ECMAScript version of the project.
    2.  __module__: Module code generation.
    3.  __outDir__: This option is commented by default. This variable specify where you are going to generate js files from typescript. The recommended value for the variable is public.
    4.  __rootDir__: This option is commented by default. This variable specify where you retrieve the ts files for compile in js files. The recommended value for the variable is src.
    5.  __strict__: This option enable strict type-check of the code.

