# st - simple terminal (Pavel's build)

st is a simple terminal emulator for X which sucks less.

All used patches in this build you can find at the patches directory. All of them I took from the [suckless.org](https://suckless.org).
Some settings I took from the [Luke's repository](https://github.com/LukeSmithxyz). I strongly recommend to look at his github he's doing a great job.


# Requirements
In order to build st you need the Xlib header files.


# Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

```
make clean install
```

# Running st

If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

```
tic -sx st.info
```

See the man page for additional details.

# Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

