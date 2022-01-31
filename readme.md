# Silent Crash with orjson==3.6.6
Python Version: 3.10.1  
Platform: Windows 10  

Steps to reproduce:
- Run `poetry install` or install `orjson==3.6.6` via pip
- Install pyinstaller via `pip install pyinstaller`
- Run `pyinstaller main.py --onefile`

Executable `dist/main.exe` would silently crash when executed.


