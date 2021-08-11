# VS-Code Config

## About
This repository is about how to install and setup vs code for competitive programming with c/c++ for Windows Users.

**Note for old users :** There were some problems with windows and bash, so i had to convert the `tasks.json` file for windows cmd. So If you are using this new json file then, please select bash as default  Profile

## Usage

### Pre-requirments
Need VS Code and C++ Compiler mingw installed in your windows pc.

#### Install vs code

- Download vs code : [Link](https://­code.visualstudio.com)
- Install in your pc

#### Install mingw

[link](https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/)

##### Setup Environment For C/C++

- In you pc search for **system environment**

![search system enbironment](/images/search%20system%20enbironment.png)

- Go to **Environment variables**

![](/images/environment%20variable.png)

- Go to **system varibale** and **click on path**

![](/images/path%20edit%20and%20add%20new.png)

- Click edit

- Select New

- Paste the link where you mingw bin folder
  For me it is `C:\MinGW\bin`
  - find it there
- Select ok ok for everything

##### Test MinGW path setup

- Open cmd and type gcc and hit enter
- If you find 

  ```
  gcc: fatal error: no input files
  compilation terminated.

  ```

  or something like that then congrats :3 

- If you cmd says : 

  ```
  'gcc' is not recognized as an internal or external command,
  operable program or batch file.

  ```

  Then go back to the [Install mingw](InstallMingw) and check everything again.


### Setup VS Code

- Open VS-Code
- Open your coding folder (From Menu bar :  `file->open folder` )
 ![](/images/top_bar.png)
- Clik on terminal (At the top Menu bar)
  ![](/images/top_bar.png)
- select `configure task..`
- select `create task.json from template`
- select `others` and it will create a new `tasks.json` file in your default folder under `.vscode` folder. The folder structure will be like this : 

```.tree
Your Default Folder (Workspace)
├───.vscode
│   tasks.json

```

- now replace [my tasks.json](./Config-Files/C&C++/Windows/tasks.json) file with your `tasks.json` file
- done :D

#### More things to do
Note : **You just need to do these things only for the first time of your workspace!**

- Split screen in 3 sections
  - split the main section in right (right mouse click on the .cpp file and u will get the split options)
  - then split the right into down (same as below)
  ![](/images/split%20options.png)
- create a file named `input.txt`
- create a file named `output.txt`
- open input.txt into the upper right section
- open output.txt into the lower right section

This will be the final look of your vs code

  ![](/images/final%20look%20%20vs%20code.png)

Now create your file .cpp and give inputs in input.txt and press `Ctrl+Shift+b` and your output will be in the output.txt file

**Note :** Make sure your mouse corsor is **clicked** or **focused** on the **cpp file** editor while you are running your code.

In the Repository i have also added _config_ files for other Programming Languages too :

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


# VS CODE Snippet

**This one is made for my personal usage ,you can add functions as you wish and edit my name and doc**

- Select User Snippets under **File** (at Left top bar) > **Preferences (Code > Preferences on macOS)**, and then select **cpp.json**
  ![](/images/top_bar.png)
- copy or replace the cpp.json file {[Link](/Snippets/cpp.json)} and save !

## Usage :

- Creating a cpp file if you type **inc** and press **Tab** in your keyboard the **snippet** will load as i have set **prefix** as **inc** in my **json file** . (**You can edit as your own !**)
- This will make programming easy and fast .

- **Snippets** for :

  - [Python](/Snippets/python.json)
  - [Dart](/Snippets/dart.json)
  - [Java]() **To be added**

# Happy coding :3
