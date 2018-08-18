## GTK+ Hello Dialog with Buttons

Install GTK+ for [Windows](https://www.gtk.org/download/windows.php)

### Bullding 

gcc -o hello.exe hello.c -mwindows `pkg-config --cflags --libs gtk+-3.0`

move the exeecutable to the msys bin directory. With the GTK+ libaray then execute the hello.exe COFF/PE binary.