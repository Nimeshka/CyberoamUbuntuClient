# Cyberoam Desktop client for Ubuntu

This is not an official or a serious project. It contains a few simple scripts I wrote with Python QT library and bash to save my time from having to open the Cyberoam web client in the browser everyday. (Cyberoam doesn't have an official desktop client for Ubuntu). 

Why is this in Github? 
It's here not because I wanted to share it as a project; but only as a backup for myself (so I can clone it anywhere when I need). If you really want to use this, you might need to solve dependencies, change a few lines in the code.

How to run?
Assuming you have Python and the other dependencies installed, you can run the following commands to install this:

1. Set the right address to access your Cyberoam web client in the `cyberoam` file.

2. Set the excecute permissions on the install script.

```chmod +x install```

3. run the install script.

```sudo ./install```

What this does? 
It copies the included scripts to /opt/, /usr/bin/ and Ubuntu autostart directories. This will most probably work only in Ubuntu.

Once you install, it will start automatically on the startup, and you can also use the `cyberoam` command from a terminal to start it.
