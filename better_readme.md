## Getting Started

After creating and activating a virutal env, run these commands to get setup:
```
pip install pyqt5
pip install lxml
pyrcc5 -o libs/resources.py resources.qrc
```
Then finally run:
```
labelImg.py
```

## To Do
- easy swap class colors
- hotkey to remove drag and click corner underneath
- undo
- dark mode

# Done
- Several custom colors, changeable in constants.py file
- toggle vertices on/off in view tab