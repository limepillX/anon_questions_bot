# Анонимный бот для отправки сообщений
### Бот создан для одной простой задачи - отправка анонимных вопросов преподавателю по курсу.

## Демонстрация работы
При условии успешно запущенного бота, любой пользователь telegram может написать в него сообщение.

![image](https://user-images.githubusercontent.com/59223504/221155727-b91b73fb-8633-42e4-8c84-0e4c5e109d1d.png)

При этом преподавателю придёт сообщение от того-же бота, содержащее только текст вопроса (без отправителя).

![image](https://user-images.githubusercontent.com/59223504/221155997-c6e009a0-92ca-44c8-bbed-cfdea5fb4a93.png)

К тому же, все вопросы записываются в json файл ```output/questions.txt```

![image](https://user-images.githubusercontent.com/59223504/221156356-14e0c003-4697-4711-bf8f-5cbf196d1dda.png)

## Установка бота

1. Для правильной работы бота необходимо установить pyTelegramBotAPI. Сделать это можно двумя способами: 
    * ```pip install -r requirements.txt```
    *  ```pip install pyTelegramBotAPI```

2. Надо получить API ключ для бота через [@BotFather](https://t.me/BotFather)

3. В корневой папке проекта создать папку ```input```, там создать файл ```API_KEY``` (без расширения) и записать в него полученный ключ.

4. В этой же папке ```input``` создать файл ```teacher_id``` (без расширения), куда записать свой (преподаватель) telegram-id. Получить его можно [здесь](https://t.me/RawDataBot). Ниже расписал подробнее.

5. Запустите файл main.py через IDE или командой ```python main.py```

## Порядок получения id преподавателя (Ваш)

1. Перейдите по ссылке, или найдите в телеграме [@RawDataBot](https://t.me/RawDataBot).

2. Запустите его командой ```/start```

3. Скопируйте id.

![image](https://user-images.githubusercontent.com/59223504/221158672-01bb8a54-c90d-4e5a-bfeb-90d751cc73ad.png)
Готово. При желании, бота можно загрузить на хостинг, ex. [pythonanywhere](https://www.pythonanywhere.com/)

***Оставить отчёт о багах можно здесь***, [ссылка](https://github.com/limepillX/anon_questions_bot/issues)

***Найти меня можно в телеграме, [@fiodoryakovenko](https://t.me/fiodoryakovenko) (кликабельно)***

