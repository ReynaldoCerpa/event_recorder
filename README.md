#### Package app into executable for Windows
Run in the root of the project and change path accordingly (path points to pip packages, run inside virtual env)
```bash
pyinstaller --onefile --paths C:\Users\Rey\Documents\code\event_recorder\venv\Lib\site-packages --name 'Event recorder' --noconsole src/main.py
```

> ### Tip
> 
> Run ```./dist/{app name} ``` to see possible error logs
