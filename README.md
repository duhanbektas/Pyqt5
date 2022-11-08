# Pyqt5

Pyqt5 examples for desktop app design / functionality. (w/QT Designer)

Document: https://doc.qt.io/qtforpython/


PYQT5;

pip install PyQt5
pip install pyqt5-tools (you can obtain qt-designer in tools, or you can download it from the web)


Start with: import PyQt5

qt designer -> you can design the ui from here but you give functionality to it from your app, (You can specify object names for elements)

After you save your design, it will be saved as xml file, you need to alter it to py file

On your IDE terminal, RUN:
pyuic5 MainWindow.ui -o MainWindow.py

This will do the work.

Note: Try working with database tables and editing the entries on List or Table view in QT designer (Suggestion)
