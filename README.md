# Super Mario Bros. 2 Glitched Worlds Script for FCEUX
This is a script for the FCEUX emulator that allows you to navigate otherwise inaccessible areas in Super Mario Bros. 2 (NES).

## How to Use
Super Mario Bros. 2 has 20 normally accessible worlds. But by using this script, the number of accessible worlds skyrockets to **thousands of potential levels**!

To access the script, start by loading the script using FCEUX's Lua window. Once the script is running, click back on the game window and press the key you have binded to the SELECT key. If done correctly, you should see an interface that looks something like this appear in the top-left corner of the screen:

![](https://i.postimg.cc/66RJmmnx/Screenshot-20260717-171454.png)

If you're wondering what these values mean:
* **$0531 (Current level loaded)**: Displays that address in memory to show you which level you're in.
* **WORLD and LEVEL**: These display the values that will be loaded into the world and area addresses in memory.
** Adjust the **WORLD** value by pressing up and down.
** Adjust the **LEVEL** value by pressing left and right.

Once you're done, you can press the B button or the key binded to it to load the level **using your currently selected WORLD and LEVEL values**. If you want to back out of the UI, press the A button or the key binded to it.
