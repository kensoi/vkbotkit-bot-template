# Рабочий шаблон для работы с vkbotkit
📘[Репозиторий vkbotkit](https://github.com/kensoi/vkbotkit)  
📕[Репозиторий шаблона](https://github.com/kensoi/vkbotkit_app)  
📄[Использовать шаблон](https://github.com/kensoi/vkbotkit_app/generate)

## Инструкция по установке
**Шаг 0.** Используйте этот шаблон, чтобы создать репозиторий для вашего чатбота, для этого нажмите на "Использовать шаблон" в начале страницы.

**Шаг 1.** Скопируйте ваш репозиторий по этой команде:
```sh
git clone https://github.com/your_nickname/your_bot_repo
cd ./
pip install -r requirements.txt
```

**Шаг 2.а** Настройка enviroment ключей в bash
```sh
export PUBLIC_TOKEN=TESTTOKEN1
export DEBUG_TOKEN=TESTTOKEN2
export CONFIG_LOG=fc
```

**Шаг 2.б** Конфигурация .env файла
```
PUBLIC_TOKEN=TESTTOKEN1
DEBUG_TOKEN=TESTTOKEN2
CONFIG_LOG=fc
```

```
f - сохранение лога в файл,
c - вывод лога в консоль
```
**Шаг 3.** Запуск бота
```sh
python3 bot.py [-d]
```
**Готово!** Бот работает, результат будет таким:
![Канари-чан](https://sun3-11.userapi.com/s/v1/ig2/vP4GRtbDgJsUd5OXLssGVf132-I4QaiT_iGnZEzefuBSBxijiOsS0oFYBgn615iZzKJhqy8EwgC1MSYeR3yBHLi1.jpg?size=814x302&quality=96&type=album)
P. S. Бот будет отвечать на все сообщения таким образом, так что перед добавлением в беседу стоит ознакомиться с документацией о библиотеке vkbotkit.