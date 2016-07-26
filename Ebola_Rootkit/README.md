#"Ebola" Rootkit
This is my unfinished rootkit for CC (although everything already written should work without any problems, I still have lots of ideas, but I'm not interested in CC anymore.)
##How to install
You can rewrite these files to CC, or download them (if you have HTTP api enabled) from your CC Computer.
Put both files ("startup" and "infstartup") to a new floppy disk, insert to your victim's PC, reboot and let the magic happen =)
**If the version of CraftOS on your victim's PC isn't 1.5, don't forget to change it!**
##Unfinished stuff
If you want to keep on developing "Ebola", here are some things #TODO

- Show directories before the ">"

If you change directory (cd command), unlike in original CraftOS Console, the path won't appear before the ">" symbol
Let's cd into folder "rom"..
```
> cd rom
```
Normal CraftOS' console will display
```
rom> 
```
But "Ebola"'s will still display
```
> 
```

- Own ls output (ls, list, dir)

Right now, these commands are blocked and won't display anything if written.
But it would be really cool if it displayed all files except for "Ebola"'s ones!
And ofcourse it'd have to change the "startup2" to "startup" (if it exists) and "startup3" to "startup"

- Modified text editor

If you enter
```
> edit startup
```
"Ebola" will launch
```
> edit startup2
```
instead. But after saving the edited file, the file editor will say
```
Saved to startup2
```
which some users can notice =)
