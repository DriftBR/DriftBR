# DriftBR
An open source browser based on the PyQtWebEngine and PyQt5 framework 

![GitHub ReadMe](https://github.com/user-attachments/assets/948fe57a-da9d-4bff-a562-531e9c930d1f)

# [DOWNLOAD](https://github.com/DriftBR/DriftBR/releases)

> New additions:

* macOS-style UI (magic)
* birbs

> Planned features

* Smooth scrolling
* YT videos higher than 360p
* Not give up after V3

> TEAM MEMBERS AND ALL COMING SOON ON THE DRIFTBR WEBSITE

### ***FEEL FREE TO CONTRIBUTE IF YOU KNOW PYTHON AND PYQT***

> [!IMPORTANT]  
> This app might soon become Mac-only (Apple Silicon) due to the fact that the owner is getting a Mac soon and will make it natively on Xcode without the hell that Python is. 

> [!NOTE]
> Mac and Linux users, you do your bit by contributing and adding build instructions

# Building
1) Make sure you have Python 3.12.4 installed with "pip"
2) Download code as zip and extract
3) Open CMD/Terminal and navigate to extracted zip directory and run command `pip install -r requirements.txt`
4) Run the script to make sure everything works. Once it does, here's the building bit:
5) Run `pip install pyinstaller`
6) In the same directory, run ```pyinstaller --noconfirm --onefile --windowed --icon "icon.ico" --name "drift" --add-data "Assets;Assets/"  ""```
7) Navigate to the brand new "dist" folder
8) All done
