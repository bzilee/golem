<img src="./images/bg.jpg" width="1500"/>

# GOLEM

Build your Python's portable executable app on Windows/Linux/Mac in One Click !

## Purpose

I was searching a way to learn well how to use a simple native GUI in python, i choose tkinter for that, and i was wondering how to easily generate my portables application in one click !

## Quick demo

This is a quick demo of generating a portable app using Golem

## Requirements

- Python (3.x recommended)
- PyInstaller (3.5)

## How to install

You just have to run this command :
```shell script
pip3 install -r requirements.txt
```

## How to use

### With the CLI

You can run it like this:
```shell script
python3 cli.py -p ./test_app -t py -n golem_test_app
```
And your application will be generated in the path of your project in the directory : `./dist/`.

This is the usage
```shell script
usage: cli.py [-h] -p PATH -t TYPE [-n NAME]

optional arguments:
  -h, --help            show this help message and exit
  -p PATH, --path PATH  The path of the code/project.
  -t TYPE, --type TYPE  The type of the code/project.
  -n NAME, --name NAME  The name of the code/project.
```

<img src="./images/cli_demo.gif" />


### With the GUI

You can run it like this:
```shell script
python3 gui.py
```
After following steps in the GUI, your application will be generated in the path of your project in the directory : `./dist/`.

Note: The GUI is based on tkinter, make sure to have it installed in your python env, in most case it came directly when installing python.

<img src="./images/gui_demo.gif" />

## MIT LICENSE

## Author

- Sanix-darker