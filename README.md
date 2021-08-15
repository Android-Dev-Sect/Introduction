# Android Dev Sect
### Чего ты хочешь?
Если ты читаешь этот текст, значит ты заинтересован в том, чтобы начать свой путь или развиться как Android разработчик. Задачи на твоем пути встретятся разные - от оптимизации систем сборок, создания библиотек для использования архитектурных паттернов и улучшения их с помощью многопоточности - до реализации и внедрения передовых сетевых протоколов и постоения различных слоев твоего приложения. Может звучать даже страшно, но от того и интереснее во всем разобраться, правда?
### Зачем нужна секта?
Подобные сообщества и инициативы помогают его участникам легче шарить знания, создавать совместные проекты, помогать новичкам вкатиться в область или перенять опыт от старичков этого дела. Здесь ты сможешь найти единомышленников, похоливарить за разные архитектуры и подходы, попросить помощи с нерешаемой задачей и поугарать над мемами.
### А что от тебя требуется?
Стоит понимать, что бьется ли пульс секты - зависит именно от тебя: делишься ли ты интересными статьями с другими участниками, участвуешь в обсуждениях и остаешься заинтересован в развитии как Android-Dev. Доказать свою заинтересованность ты можешь с помощью реализации проектов, которые будут с определенной регулярностью поститься в канал секты.
### Тестовое задание
Оценки за тестовое задание ставиться **не будут**. Тестовое нужно, чтобы определить твой уровень, проверить твою мотивацию и вовлеченность в разработку. Выполнение тестового задания **обязательно**.
### Что будет, если не сделать тестовое задание?
Для вступления в сообщество придется приложить немного усилий. Если у тебя сейчас нет времени на выполнения тестового, возвращайся, когда появится свободное время и дерзай! А пока тебе придется лишиться статуса участника 😞
### Как выполнять тестовое задание?
Тестовые задания разбиты по уровню сложности. Исходя из своих навыков, ты выбираешь **одно** тестовое по своему уровню. Чтобы проще определиться со своим уровнем, у каждого тестового будет список навыков, который необходим для его выполнения. Срок выполнения тестового для всех уровней одинаковый: **две недели**
## Описание тестовых заданий

### _Вспомогательные ресурсы_
* [StartAndroid](https://startandroid.ru/ru/) - простенький онлайн учебник на русском для освоения азов Android-разработки
* [Документация](https://developer.android.com/) - документация от гугла с примерами
* [Kotlin Koans](https://play.kotlinlang.org/koans/overview) - обучение фишкам котлина, для тех, кто знаком с Java
* [Стартовая книга по Android](https://vk.com/doc204761338_505857021?hash=728a1435bd7016268f&dl=a09d3461ae53284618) - рассмотрены чуть более детально и в более художественной манере основные приемы в Android. Можно считать уже устаревшей в плане архитектурных подходов, но, что касается компонентов - много что осталось неизменным
### Уровень: Новенький
##### Описание
Создать Android-приложение с полем для ввода и двумя кнопками. 
Кнопка №1 выводит [Toast](https://developer.android.com/guide/topics/ui/notifiers/toasts?hl=ru) с содержимым полем ввода.
Кнопка №2 изменяет фон экрана на произвольный цвет.
##### Для кого это тестовое?
* Есть базовые знания в программировании
* Желание бешеное имеет разобраться в создании Android-приложений
### Уровень: Уже Смешарик
##### Описание
Создать приложение-калькулятор. Если ты знаком с разработкой под Android, то оформить это тестовое нужно в виде Android-приложения, иначе в виде консольного приложения на Java/Kotlin
##### Для кого это тестовое?
* Знаком с Java/Kotlin/C#
* Был опыт написания простых Android-приложений (не обязательно)
##### Требования:
1. Общие:
    1. Поддержка следующих операций: "+", "-", "×", "÷", "√"
    2. Возможно наличие скобок в выражении [ex. **(3 + 2) × 5**  ]
    3. Вычисления должны проводиться в правильном математическом порядке
    4. Все вычисления в пределах INT_32
    5. Обработка ошибок неправильно заданного выражения
    6. Запрещено использовать какие-либо библиотеки
2. Android-приложение:
    0. _minApi = 23 targetApi = 30_
    1. Сохранение состояния ввода, после поворота экрана
    2. Адаптивность к размерам устройства
    4. Запрещается использовать системную клавиатуру
    5. Отображение истории вычисленных выражений
3. Консольное-приложение:
    1. Указание источника ввода (консоль/файл)
    2. Указание источника вывода (консоль/файл)
    3. Сохранение истории вычисленных выражений в отдельный файл

### Уровень: Трах-трахыч
Реализовать Android-приложение для прослушивания mp3 треков c устройства.
##### Для кого это тестовое?
* Имеет хотя бы один Android pet-project
* Знает основные компоненты Android системы
##### Требования
1. _minApi = 23 targetApi = 30_
2. Язык разработки - only Kotlin
3. Правильная работа с пермишенами в рантайме
4. Правильная обработка поворота экрана
5. Наличие архитектуры в приложении
6. Возможность прослушивать музыку при свернутом приложении
7. Возможность выбрать папку на устройстве и работать с ней, как с плейлистом [ex: в папке лежит три mp3, при выборе данной папки треки из папки будут проигрываться по очереди]
8. Запрещается использовать библиотеки, кроме ExoPlayer
9. Анимация сворачивания/разворачивания плеера
10. Бонус: реализовать свой системный пикер папок
11. Бонус: поддержка темной темы
##### Пример макетов
Menu             |  Player
:-------------------------:|:-------------------------:
<img src="https://github.com/Android-Dev-Sect/Introduction/blob/main/Menu.png" width="50%" height="50%">  |  <img src="https://github.com/Android-Dev-Sect/Introduction/blob/main/Player.png" width="50%" height="50%">
