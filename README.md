_________________________________________________________________________________
 ### GIT file JSON
 _________________________________________________________________________________
 1. Создать внешний репозиторий c названием JSON            - **[JSON](https://github.com/EvgeneyKEO/JSON.git)**

 2. Клонировать репозиторий JSON на локальный компьютер     - `git clone git@github.com:EvgeneyKEO/JSON.git`

 3. Внутри локального JSON создать файл “new.json”          - `touch new.json`

 4. Добавить файл под гит.                                  - `git add .`

 5. Закоммитить файл.                                       - `git commit -m "add new file"`

 6. Отправить файл на внешний GitHub репозиторий.           - `git push`

 7. Отредактировать содержание файла “new.json” - написать 
информацию о себе (ФИО, возраст, количество домашних
животных, будущая желаемая зарплата).
Всё написать в формате JSON.                                - ```vim new.json после нажать на i ввести информацию о себе в формате JSON
                                                               {"FIO":"Kandyba Evgeney Olegovich";"age":24;"pets":1;"salary":2000}
                                                               после окончания ввода нажать Esc ввести :wq
                                                              ```
                                                               

 8. Отправить изменения на внешний репозиторий.            - ```git add . 
                                                                git commit -m "update new.json" 
                                                                git push
                                                              ```
 
 9. Создать файл preferences.json                          - `touch preferences.json`

 10. В файл preferences.json добавить информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, любимая еда,
любимое время года, сторона которую хотели бы посетить) 
в формате JSON.                                             - ```vim preferences.json после нажать на i ввести информацию о себе в формате JSON                                                                                          {"movie":"1+1";"series":"Peaky_Blinders";"food":"salat";"season":"winter";"country":"USA"}
                                                                 после окончания ввода нажать Esc ввести :wq
                                                              ```

 11. Создать файл skills.json добавить информацию о скиллах
которые будут изучены на курсе в формате JSON               - ```vim skills.json после нажать на i ввести информацию о себе в формате JSON
                                                                {"instruments":"postman","SQL","Jmeter","Python","Terminal","Android
                                                                Studio","XCode","DevTools","Charles","Fiddler","GitBash"}
                                                                после окончания ввода нажать Esc ввести :wq
                                                              ```

 12. Отправить сразу 2 файла на внешний репозиторий.        - ```git add .
                                                                 git commit -m "add two new files: new preferences.json skills.json"
                                                                 git push
                                                              ```


 13. На веб интерфейсе создать файл bug_report.json.        - [bug_report.json](https://github.com/EvgeneyKEO/JSON/blob/62d356725170363a1826bcee6f123ea125e261fe/bug_report.json)


 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.


 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.


 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.


 17. Синхронизировать внешний и локальный репозиторий JSON - `git pull`
