Поддержка BEM-tools из контекстного меню IntelliJ IDEA
========
Возможности:
---------------------------
 * Создание уровня переопределения
 * Создание блока
 * Создание модификатора блока
 * Создание элемента
 * Добавление файла с технологией для уже существующего блока

Как выглядит:
---------------------------
![Как выглядит](https://github.com/banzalik/bemidea-et/raw/master/screen.png)

Использование:
---------------------------
Инструмент используется на проектных папках.

Во всех случаях необходимо ввести имя блока|элемента|технологии.

При создании модификатора, необходимо указать не только имя модификатора, но и его значение:

```имя-модификатора -v значение-модификтора```

Установка
---------------------------
Необходимо убедиться, что пути к node.js и bem правильные:

```which node

/usr/local/bin/node
```

```which bem

/usr/local/bin/bem
```

Если пути совпадают с теми, что выше, то достаточно скопировать файл BEM.xml в директории:

 * для WebStorm\PhpStorm: ~/Library/Preferences/WebIDE10/tools/
 * для IntelliJ IDEA: ~/Library/Preferences/IntelliJIdea10/tools/

Если пути не совпадают, то, необходимо в файле BEM.xml актуализировать правильные пути до приложений.