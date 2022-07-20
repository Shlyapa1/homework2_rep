## Ініціалізація репозиторія
<code>git init</code>

## Додаємо нові файли в коміт
- Вибірково <code>git add файл …</code>
- Всі нові <code>git add .</code>

## Перший коміт - фіксація змін
<code>git commit -m "Init repository"</code>

## Створення нової гілки
- Додамо нову гілку dev <code>git branch dev</code>
- Перелік гілок <code>git branch</code>
- Перемкнемося на гілку dev <code>git checkout dev</code>
- Додамо всі нові зміни в індекс <code>git add .</code>
- Фіксація змін <code>git commit -m "Dev branch chenges"</code>

## Зливання гілки dev з гілкою master
- Перемкнемося на гілку master <code>git checkout master</code>
- Перевіримо статус змін гілки master <code>git status</code>
- Якщо гілка має не зафіксовані зміни їх потрібно завіксувати!
- Зливаємо гілку master <code>git merge master</code>
- Додамо всі нові зміни в індекс <code>git add .</code>
- Комітимо зміни <code>git commit -m "Master branch merge from dev"</code>