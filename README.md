### :large_orange_diamond: JSON
 _________________________________________________________________________________
 1. Создать внешний репозиторий c названием JSON            - [JSON](https://github.com/EvgeneyKEO/JSON.git)

 2. Клонировать репозиторий JSON на локальный компьютер     - `git clone git@github.com:EvgeneyKEO/JSON.git`

 3. Внутри локального JSON создать файл “new.json”          - `touch new.json`

 4. Добавить файл под гит.                                  - `git add .`

 5. Закоммитить файл.                                       - `git commit -m "add new file"`

 6. Отправить файл на внешний GitHub репозиторий.           - `git push`

 7. Отредактировать содержание файла “new.json” - написать 
информацию о себе (ФИО, возраст, количество домашних
животных, будущая желаемая зарплата).
Всё написать в формате JSON.                                - `vim new.json ---> input data ---> esc ---> enter ":wq"`
                                                               
 8. Отправить изменения на внешний репозиторий.            - `git commit -am "update file" && git push`
 							       [new.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/new.json)

 9. Создать файл preferences.json                          - `touch preferences.json`

 10. В файл preferences.json добавить информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, любимая еда,
любимое время года, сторона которую хотели бы посетить) 
в формате JSON.                                             - `vim preferences.json ---> input data ---> esc ---> enter ":wq"`

 11. Создать файл skills.json добавить информацию о скиллах
которые будут изучены на курсе в формате JSON               - `cat >> skills.json ---> input data ---> ctrl + c`

 12. Отправить сразу 2 файла на внешний репозиторий.        - `git add . && git commit -m "add new file" && git push` [preferences.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/bug_report.json) [skills.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/skills.json)

 13. На веб интерфейсе создать файл bug_report.json.        - `Add file --> Create new file --> Name: bug_report.json`

 14. Сделать Commit changes (сохранить) 
изменения на веб интерфейсе.				    - `Commit new file`  [bug_report.json](https://github.com/EvgeneyKEO/JSON/blob/cc2c6d91e579d92e0c575d1b85dd255531e6935c/skills.json)

 15. На веб интерфейсе модифицировать файл 
bug_report.json, добавить баг репорт в формате JSON.        - `Choose bug_report.json --> Edit this file` 

 16. Сделать Commit changes (сохранить) изменения
на веб интерфейсе.					    - `Commit changes`

 17. Синхронизировать внешний и локальный репозиторий JSON  - `git pull`
