# READ ME
 
## dwm-exitscript-6.2

dwm-exitscript-6.2 contains a patch for dwm 6.2 build, that adds the spawnandquit() function; which executes a script and then if the script was executed succefully; it quits (cleanly??) the DWM by setting the running variable equal to 0. See the config.def.h file where a commented line is added which contains the proposed way to use it.
