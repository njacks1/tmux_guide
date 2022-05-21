# How To Setup **<span style="color:#3DCB3E">tmux</span>** In Shell


## **About**

### This guide will give you the commands needed to load and run tmux within the shell.

<br/>

## **Setting It Up**


1. Open up your preferred shell. If you are not sure what shell is your favorite, just start with termx.

2. Check to see if tmux is already in your bin folder
```
which tmux
```

3. If you get a "not found" message after running the above command run the following command below
```bash
mgrep tmux
```

4. After getting tmux in your bin folder, simply load the module with the command below
```bash
module load tmux
```

<br/>

## **Activating **<span style="color:#3DCB3E">tmux</span>** and some useful commands**

### This is by no means an extensive list of the commands or operations which can be performed in tmux. To see a full list or more detailed one, visit this [link](https://man.openbsd.org/OpenBSD-current/man1/tmux.1).

<br/>

* To turn on tmux
```bash
tmux
```

<br/>

### **Before entering any command below:**


 1. ### Press **<span style="color:#E34F1B">CTRL+B</span>** on your keyboard.
 2. ### Release the keys. 
 3. ### Then type the symbol for the respective operation desired.

 ### **This process will need to be re-completed for every operation called.**

<br/>

* Horrizontal split of windows
```
"
```

* Vertical split of windows
```
%
```

* Move to different window
```
Use the arrow keys to go left, right, up and down
```

* To exit a window
```
exit
```