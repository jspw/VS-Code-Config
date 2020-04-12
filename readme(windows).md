## How to install and setup vs code for competitive programming with c/c++ for Windows Users

###  install  vs code

- Download vs code : [Link](https://­code.visualstudio.com)
- Install in your pc

### Setup environment for c/c++

- install mingw : [link](https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/)

- In you pc search for **system environment**
![]()
- go to **Environment variables**
- Go to **system varibale** and **click on path**
- click edit
- select new 
- paste the link where you mingw bin folder . for me it is `C:\MinGW\bin` 
    - find it there
- select ok ok for everything

### Install git 
- download link [Link](https://git-scm.com/download/win)

Then 

- Open Vs code
- Open your coding folder `file->open folder`
- press `ctrl+~` and the terminal will be opened below
- if in the terminal u find that its cmd then click  on cmd and select '`set default sell`' and select `git`
- Now its saying your shell is bash!


### Run a programme for testing :
- create a file hello.cpp
- write code to print hello
- in terminal (Ctrl+`) use the command `g++ hello.cpp -o test && ./test`
- If you find `hello` then congrats

### Setup vs code

- Clik on terminal (At the top)
- select configure task
- select create task.json from template 
- select other and new task.json file will be created
- now copy and paste the my `task.json` file into ur `task.json` file
- done

More things to do :
Note : **You just need to do these things only for the first time of your workspace!**
- Split screen in 3 sections 
  - split the main section in right (right mouse click on the .cpp file and u will get the split options)
  - then split the right into down (same as above)
- create a file named `input.txt`
- create a file named `output.txt`
- open input.txt into the upper right section
- open output.txt into the lower right section