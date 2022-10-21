# BankingInfo_Bot
---

## Описание ПО:
Bot для мессенджера Telegram, который позволяет получить через официальный API Банка России важную финансовую информацию.

Возможности бота связаны с получением в интерактивном режиме следующих данных:
* темпы инфляции,
* значение ключевой ставки,
* официальные курсы основных валют,
* учетные цены на драгоценные металлы.
---

Возможности программы:
* Отправка запроса на получение информации в диалоговом режиме.
* Выбор запрашиваемой информации в меню.
* Возможность использования бота в Inline-режиме.
* Получение помощи в случае некорректного запроса или путем отправки ключевого слова "help" (или аналогичных).
* Обработка ошибок (исключений), возникающих из-за некорректных действий пользователя, проблем с источником данных и пр.
* Логгирование ошибок для отладки и устранения проблем в случае изменения [API Банка России](https://www.cbr.ru/DailyInfoWebServ/DailyInfo.asmx). 
---

Технологии:
* Python 3.7.9
* BeautifulSoup4 4.11.1
* Requests 2.28.1
---

### Установка (Windows):
1. Создать виртуальное окружение: `python -m venv venv`
2. Активировать виртуальное окружение: `source venv/scripts/activate`
3. Установить зависимости: `pip install -r requirement.txt`
---

### Адрес по которому доступен Bot:

* `@BankingInfo_Bot`
---

#### Автором данного кода является:
- [Олег Мазняк](https://vk.com/id711694423) ученик 10 класса [Школы № 1 в ст. Ольгинской](https://olginschool.rnd.eduru.ru/?ysclid=l9hbe3ijli576377254) Аксайского района Ростовской области.