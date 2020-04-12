# Make Coding Easy
**This tutorial is for linux (debian based) only <br>
If you are a windows user then check this out [Setup VS Code for windows](https://github.com/jspw/VS-Code-Config/blob/master/readme(windows).md)**
### 1. [**VS code task config** to make **competitive programming** easy and **programme ananlysis** !](https://github.com/jspw/VS-Code-Config/blob/master/tasks.json) <br> 

This is a **.json** file which will help you to run your **cpp** file with one **click** or **shortcut**.
In this case , you **don't** need to write **input** in the command line or write **fopen** / **close** stuffs , programme will take input from a file **(input.txt)** automatically and give the output in another file **(output.txt)** .<br>
<br>
You can also find the programme **runtime status** which will help  you to calculate **execution time** as well as **memory usage** and many more !<br>

pre-requirments : 
- Visual Studio Code
- gcc/g++
- time 
  - install time : ```sudo apt install time```
  
More things to do :
Note : **You just need to do these things only for the first time of your workspace!**
- Split screen in 3 sections 
  - split the main section in right
  - then split the right into down
- create a file named `input.txt`
- create a file named `output.txt`
- open input.txt into the upper right section
- open output.txt into the lower right section



A Screenshot of the vs code : ![](https://github.com/jspw/VS-Code-Config/blob/master/vs%20code%20setting.png)

How to setup :
- Go to Configure Default Build Task...
  - In Menu bar 
    - select Terminal
    - Configure Default Build Task
    - will get a  tasks.json file
    - replace the file with my tasks.json file or copy paste
    - save 
    - done 
    
Usage :
- Run : 
  - Shortcut type : **`ctrl+shift+b`** 
- You nee to give the input in the **input.txt** file
- output will be shown in the **output.txt** file
- ##### Bonus : programme status will be shown in the **sys.txt** file 
- people concern about more details such as **binary form** and **disassemble code** can check `tasks(more).json` [file](https://github.com/jspw/VS-Code-Config/blob/master/tasks(more).json)

### 2. [VS CODE Snippet](https://github.com/jspw/VS-Code-Config/blob/master/cpp.json) : 
**This one is made for my personal usage ,you can add functions as you wish and edit my name and doc**
  - Download the cpp.json file 
  - Select User Snippets under **File** > **Preferences (Code > Preferences on macOS)**, and then select **cpp.json** 
  - copy or replace the cpp.json file with downloaded file and save !

### Happy Coding with VS Code
