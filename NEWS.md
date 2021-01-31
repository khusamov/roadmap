Новинки
=======

Удаленная разработка при помощи Visual Studio Code
--------------------------------------------------

### Remote SSH

Первый вариант это [использование Visual Studio Code для удаленной разработки][remote-article] 
с помощью плагина [Remote SSH][remote]. Сама среда разработки устанавливается на локальном компьютере.
А файлы находятся на удаленном. Также на локальном компе будет доступен терминал.

### Cloud IDE ala Visual Studio Code

Второй вариант это использовать облачные варианты Visual Studio Code:
1. [Code Server][code-server] Run VS Code on any machine anywhere and access it in the browser.
2. [Eclipse Theia][theia] Cloud & Desktop IDE Framework

Кстати, для этих IDE нужно ставить на локальном компьютере шрифт FiraCode.

### Gitpod

Третий вариант это проект [Gitpod][gitpod]. Это облачная IDE для Github.
Вариант похоже временный, потому что Github готовит свою облачную IDE.
С помощью плагина к браузеру можно добавить специальную кнопку ко всем своим репозиториям, для загрузки
репозитория в эту IDE.

Надо не забывать, что рабочее пространство Gitpod на бесплатном тарифе существует 14 дней. После этого уничтожается. 
То есть перед завершением работы над кодом надо не забывать про `git push --all`.

### Github Codespaces

Четвертый вариант дождаться [облачную IDE для Github][codespaces].

Создание своей IDE
------------------

Проект [Eclipse Theia][theia] предлагает сразу создавать свою IDE. Но пока точно не ясно что лучше.
[Code Server][code-server] утверждает что он лучше Theia (например магазин расширений содержит больше расширений).




[remote]: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh
[remote-article]: https://www.digitalocean.com/community/tutorials/how-to-use-visual-studio-code-for-remote-development-via-the-remote-ssh-plugin-ru
[code-server]: https://github.com/cdr/code-server
[theia]: https://github.com/eclipse-theia/theia
[gitpod]: https://gitpod.io/
[codespaces]: https://github.com/features/codespaces