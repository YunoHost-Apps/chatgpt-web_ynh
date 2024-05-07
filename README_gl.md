<!--
NOTA: Este README foi creado automáticamente por <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON debe editarse manualmente.
-->

# chatGPT-web para YunoHost

[![Nivel de integración](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://dash.yunohost.org/appci/app/chatgpt-web) ![Estado de funcionamento](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Estado de mantemento](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![Instalar chatGPT-web con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Le este README en outros idiomas.](./ALL_README.md)*

> *Este paquete permíteche instalar chatGPT-web de xeito rápido e doado nun servidor YunoHost.*  
> *Se non usas YunoHost, le a [documentación](https://yunohost.org/install) para saber como instalalo.*

## Vista xeral

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


**Versión proporcionada:** 2024.05.06~ynh1

**Demo:** <https://niek.github.io/chatgpt-web/>

## Capturas de pantalla

![Captura de pantalla de chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Caraterísticas cuestionables

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentación e recursos

- Web oficial da app: <https://niek.github.io/chatgpt-web/>
- Repositorio de orixe do código: <https://github.com/Niek/chatgpt-web>
- Tenda YunoHost: <https://apps.yunohost.org/app/chatgpt-web>
- Informar dun problema: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Info de desenvolvemento

Envía a túa colaboración á [rama `testing`](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

Para probar a rama `testing`, procede deste xeito:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
ou
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Máis info sobre o empaquetado da app:** <https://yunohost.org/packaging_apps>
