1. Создать внешний репозиторий c названием “JSON”

        New → Create repository
2. Клонировать репозиторий “JSON” на локальный компьютер.


        https://github.com/kolikplatis/JSON.git
3. Внутри локального “JSON” создать файл “new.json”

        touch (или cat >, или > ) new.json
4. Добавить файл под гит

        git add .
5. Закоммитить файл

        git commit -m “new file”
6. Отправить файл на внешний GitHub репозиторий

        git push
7. Отредактировать содержание файла “new.json”: написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON

        cat  >> new.json
        {
        “FIO”: “J J Simmons”,
        “Age”: 60,
        “Pets”: 2,
        “Expected salary”: 100000
        }
8. Отправить изменения на внешний репозиторий

        git add .
9. Создать файл “preferences.json”

        > preferences.json
10. В файл “preferences.json” добавить информацию о своих предпочтениях (любимый фильм, любимый сериал, любимая еда, любимое время года, страна, которую хотели бы посетить) в формате JSON.

        vim preferences.json
        i
        {
        "favorite film" : "Departed",
        "favorite series" : "Method",
        "favorite food" : "pizza",
        "favorite season" : "summer",
        "desired country" : "Serbia"
        }
11. Создать файл “skills.json”, добавить информацию о скиллах которые будут изучены на курсе в формате “JSON”

        cat > skills.json
        {
        "skills" : ["theory", "terminal", "git", "sql"]
        }
12. Отправить сразу 2 файла на внешний репозиторий.

        git add .
13. На веб-интерфейсе создать файл “bug_report.json”

        - кнопка [Add file]
        - кнопка [Create new file]
14. Сделать Commit changes (сохранить) изменения на веб-интерфейсе

        кнопка [Commit changes]
15. На веб-интерфейсе модифицировать файл “bug_report.json”, добавить багрепорт в формате “JSON”

        кнопка [Edit this file]
16. Сделать Commit changes (сохранить) изменения на веб-интерфейсе

        кнопка [Commit changes]
17. Синхронизировать внешний и локальный репозиторий JSON

        git pull

