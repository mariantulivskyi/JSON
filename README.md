# JSON Home Work

 4. Создать внешний репозиторий c названием JSON. 
 5. Клонировать репозиторий JSON на локальный компьютер. - git clone https://github.com/mariantulivskyi/JSON.git
 6. Внутри локального JSON создать файл “new.json”. - vim new.json
 7. Добавить файл под гит. - git add .
 8. Закоммитить файл. - git commit -m "Add file new,json"
 9. Отправить файл на внешний GitHub репозиторий.c - git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 vim new.json
 ``{
 "name":"Marian",
 "surame":"Tulivskyi",
 "age":"25",
 "pets":"1",
 "salary":"350"
}``
 11. Отправить изменения на внешний репозиторий. - git push
 12. Создать файл preferences.json - touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
``{
"film":"Law Abiding Citizen",
"serial":"Prison Break",
"food":"pizza",
"season":"summer",
"visitcountry":"Italy"
}``
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
``{	
"theory": "what is testing, bug reports, documentation, SDLC, STLC, method, etc",
"apps": "Postman, Fidler, XCode, Android Studio, Jmeter, etc",
"SQL": "Create, Delete, Drop, Insert",
"methodology": "Scrum"
}``
 15. Отправить сразу 2 файла на внешний репозиторий. 
	git add preferences.json skills.json 
	git commit
	git push
 16. На веб интерфейсе создать файл bug_report.json.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON
