<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# chatGPT-web voor Yunohost

[![Integratieniveau](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/) ![Mate van functioneren](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Onderhoudsstatus](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![chatGPT-web met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je chatGPT-web snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

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


**Geleverde versie:** 2024.10.17~ynh1

**Demo:** <https://niek.github.io/chatgpt-web/>

## Schermafdrukken

![Schermafdrukken van chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Anti-eigenschappen

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentatie en bronnen

- Officiele website van de app: <https://niek.github.io/chatgpt-web/>
- Upstream app codedepot: <https://github.com/Niek/chatgpt-web>
- YunoHost-store: <https://apps.yunohost.org/app/chatgpt-web>
- Meld een bug: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
of
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
