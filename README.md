### Список необходимых программ для установки EXPO ide

* Dr.Web remover
* Git
* Node JS
* VS source code editor
* Expo XDE

### Шаги по установке

1.  В первую очередь удалите Dr.web, введите код для удаление. Отвечаем "нет" на вопрос "Перезагрузить компьютер сейчас?".
2.  Установите Git.
3.  Установите NodeJS.
4.  Установите VS Code.
5.  Установите Expo XDE.

### Настройка переменных сред

1.  Заходим в свойство компьютера. Выбираем "Дополнительные парамаетры системы".

![SettingsTool](https://github.com/021NIS/ToolsInstallation/blob/master/screenshots/first.png)

2.  Входим в переменные среды.

    ![EnvVar](https://github.com/021NIS/ToolsInstallation/blob/master/screenshots/second.png)
    
    2.1. При присуствии переменной "PATH", выбираем "Изменить".

    2.2. При отсуствии переменной "PATH", выбираем "Создать" и вводим слово "PATH" в окошко "Имя переменной".
    
    ![SettingsTool](https://github.com/021NIS/ToolsInstallation/blob/master/screenshots/third.png)

3.  Копируем путь к программам NodeJS, Git.

    3.1. NodeJs - пример! => `C:\ProgramFiles\nodejs`

    3.2. Git - (выбираем путь до cmd!) пример! => `C:\ProgramFiles\Git\cmd`

    3.3. Копируем и указываем пути в "Значения переменной". (используется знак ; между путями)
    
    ![SettingsTool](https://github.com/021NIS/ToolsInstallation/blob/master/screenshots/forth.png)

    3.4. Нажимаем "Ок" и выходим из свойств.

### Проверка успешности уствновки

1.  Входим в терминал.
2.  Выполняем комманду "node --version", вы должны увидеть версию node в качестве ответа.
3.  Выполняем комманду "npm --version", вы должны увидеть версию npm в качестве ответа.
4.  Выполняем комманду "git --version", вы должны увидеть версию git в качестве ответа.

![SettingsTool](https://github.com/021NIS/ToolsInstallation/blob/master/screenshots/fifth.png)
