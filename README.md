# RBC.RU parser
Скрипт для парсинга 15 новостей с главной страницы www.rbc.ru


При запуске собирает ифнформацию в каждой новости:

1. Заголовок
2. Дата публикации
3. Ссылка на новость
4. Категория новости
5. Ссылка на картинку новости
6. Полный текст новости


Затем выгружает данные в формате JSON в виде:

{"New_1": {
        "link": "some",
        "date": "some",
        "text": "some",
        "title": "some",
        "category": "some",
        "image": "some"
    },
   "New_n": {}
}


Для работоспособности скрипта необходимо установить 2 библиотеки:

1. pip3 install beautifulsoup4
2. pip3 install lxml
