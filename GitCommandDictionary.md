# **СЛОВАРЬ КОМАНД GIT**

> ### После установки необходимо представиться ситеме контроля версий. Это нужно выполнить только один раз, и GIT запомнит Вас. Для этого нужно ввести в терминале 2 команды: 

*   # git config --global user.name "Твоё имя латинскими буквами"
*   # git config --global user.name "your@email.com"
<br/><br/>
## КОМАНДЫ

* # `git --version` - указывает актуальную версию GIT

<a href="https://imgbb.com/"><img src="https://i.ibb.co/RQFhd5m/version.jpg" alt="version" border="0"></a>
<br/><br/>

* # `git init`      - указываем папку в которой необходимо отследить изменения (Создаётся скрытая папка .git)

<a href="https://ibb.co/8cfGtmp"><img src="https://i.ibb.co/3zjVQTq/init.jpg" alt="init" border="0"></a>

<br/><br/>
* # `git add` - добавляет содержимое для последующего commit
>Клавиша TAB - позволяет быстро переходить из разных директорий. Пример: gitt add .\hello_world.md


<a href="https://ibb.co/4F6hdQ6"><img src="https://i.ibb.co/wd95sv9/add.jpg" alt="add" border="0"></a>

<br/><br/>
* # `git commit` - команда фиксирует и сохраняет данные в индексе с помощью git add
>Пример: git commit -m "YOUR COMMENT"
 (Комментарий необходим для того, чтобы все коллеги участвующие в проекте могли иметь маркер деятельности)


 <a href="https://ibb.co/Bj93NGf"><img src="https://i.ibb.co/WFL5t0H/commit.jpg" alt="commit" border="0"></a>
 
 <br/><br/>


* # `git log` - показывает журнал изменений
>Укажет все версии файла, позволяет увидеть сколько было изменений и комментарии к сохранениям.

<a href="https://ibb.co/4VdrsKx"><img src="https://i.ibb.co/z4Jv8Qw/log.jpg" alt="log" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />
<br/><br/>

* # `git checkout` - команда позволяет переключаться меджу версиями
> Для работы необходиомо указать интересующий коммит, и выбрать тот, в котром желаем остаться. При момощи команды git checkout master


<a href="https://imgbb.com/"><img src="https://i.ibb.co/2SM2Dc0/checkout.jpg" alt="checkout" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'></a><br />

<br/><br/>
* # `git diff` - показ разницы между текущим файлом и сохраненным
>  Перед переключением версии файла в GIT используй команду git log, чтобы увидеть все сохранения

<a href="https://imgbb.com/"><img src="https://i.ibb.co/fCVqtX1/diff.jpg" alt="diff" border="0"></a>
<br/><br/>

* # `git branch` - команда выводит все ветки репозитория
<a href="https://ibb.co/Sfs37Z9"><img src="https://i.ibb.co/tLmJP1W/branch.jpg" alt="branch" border="0"></a>
<br/><br/>

* # `git branch (new branch name)` - команда создаёт новую ветку с именем 
<a href="https://ibb.co/GWTFvdD"><img src="https://i.ibb.co/Cb2W5wy/git-branch-name.jpg" alt="git-branch-name" border="0"></a>
<br/><br/>

* # `git branch -d (branch name)` - команда удаляет ненужную ветку
<a href="https://ibb.co/gzNkHRP"><img src="https://i.ibb.co/72Ps81R/git-branch-d.jpg" alt="git-branch-d" border="0"></a>
 <br/><br/>
 
* # `git log --graph` - команда выводит список commit в виде древа
<a href="https://ibb.co/Dfd7YWZ"><img src="https://i.ibb.co/k2ZhJBt/git-log-graph.jpg" alt="git-log-graph" border="0"></a>

### ВСПОМОГАТЕЛЬНЫЕ КОМАНДЫ ТЕРМИНАЛА

* # `q` - выход
* # `CTRL + S` - сохраннение информации перед git unit
* # `clear` - отчистить командную строку

---
// Copyright (C) 2015, 2016, 2017 Dapphub

// This program is free software: you can redistribute it and/or modify
// it under the terms of the GNU General Public License as published by
// the Free Software Foundation, either version 3 of the License, or
// (at your option) any later version.

// This program is distributed in the hope that it will be useful,
// but WITHOUT ANY WARRANTY; without even the implied warranty of
// MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
// GNU General Public License for more details.

// You should have received a copy of the GNU General Public License
// along with this program.  If not, see <http://www.gnu.org/licenses/>.

pragma solidity >=0.4.22 <0.6;

contract WETH9 {
    string public name     = "Wrapped Ether";
    string public symbol   = "WETH";
    uint8  public decimals = 18;

    event  Approval(address indexed src, address indexed guy, uint wad);
    event  Transfer(address indexed src, address indexed dst, uint wad);
    event  Deposit(address indexed dst, uint wad);


# **ИНТЕРЕСНЫЕ ССЫЛКИ И СТАТЬИ ПО НАСТРОЙКЕ GIT**

[GitHub: настройка и первая публикация проекта](#https://gb.ru/posts/github-nastrojka-i-pervaya-publikaciya-proekta)

[Как устроен и работает GitHub](#https://gb.ru/posts/kak-ustroen-i-rabotaet-github)

[GitHub: работа с ветками и коммитами](#https://gb.ru/posts/github-rabota-s-vetkami-i-kommitami)

[Установщик](#https://githowto.com/ru)

[Сcылка на бесплатный базовый курс GIT](#https://gb.ru/chapters/7831)