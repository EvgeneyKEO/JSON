### :large_orange_diamond: JSON
 _________________________________________________________________________________
 4. Создать внешний репозиторий c названием JSON            - [JSON](https://github.com/EvgeneyKEO/JSON.git)

 5. Клонировать репозиторий JSON на локальный компьютер     - `git clone git@github.com:EvgeneyKEO/JSON.git`

 6. Внутри локального JSON создать файл “new.json”          - `touch new.json`

 7. Добавить файл под гит.                                  - `git add .`

 8. Закоммитить файл.                                       - `git commit -m "add new file"`

 9. Отправить файл на внешний GitHub репозиторий.           - `git push`

 10. Отредактировать содержание файла “new.json” - написать 
информацию о себе (ФИО, возраст, количество домашних
животных, будущая желаемая зарплата).
Всё написать в формате JSON.                                - `vim new.json ---> input data ---> esc ---> enter ":wq"`
                                                               
 11. Отправить изменения на внешний репозиторий.            - `git commit -am "update file" && git push`
 							       [new.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/new.json)

 12. Создать файл preferences.json                          - `touch preferences.json`

 13. В файл preferences.json добавить информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, любимая еда,
любимое время года, сторона которую хотели бы посетить) 
в формате JSON.                                             - `vim preferences.json ---> input data ---> esc ---> enter ":wq"`

 14. Создать файл skills.json добавить информацию о скиллах
которые будут изучены на курсе в формате JSON               - `cat >> skills.json ---> input data ---> ctrl + c`

 15. Отправить сразу 2 файла на внешний репозиторий.        - `git add . && git commit -m "add new file" && git push` [preferences.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/bug_report.json) [skills.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/skills.json)

 16. На веб интерфейсе создать файл bug_report.json.        - `Add file --> Create new file --> Name: bug_report.json`

 17. Сделать Commit changes (сохранить) 
изменения на веб интерфейсе.				    - `Commit new file`  [bug_report.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/skills.json)

 18. На веб интерфейсе модифицировать файл 
bug_report.json, добавить баг репорт в формате JSON.        - `Choose bug_report.json --> Edit this file` 

 19. Сделать Commit changes (сохранить) изменения
на веб интерфейсе.					    - `Commit changes`

 20. Синхронизировать внешний и локальный репозиторий JSON  - `git pull`
