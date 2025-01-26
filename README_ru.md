<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# chatGPT-web для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/chatgpt-web)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/)
![Состояние работы](https://apps.yunohost.org/badge/state/chatgpt-web)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/chatgpt-web)

[![Установите chatGPT-web с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить chatGPT-web быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

ChatGPT-web is a simple one-page web interface to the OpenAI ChatGPT API. To use it, you need to register for an OpenAI API key first. All messages are stored in your browser's local storage, so everything is private. You can also close the browser tab and come back later to continue the conversation.

### Features

- Private: All chats and messages are stored in your browser's local storage, so everything is private.
- Customizable: You can customize the prompt, the temperature, and other model settings. Multiple models (including GTP-4) are supported.
- Cheaper: ChatGPT-web uses the commercial OpenAI API, so it's much cheaper than a ChatGPT Plus subscription.
- Fast: ChatGPT-web is a single-page web app, so it's fast and responsive.
- Mobile-friendly: ChatGPT-web is mobile-friendly, so you can use it on your phone.
- Voice input: ChatGPT-web supports voice input, so you can talk to ChatGPT. It will also talk back to you.
- Pre-selected prompts: ChatGPT-web comes with a list of pre-selected prompts, so you can get started quickly.
- Export: ChatGPT-web can export chats as a Markdown file, so you can share them with others.
- Code: ChatGPT-web recognizes and highlights code blocks and allows you to copy them with one click.


**Поставляемая версия:** 2025.01.22~ynh1

**Демо-версия:** <https://niek.github.io/chatgpt-web/>

## Снимки экрана

![Снимок экрана chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Анти-функции

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Документация и ресурсы

- Официальный веб-сайт приложения: <https://niek.github.io/chatgpt-web/>
- Репозиторий кода главной ветки приложения: <https://github.com/Niek/chatgpt-web>
- Магазин YunoHost: <https://apps.yunohost.org/app/chatgpt-web>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
или
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
