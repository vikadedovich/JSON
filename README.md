### GIT Homework 1
### JSON 

 1. Создать внешний репозиторий c названием JSON: 

    `New repository, Json ,Create repository.`
    
 3. Клонировать репозиторий JSON на локальный компьютер: 
    
    `git clone https://github.com/vikikiller/JSON.git`
    
 4. Внутри локального JSON создать файл “new.json”: 

    `cd JSON && touch new.json`
    
 6. Добавить файл под гит: 

    `git add new.json`
    
 8. Закоммитить файл:

    `git commit -m "add new.json"`
    
 10. Отправить файл на внешний GitHub репозиторий: 

     `git push`
    
 12. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая            желаемая зарплата). Всё написать в формате JSON:

     `cat >> new.json`
    
 14. Отправить изменения на внешний репозиторий:

     `git add new.json && git commit -m "update new.json" && git push`
    
 16. Создать файл preferences.json: 

     `touch preference.json`
    
 18. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года,       сторона которую хотели бы посетить) в   формате JSON: 

     `cat >> preference.json`
    
 19. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON: 

     `cat > skils.json`
    
 20. Отправить сразу 2 файла на внешний репозиторий: 

     `git add . && git commit -m " add preference.json skills.json " && git push`
    
 21. На веб интерфейсе создать файл bug_report.json:

     `Add new file` 
    
 22. Сделать Commit changes (сохранить) изменения на веб интерфейсе:

     `Commit new file`
    
 23. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON: 

     `Edit this file`
    
 24. Сделать Commit changes (сохранить) изменения на веб интерфейсе:

     `Commit changes`
    
 25. Синхронизировать внешний и локальный репозиторий JSON:

     `git pull`


