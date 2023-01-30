# paintingApp-gtk4

## Compiling

To Compile navigate extract zip to desktop, and open a command prompt/terminal window in this directory
compile with:
    gcc $( pkg-config --cflags gtk4 ) -o polish polish.c $( pkg-config --libs gtk4)
run with:
    ./polish
