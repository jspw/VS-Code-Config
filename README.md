# VS Code Config

![How It Looks Like](./images/vscode-in-mac.png)

> [!IMPORTANT]
> _**Newly Added Support for RUST**_
>
> Rust :
>
> - [Linux File](Config-Files/Rust/Linux/tasks.json)
> - [MacOS File](Config-Files/Rust/MacOS/tasks.json)
>

## Intro

This repository contains some configuration files for [Visual Studio Code](https://code.visualstudio.com/) that will give you a better experience while practicing **competitive programming** in a sense of **easy input & output**.

## Back Story

Generally we used to use [Code Blocks](https://www.codeblocks.org/) for practicing competitive programming back then (2018).

It has everything build in there. You just need to create the `.cpp` or `.c` file and run the code by pressing the run button. Then the terminal came up and you put the inputs and get the outputs in the terminal there.

You might be a good coder but I had to run and test my code multiple times to get the correct output. Also I was not a fan of codeblocks as it looks very odd. And at the same time, VS Code also crosses my way. Then I started using it and I found it very useful. But the problem was, I had to run the code in terminal and give inputs and get outputs. So I thought of making a configuration file that will make my life easier. And here it is.

## How It Works

VS Code has their way of doing things. It has concept of workspace and tasks.You can open a folder as workspace and do your stuffs. You can also configure the workspace according to your need. There is a `.vscode` folder in the workspace folder where you can put your configuration files. `settings.json` is the settings for your current workspace and another important file is `tasks.json` file which can be configured to build & run your code with some shortcuts. We have used this `tasks.json` file to make our life easier.

Basically we can set the commands that will run when the shortcut is being used. So, the config file includes building, running the code and then taking input from a file and giving output to another file. Then you just need to write your code, give inputs in the input file and press the shortcut. You will get the output in the output file.

## How To Configure (OS Wise)

- [Windows](./windows.md)
- [Linux](./linux.md)
- [MacOS](./mac.md)

**Note:** The README files are written for **C/C++** only. You can follow the same steps for other languages too.

## Available Language Config Files

- [C/C++](Config-Files/C&C++/)
- [Python](Config-Files/Python/)
- [Java](Config-Files/Java/)
- [Dart](Config-Files/Dart/)
- [Go](Config-Files/Golang/)

## How To Use

- Open your workspace **Folder** where you will code your shit.
  
  - Open VS Code window
  - Then you can go to `Menu -> File -> Open Folder ...`
    ![FILE | MENU](/images/top_bar.png)
    ![Choose Folder](/images/open_folder.png)

- Create your `.c` or `.cpp` file,
- Write code and give inputs in `input.txt` file
- Press `Ctrl+Shift+b` and your output will be in the `output.txt` file.

### Notes

- Make sure your mouse cursor is **clicked** or **focused** on the **cpp file** editor while you are pressing the shortcuts
- I have came to know that some new comers or vscode users sometimes just open the file in vscode instead of opening as folder and press `Ctrl+Shift+b` which will not work. So please open vscode in your desired folder.

Happy coding :3 ([Extra cheese?](./snippets.md))
