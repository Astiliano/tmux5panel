# tmux5panel
Template for creating a 5 panel tmux session and a while script to manage input sent to each panel individually

## Instructions:

Create both scripts in same directory
```
chmod +x tmux5panel tmux5panelwhile
./tmux5panel [SESSION-NAME]   ##### tmux does not allow certain characters to be in session names.
```

Once attached to the session, press the following keys
```
CTRL+b then q
```
this will show you panel ID's

in the whilescript you have options:
```
0 ## send keys to panel 0
1 ## send keys to panel 1
2 ## send keys to panel 2
3 ## send keys to panel 3
quit ## kills the tmux session you're in
```


If you want to detach from the tmux session but still have it running in the background, press the following keys
```
CTRL+b then d
```


// You can google search tmux hotkeys





