# PySide6_calculator

## Utils
- [Qt Doc](https://doc.qt.io/qtforpython-6/)
- [App icon](https://www.flaticon.com/br/icone-gratis/matematica_3965108?term=matem%C3%A1tica&page=1&position=1&origin=search&related_id=3965108)
- [PyQt QSS](https://doc.qt.io/qtforpython-6/tutorials/basictutorial/widgetstyling.html)
- [Dangers of eval()](https://realpython.com/python-eval-function/#minimizing-the-security-issues-of-eval) 
- [Py Installer Doc](https://pyinstaller.org/en/stable/)

## Dangers of eval

<img src="imgs/eval_issue.png" alt="eval issue example" style="width: 250px; height: 300px;"/>

## Py Installer Command Used
```shell
pyinstaller --name="Sapucaia Calculadora" --noconfirm --onefile --add-data="..\imgs\:imgs\" --add-data="..\src\:src\" --add-data="..\style\:style\" --icon="..\imgs\kerismaker_icon.png" --noconsole --clean --log-level=WARN --distpath="sapucaia_app\dist" --workpath="sapucaia_app\build" --specpath="sapucaia_app\" main.py
```

## sapucaia_app
This app was built on windows. For other operating systems, rebuild it!
For that, look at [Py Installer Doc](https://pyinstaller.org/en/stable/).

[app | google drive](https://drive.google.com/drive/folders/1RzPhTobMfQ6KEdy2kLqBu2wWkA1tFMYa?usp=sharing)