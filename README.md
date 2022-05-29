# vsCode_key_bindings

1. Get the "macros" extension in vsCode
2. Goto settings.json for user and paste at the end the code from settings.json file listed in the git repo
3. This actually creates the custom commands like the vsCode has :
e.g.
vsCode has command cursorUp : To move cursor one line up
But,it doesn't have any command to move up multiple lines

4.So, The commands that you just pasted contains the same commands from the vsCode but has the ability to executed multiple commands on a single trigger

5.You can say it groups the commands together to execute them simultaneously
6.Then you can assign keyBindings to those commands through graphical window  "vsCode keyboard shortcuts"  as "macros.CommandName" format where you can change
CommandName with the custom command available right there in "settings.json" file
7.If it seems tedious to assign each and every command the hotkeys, don't worry just do the following:
    i)Copy the contents of the keybindings.json from gitHub repository
    ii)Paste the contents into  "keybindings.json" for user.Then save.

8.This keybindings overrite the default keybidings available in the default "keybindings.json" file which is read-only for user.

                                                                      Hope it helps....
