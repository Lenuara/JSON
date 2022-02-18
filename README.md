# JSON
19. Создать внешний репозиторий c названием JSON.  
    * Войти в свой профиль на https://github.com/ 
    * Зайти в раздел Repositories
    * Нажать кнопку New 
    * Указать:
       * Repository name "JSON"
       * Radiobutton "Private"
       * Checkbox "Add a README file"
    * Репозиторий [JSON](https://github.com/Lenuara/JSON) создан, его имя появилось в списке репозиториев 

20. Клонировать репозиторий JSON на локальный компьютер.  
   `cd ~/LearningQA/LearnGIT/`  
   `git clone https://github.com/Lenuara/JSON.git`
21. Внутри локального JSON создать файл “new.json”.  
   `cd JSON`  
   `touch new.json`
22. Добавить файл под гит.  
   `git add new.json`
23. Закоммитить файл.  
   `git commit -m "Add new.json"`
24. Отправить файл на внешний GitHub репозиторий.  
   `git push`
25. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
   `vim new.json`
26. Отправить изменения на внешний репозиторий.  
   `git add new.json`  
   `git commit -m "Edited new.json"`  
   `git push`
27. Создать файл preferences.json  
   `touch preferences.json`
28. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
   `vim preferences.json`
29. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
   `vim sklls.json` 
30. Отправить сразу 2 файла на внешний репозиторий.  
   `git add . && git commit -m "Add preferences.json and sklls.json"`  
   `git push`
31. На веб интерфейсе создать файл bug_report.json.  
    На вкладке репозитория нажать Add file -> Create new file -> Name your file... -> bug_report.json
32. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
    Нажатием на кнопку Commit new file сохранить изменения
33. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
    Зайти в файл bug_report.json  
    Нажать пиктограмму Edit this file
34. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
    Нажать Commit changes  
35. Синхронизировать внешний и локальный репозиторий JSON  
   `git pull`
