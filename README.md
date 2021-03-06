# system-of-programming
## Система Программирования. Навык 

### Workflow
* Причина. 5 вопросов почему.
* Это регресс, найти источник?
* Кайдзен.
* 5 минут улучшения.
* Системный подход к программированию.
* Инпакт тестирование.
* Связанные задачи.
* Стандарты кодирования.



## Подробное разбяснение по каждому навыку.

### Причина. 5 вопросов почему. 

Описание: Перед началом задачи задать себе вопросы (и повторить их 5 раз, можно и больше), чтобы лучше понять задачу. 
Базовые вопросы:
- Почему это задача возникла?
- Как не повторить данной задачи в будущем?
Подробнее прочитать: https://www.adme.ru/svoboda-psihologiya/5-voprosov-kotorye-neobhodimo-zadat-chtoby-reshit-lyubuyu-problemu-1625015/

### Это регресс, найти источник?

Описание: В процессе решения задачи найти причину (источник) проблемы. Если причина деффекта была найдена в процессе и есть ответственный, предложить ему сделать свою задачу, которая не будет ломать оставшиеся части проекта.
Алгоритм:
- Данная задача/ошибка новая?
- Найдёна ли изначальная причина ошибки?
- Найден отвественный за ошибку?
- Была исправлена причина ошибки или её следствие?

### Кайдзен
Описание: Кайдзен - это методика неприрывного улучшения
Алгоритм:
- Аккуратность
- Порядок
- Чистота
- Стандартизирование
- Дисциплина
Подробнее: https://lifehacker.ru/kaizen/

### 5 минут улучшения
Описание: посмотреть на ежедневные действия, которые отнимают время и постораться из автоматизировать, улучшить, убрать.
Алгоритм:
- Посмотреть на ежедневные дела, рутины, задачи.
- Выявить повторяющиеся действия
- Оптимизировать их или убрать.
Подробнее прочитать: https://habr.com/ru/post/547592/

### Системный подход к программированию
Описание: курс по реализации задачи как разработке ПО. https://habr.com/ru/post/545852/
Алгоритм:
- Анализ задачи и предметной области
- - Представить задачу в динамике
- - Выделить Константы, Переменные и События.
- Проектирование структур данных
- - Фиксируем название структуры
- - Описываем её тип
- - Пишем интерпретацию структуры - описание того, как преобразовать реальные данные в указанный тип.
- - Придумываем один - два примера заполненной структуры.
- Проектирование функций
- - Создаем заглушку. Заглушка - это определение функции, которое:
- - - отражает правильное название функции
- - - принимает правильное количество и типы параметров
- - - возвращает произвольный результат, но корректного типа
- - Описываем входные, выходные данные и назначение функции
- - Пишем тесты. Тесты должны иллюстрировать поведение функции и проверять корректность выходных данных при разных входных данных.
- - Пишем тело функции.
- - Если в процессе написания функции необходимо обращаться к другой функции, то мы:
- - - сразу описываем функцию и добавляем заглушку
- - - добавляем отметку (TODO), помечающую нашу функцию как объект списка задач
Подробнее: https://habr.com/ru/post/545852/


### Инпакт тестирование.
Описание: Инпакт тестирование - это тестирование связанных компонентов при дороботке функционала.
Алгоритм: 
- После завершения задачи проверить все связанные места и компоненты, которые затронуло изменения
- После завершения задачи в описание Merge Request добавить описание тех мест, которые могли бы быть затронуты 

Подробнее: https://habr.com/ru/post/539208/, https://habr.com/ru/post/144609/

### Связанные задачи
Описание: если задача связана с другой задаче, необходимо эту связь обозначить
Алгоритм:
- У задачи проставлена родительская задача?
- У задачи проставленны связанные задачи?

### Стандарты кодирования
Описание: оставить лишь 1 вариант написания кода на все случаи жизни.
Алгоритм: 
- Какой синтаксис используется в проекте?
- Есть ли файл с описанием стандартов кодирования?
- Есть ли возможность проверять на стандарты кодирования совремменные?
