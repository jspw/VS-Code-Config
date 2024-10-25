# VS Code Config

## Intro

This repository is about how to install and setup vs code for **competitive programming (actually easy input & output)** with **c/c++** for **windows** users.

**Note for old users of this repo :** There were some problems with bash in windows, so i had to convert the `tasks.json` file for cmd (Command Prompt). If you are using this new [json file](./Config-Files/C&C++/Windows/tasks.json) then, please select **cmd** as default profile for vscode terminal. [check this out](#terminal-setup)

## How To Configure

**Note :** You just need to do these things only for the first time of your workspace!

### Pre-requirements

Need VS Code and C++ Compiler mingw installed in your windows pc.

#### Installing VS Code

- [Download & Install](https://­code.visualstudio.com)

#### Installing mingw

- [Download & Install](https://osdn.net/projects/mingw/downloads/68260/mingw-get-setup.exe/)

### Setting Up Environment For C/C++

- In you pc search for **system environment**

  ![search system environment](/images/search%20system%20enbironment.png)

- Go to **Environment variables** (on advance section)

  ![Environment Variables](/images/environment%20variable.png)

- On **system variable** section, select **path**. Then click edit, select new & paste the link of your **mingw bin** folder. (Most probably its in `C:\MinGW\bin`, find it. For me it is `C:\MinGW\bin`)

  ![Path Select](/images/path%20edit%20and%20add%20new.png)

- Select ok>ok>apply>ok for everything.

#### Test MinGW path setup is working

- Open `cmd` (can search in the search section) and type `gcc` and hit enter
- If you find

  ```txt
  gcc: fatal error: no input files
  compilation terminated.
  ```

  or something like that then congrats :3

- else if you cmd says :

  ```txt
  'gcc' is not recognized as an internal or external command,
  operable program or batch file.
  ```

  Then go back to the [Install mingw](#installing-mingw) and check everything again.

### Setup VS Code

- In VS Code, Open your coding folder (From Menu bar : `file->open folder` )
  ![File | Menu](/images/top_bar.png)

- Click on terminal (At the top Menu bar)
  ![Terminal | Menu](/images/top_bar.png)

- Select `configure task..`
- Select `create task.json from template`
- Select `others` and it will create a new `tasks.json` file in your default folder under `.vscode` folder. The folder structure will be like this :

```tree

Your Default Folder (Workspace)
├───.vscode
│      ─── tasks.json

```

- Now replace or copy-paste full [tasks.json of the repository](./Config-Files/C&C++/Windows/tasks.json) with your `tasks.json` file.

#### More things to do

- Split screen in 3 sections
  - split the main section in right (right click of mouse on a file and u will get the split options)
  - then split the right section into up-down (same as below)
    ![Split Options](/images/split%20options.png)
- create a file named `input.txt`
- create a file named `output.txt`
- open input.txt into the upper right section
- open output.txt into the lower right section

This will be the final look of your vs code :

![Final Look of VS-Code](/images/final%20look%20%20vs%20code.png)

## How To Use

Open your workspace **Folder** where you will code your shits.

Create your `.cpp` file, write code and give inputs in input.txt and press `Ctrl+Shift+b` and your output will be in the output.txt file.

**Note :** Make sure your mouse cursor is **clicked** or **focused** on the **cpp file** editor while you are running your code.

***New* Note :** I have came to know that some new comers or vscode users sometimes just open the file in vscode instead of opening as folder and press `Ctrl+Shift+b` which will not work. So please open vscode in your desired folder.
Open VS Code, then you can go to `Menu -> File -> Open Folder ...`
![FILE | MENU](/images/top_bar.png)

In the Repository i have also added *config* files for other Programming Languages too :

- **tasks.json** files for :

  - Python :

    - [Windows File](Config-Files/Python/Windows/tasks.json)
    - [Linux File](Config-Files/Python/Linux/tasks.json)

  - Java :

    - [Windows File](Config-Files/Java/Windows/tasks.json)
    - [Linux File](Config-Files/Java/Linux/tasks.json)

  - Dart :

    - [Windows File](Config-Files/Dart/Windows/tasks.json)
    - [Linux File](Config-Files/Dart/Linux/tasks.json)

  - Go :
    - [Linux File](Config-Files/Golang/Linux/tasks.json)

# VS CODE Snippet

**This one is made for my personal usage, you can add functions as you wish and edit my name and doc.**

## Setup

- Select User Snippets (at top menubar, File/Code [for **mac**] > Preferences > User Snippets) and then select **cpp.json**.
  ![Top Bar](/images/top_bar.png)
- copy or replace the [cpp.json file](./Snippets/cpp.json) and save.

## Usage

- Creating a cpp file if you type **inc** and press **Tab** in your keyboard the **snippet** will load as i have set **prefix** as **inc** in my **json file** . (**You can edit as your own !**)
- This will make programming easy and fast .

## Snippets

- [C++](/Snippets/cpp.json)
- [Python](/Snippets/python.json)
- [Dart](/Snippets/dart.json)
- [Java](/Snippets/java.json)

Happy coding :3
