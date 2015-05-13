# tknotify
tkinter notification similar to notifysend (linux)


# tknotify #

TkNotify its a library and command line program (Windows and Linux) to show a popup message in your system.

To run it you must have python and tck/tk configured.

To use it like program type in terminal:

```sh
./tknotify.py -t "My Message"
```
To see list of commands:
```sh
./tknotify.py --help
```

In Windows you must rename the file to "tknotify.pyw" to not show terminal.

In Linux you can rename the file to "tknotify" (without python extension) and must
set permissions to call it:

```sh
chmod +x ./tknotify
```

To use like library you can make this:

```python
import tknotify
my_main_window = Tk()
# Here I do many things
if (this and that):
    tknotify.show(title="My Title")
my_main_window.mainloop()
```

**If you want use tknotify like library you must set extension to *.py.**

##Contact##
Mail-me: cptx032 arroba gmail dot com
