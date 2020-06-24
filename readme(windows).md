## How to install and setup vs code for competitive programming with c/c++ for Windows Users

###  install  vs code

- Download vs code : [Link](https://­code.visualstudio.com)
- Install in your pc

### Setup environment for c/c++

- install mingw : [link](https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/)

- In you pc search for **system environment**

![search system enbironment](/images/search%20system%20enbironment.png)

- go to **Environment variables** 

![](/images/environment%20variable.png)

- Go to **system varibale** and **click on path**

![](/images/path%20edit%20and%20add%20new.png)

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

- press `ctrl+~` and the terminal will be opened below (At the bottom of the vs code)

![](/images/vs%20code%20terminal.png)

- if in the terminal u find that its **cmd** or **powershell** then click  on **cmd/powershell** and select '`set default sell`' and select `git`

- - Now click on the delete icon and  press `ctrl+~` and its saying your shell is bash!

- if still bash no showing then close vs code and open vs code again

![](/images/vs%20code%20terminal.png)


### Run a programme for testing :
- create a file hello.cpp
- write code to print hello
- in terminal use the command 

        g++ hello.cpp -o test && ./test
        
        
- If you find `hello` then congrats
- if saying g++ not found then try to close vs code and then oepn vs code again.

### Setup vs code

- Clik on terminal (At the top bar) 
  ![](/images/top_bar.png)
- select configure task
- select create task.json from template 
- select other and new task.json file will be created
- now copy and paste the my `task(windows).json` {[link is here](https://github.com/jspw/VS-Code-Config/blob/master/task(windows).json)}   file into your `task.json` file
- done

More things to do :
Note : **You just need to do these things only for the first time of your workspace!**
- Split screen in 3 sections 
![](/images/split%20options.png)
  - split the main section in right (right mouse click on the .cpp file and u will get the split options)
  - then split the right into down (same as above)
- create a file named `input.txt`
- create a file named `output.txt`
- open input.txt into the upper right section
- open output.txt into the lower right section

#### This will be the final look of your vs code 
![](/images/final%20look%20%20vs%20code.png)


## Now create your file .cpp give inputs in input.txt and press `Ctrl+Shift+b` and your output will be in the output.txt file 


# 2. VS CODE Snippet 
**This one is made for my personal usage ,you can add functions as you wish and edit my name and doc**

  - Select User Snippets under **File** (at Left top bar) > **Preferences (Code > Preferences on macOS)**, and then select **cpp.json** 
  ![](/images/top_bar.png)
  - copy or replace the cpp.json file {[Link](</Snippets/cpp.json>)} and save !

## Usage :
- Creating a cpp file if you type **inc**  and press **Tab**  in your keyboard the **snippet** will load as i have set **prefix** as **inc** in my **json file** . (**You can edit as your own !**)
- This will make programming easy and fast .




# In the Repository i have also added *config* files for other Programming Languages too :
- **task.json** files for :

  - Python : 

    - [Windows File](Config-Files/Python/Windows/tasks.json)
    - [Linux File](Config-Files/Python/Linux/tasks.json)


  - Java : 

    - [Windows File](Config-Files/Java/Windows/tasks.json)
    - [Linux File](Config-Files/Java/Linux/tasks.json)

  - Dart : 
  
    - [Windows File](Config-Files/Dart/Windows/tasks.json)
    - [Linux File](Config-Files/Dart/Linux/tasks.json)



- **Snippets** for :

  - [Python](/Snippets/python.json)
  - [Dart](/Snippets/dart.json)
  - [Java]() **To be added**



# Happy coding :3 
