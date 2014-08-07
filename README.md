H5ProjGen
=========
h5projgen Version:1.0
Copyright (C) 2014 by Victor A. Hernández
<https://github.com/gros777/H5ProjGen >

h5projgen comes with ABSOLUTELY NO WARRANTY.  
This is free software, and you are welcome to 
redistribute it under certain conditions.  
See the GNU General Public Licence v3 for details.

h5projgen is a HTML5 Project generator.    

Uasage:
------- 
h5projgen [OPTIONS]
    -v                  prints the version
    -h                  Shows this message
    -p <project name>   name of the project to be created
    -g                  initialize git repository

Examples:
---------
    h5projgen -p newApp 
        the above command generates the newApp project with the structure
        newApp
        ├── README.txt
        ├── audio   
        ├── images
        ├── lib
        ├── newApp.css
        ├── newApp.html
        └── newApp.js

    h5projgen -p newApp -g
        generates the newApp project and initialize a git repository 
        with a .gitignore file and add an initial commit
        newApp
        ├── README.txt
        ├── audio
        │   └── gitAddFile
        ├── images
        │   └── gitAddFile
        ├── lib
        │   └── gitAddFile
        ├── newApp.css
        ├── newApp.html
        └── newApp.js

