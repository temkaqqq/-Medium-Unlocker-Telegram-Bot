Телеграм-бот который разблокирует статьи с Medium и переводит их на русский.

## Что умеет

- Разблокирует платные статьи Medium
- Переводит на русский
- Делает AI-выжимку (краткое содержание)
- Озвучивает статьи голосом
- Подбирает интересные статьи по темам

## Установка

```bash
cd telegram-bot
npm install
```

Для озвучки нужен Python:
```bash
pip install torch torchaudio --index-url https://download.pytorch.org/whl/cpu
pip install scipy
```

## Настройка

Создай `.env` файл:

```
BOT_TOKEN=токен_бота
ADMIN_ID=твой_id
GROQ_API_KEY=ключ_groq
```

## Запуск

```bash
npm start
```

Или просто `start.bat` на Windows.

## Как пользоваться

Кидаешь ссылку на Medium → получаешь переведённую статью.

Можно подписаться на темы и получать подборки статей.


пример работы тут https://t.me/football333_bot
