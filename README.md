Необходимо написать приложение для Android, которое использует GitHub API (https://developer.github.com/v3/search/) для поиска репозитория по ключевым словам.
В приложении должно быть два экрана:

- Поиск репозитория по ключевым словам. Есть поле для ввода запроса и кнопка. При нажатии на кнопку начинается поиск. Пока идет поиск, пользователю необходимо показать соответствующее сообщение. Все найденные репозитории нужно отобразить в список. При клике на элемент списка - открыть браузер и перейти на страницу проекта.

- История посещений. Нужно запомнить все репозитории в которые переходил пользователь из приложения и отобразить список в хронологическом порядке. Помимо названия репозитория нужно еще вывести: краткое описание проекта, язык программирования, логин автора (owner) и дату создания проекта. Этот список должен быть доступен без интернета. Если в репозиторий переходили несколько раз, то нужно отображать информацию только о самом последнем переходе.

Навигация/переключение между экранами на ваш выбор. Вдохновение можно поискать тут: https://material.io/components/

Дополнительная часть (если хватит времени): На экране истории посещений пользователь может отметить репозиторий как избранный. Соответственно, нужно добавить возможность переключать режим отображения истории: показывать все или только избранные.

Минимальные требования:
- Приложение должно корректно работать на Android 5 - Android 10

- Приложение не должно падать

- Для разработки нужно использовать Android Studio

- Писать код можно на Java или Kotlin

Проект с решением нужно опубликовать на Github или Bitbucket и отправить ссылку на kuznetsov-v@yandex-team.ru с темой "Яндекс.Авто Стажировка". На почту можно задавать вопросы относительно задачи. В первую очередь советую сосредоточиться на качестве кода (именование переменных/классов, структура, итп).
