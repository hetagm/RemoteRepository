# **СЛОВАРЬ КОМАНД GIT**

> ### После установки необходимо представиться ситеме контроля версий. Это нужно выполнить только один раз, и GIT запомнит Вас. Для этого нужно ввести в терминале 2 команды: 

*   # git config --global user.name "Твоё имя латинскими буквами"
*   # git config --global user.name "your@email.com"

## КОМАНДЫ

* # `git --version` - указывает актуальную версию GIT
* # `git init`      - указываем папку в которой необходимо отследить изменения (Создаётся скрытая папка .git)

<a href="https://ibb.co/8cfGtmp"><img src="https://i.ibb.co/3zjVQTq/init.jpg" alt="init" border="0"></a>


* # `git add` - добавляет содержимое для последующего commit
>Клавиша TAB - позволяет быстро переходить из разных директорий. Пример: gitt add .\hello_world.md


<a href="https://ibb.co/4F6hdQ6"><img src="https://i.ibb.co/wd95sv9/add.jpg" alt="add" border="0"></a>


* # `git commit` - команда фиксирует и сохраняет данные в индексе с помощью git add
>Пример: git commit -m "YOUR COMMENT"
 (Комментарий необходим для того, чтобы все коллеги участвующие в проекте могли иметь маркер деятельности)


 <a href="https://ibb.co/Bj93NGf"><img src="https://i.ibb.co/WFL5t0H/commit.jpg" alt="commit" border="0"></a>

* # `git log` - показывает журнал изменений
>Укажет все версии файла, позволяет увидеть сколько было изменений и комментарии к сохранениям.

<a href="https://ibb.co/4VdrsKx"><img src="https://i.ibb.co/z4Jv8Qw/log.jpg" alt="log" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />

* # `git checkout` - команда позволяет переключаться меджу версиями
> Для работы необходиомо указать интересующий коммит, и выбрать тот, в котром желаем остаться. При момощи команды git checkout master


<a href="https://imgbb.com/"><img src="https://i.ibb.co/2SM2Dc0/checkout.jpg" alt="checkout" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />

* # `git diff` - показ разницы между текущим файлом и сохраненным
>  Перед переключением версии файла в GIT используй команду git log, чтобы увидеть все сохранения

<a href="https://imgbb.com/"><img src="https://i.ibb.co/fCVqtX1/diff.jpg" alt="diff" border="0"></a>

### ВСПОМОГАТЕЛЬНЫЕ КОМАНДЫ ТЕРМИНАЛА

* # `q` - выход
* # `CTRL + S` - сохраннение информации перед git unit
* # `clear` - отчистить командную строку
