# PySide6_calculator

## Utils
- [Qt Doc](https://doc.qt.io/qtforpython-6/)
- [App icon](https://www.flaticon.com/br/icone-gratis/matematica_3965108?term=matem%C3%A1tica&page=1&position=1&origin=search&related_id=3965108)
- [PyQt QSS](https://doc.qt.io/qtforpython-6/tutorials/basictutorial/widgetstyling.html)
- [Dangers of eval()](https://realpython.com/python-eval-function/#minimizing-the-security-issues-of-eval)  
<img src="imgs/eval_issue.png" alt="eval issue example" style="width: 250px; height: 300px;"/>
- [Py Installer Doc](https://pyinstaller.org/en/stable/)

## Py Installer Command Used
```shell
(venv) PS D:\projects_work\python_apps\PySide6_calculator> pyinstaller --name="Sapucaia Calculadora" --noconfirm --onefile --add-data="D:\projects_work\python_apps\PySide6_calculator\imgs\:imgs\" --add-data="D:\projects_work\python_apps\PySide6_calculator\src\:src\" --add-data="D:\projects_work\python_apps\PySide6_calculator\style\:style\" --icon="D:\projects_work\python_apps\PySide6_calculator\imgs\kerismaker_icon.png" --noconsole --clean --log-level=WARN --distpath="sapucaia_app\dist" --workpath="sapucaia_app\build" --specpath="sapucaia_app\" main.py
```

## sapucaia_app
This app was built on windows. For other operating systems, rebuild it!
For that, look at [Py Installer Doc](https://pyinstaller.org/en/stable/).