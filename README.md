# TXT

## Homework to the first GIT lesson TXT part - Vadim Ksendzov's course

### 1. Создать внешний репозиторий c названием TXT

    Repositories >> New >> TXT >> Create repository 

### 2. Клонировать репозиторий TXT на локальный компьютер

    TXT >> Code >> Copy HTTPS

    $ git clone https://github.com/xenia513/TXT.git

### 3. Внутри локального TXT создать файл “new.txt”

    $ touch new.txt

### 4. Добавить файл под гит

    $ git add new.txt

### 5. Закоммитить файл

    $ git commit -m "created new.txt"

### 6. Отправить файл на внешний GitHub репозиторий

    $ git push

### 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT

    $ vim new.txt

Эта команда открывает встроенный редактор текста, для начала редактирования необходимо нажать `i` и ввести текст:
    
    ФИО - Киселева Ксения Сергеевна,
    возраст - 30,
    количество домашних животных - 1 китяо,
    будущая желаемая зарплата - 80тыс.руб

После завершения редактирования нажимаем `Esc` и `:wq` для сохранения внесенных изменений и выхода из режима редактора.

### 8. Отправить изменения на внешний репозиторий

    $ git commit -a -m "added text"

### 9. Создать файл preferences.txt

    $ cat > preferences.txt
    
После ввода этой команды открывается поле ввода текста для записи в файл, поэтому мы сразу же приступаем к выполнению следующего задания.

### 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, стрaна, которую хотели бы посетить) в формате TXT

    Любимый фильм - Начало, 
    любимый сериал - Ты отстой,
    любимая еда - индийская кухня,
    любимое время года - лето!
    страна, которую хотела бы посетить, - Шри-Ланка

Для завершения редактирования нажимаем `Enter` и `Ctrl+C`

### 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

    $ cat > skills.txt

    Bash, Postman, GIT, client-server architecture, devTools, Charles Proxy, Fiddler, Andriod Studio

### 12. Сделать коммит в одну строку

    $ git add . && git commit -m "added preferences.txt and skills.txt"

### 13. Отправить сразу 2 файла на внешний репозиторий

    $ git push

### 14. На веб-интерфейсе создать файл bugReport.txt

    TXT >> Add file >> Create new file >> bugReport.txt

### 15. Сделать Commit changes (сохранить) изменения на веб-интерфейсе

    Commit new file 

### 16. На веб-интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT

    TXT >> bugReport.txt >> Edit this file

Кнопка редактирования файла выглядит так:

![Edit this file button](https://docs.github.com/assets/cb-47677/mw-1440/images/help/repository/edit-file-edit-button.webp)

Вводим текст: 

    ID - 0001
    Severity - Trivial
    Environment - Win 7 Chrome 109 IPhone 11 IOS 16.4.1
    Title - The link [Share price] redirects to the english page from Trading Course 1, section 2 when AR, NL, VI, TH or ZN is chosen
    Precondition - -
    Steps - 
      1: Navigate to capital.com,
      2: Hover over the [Education] menu section,
      3: Click the [Trading сourses] menu item,
      4: Click the [Who are the main market players?] row in the Introduction to Financial Markets box,
      5: Select AR, NL, VI, TH or ZN language,
      6: Scroll to the second to the last paragraph,
      7: Click the link [Share price]
    Postcondition - -
    Expected Result - The link [Indices]  redirects to the page translated into chosen language
    Actual Result - The link [Indices] redirects to the english page 
    Attachment - ~Link~
    Author - @xenia513

### 17. Сделать Commit changes (сохранить) изменения на веб-интерфейсе

    Commit changes

### 18. Синхронизировать внешний и локальный репозиторий TXT

    $ git pull
