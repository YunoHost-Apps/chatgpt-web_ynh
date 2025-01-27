<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# chatGPT-web dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/chatgpt-web)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/)
![Status działania](https://apps.yunohost.org/badge/state/chatgpt-web)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/chatgpt-web)

[![Zainstaluj chatGPT-web z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację chatGPT-web na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

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


**Dostarczona wersja:** 2025.01.22~ynh1

**Demo:** <https://niek.github.io/chatgpt-web/>

## Zrzuty ekranu

![Zrzut ekranu z chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Niepożądane funkcje

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://niek.github.io/chatgpt-web/>
- Repozytorium z kodem źródłowym: <https://github.com/Niek/chatgpt-web>
- Sklep YunoHost: <https://apps.yunohost.org/app/chatgpt-web>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
lub
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
