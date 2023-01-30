# paintingApp-gtk4

## Compiling

To Compile navigate extract zip to desktop, and open a command prompt/terminal window in this directory
compile with:
    gcc $( pkg-config --cflags gtk4 ) -o polish polish.c $( pkg-config --libs gtk4)
run with:
    ./polish
    
    
    
## Explanation


### paint
works automatically, when colour dropper is active, will not paint surface

### colour dropper

Gets rGB value of pixel
Draws red lines to pixel
Saves rib value to draw with

### Save
saves the surface as a png to the folder that polish.c is saved to
