# Allegro v4.2.3

This is the allegro source with the sb-patch applied. all compiled
binaries are included.

### Usage

- download [latest release](https://github.com/leegibsonhoward/allegro-v432/releases/tag/v4.2.3-r1).
- extract .zip, rename folder to `allegro`  
- move folder to c:\allegro  

Thats it! No need to compile since all binaries, examples, tools, and demo are included in zip.

### Compilation

If you would like to rebuild allegro, I would suggest not to do it on dosbox.
It works, but when I compiled it on dosbox the process took about an hour to
complete. Whereas if you simply create a win9x virtual machine the
compilation process will only take a few minutes.

`cd c:\allegro`    
`make`  
`make install`  

if you want to clean to project run:  
`make  clean`  