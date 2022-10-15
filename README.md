# Рабочий шаблон для работы с vkbotkit
📘[Репозиторий vkbotkit](https://github.com/vkbotkit/vkbotkit)  
📄[Репозиторий шаблона](https://github.com/vkbotkit/template) ([Использовать](https://github.com/vkbotkit/template/generate))  
📕[Репозиторий с примерами](https://github.com/vkbotkit/examples)  

## Инструкция по установке
**Шаг 0.** Используйте этот шаблон, чтобы создать репозиторий для вашего чатбота, для этого нажмите на "Использовать шаблон" в начале страницы.

**Шаг 1.** Скопируйте ваш репозиторий по этой команде:
```bash
git clone https://github.com/your_nickname/your_bot_repo
cd ./
pip install -r requirements.txt
```

**Шаг 2** Конфигурация ```.env``` файла в корне вашего репозитория
[Пример .env файла на Gist](https://gist.github.com/kensoi/9fe5b96a132bb25aa6114964715f5156)
```
PUBLIC_TOKEN=TESTTOKEN1
DEBUG_TOKEN=TESTTOKEN2
CONFIG_LOG=fc
```

```
f - вывод лога в файл,
c - вывод лога в консоль
```

**Шаг 3.а** Запуск бота
```bash
python3 bot.py
```

**Шаг 3.б** Запуск бота в режиме отладки
```sh
python3 bot.py -d
```

## Пример работы шаблона
![Канари-чан](https://sun9-52.userapi.com/s/v1/ig2/5yBG60JVrtlBYspn2YdMG8KRFZBSyyPuKr0nCbpc1Ms8hzv9iHQ5toAxm9kxT3Q0w_YzKVUdqWGEQcOMbQY9xWna.jpg?size=512x249&quality=96&type=album)  
P. S. Бот будет отвечать на все сообщения таким образом, так что перед добавлением в беседу стоит ознакомиться с документацией о библиотеке vkbotkit.
