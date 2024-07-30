<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# chatGPT-web para Yunohost

[![Nivel de integración](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/) ![Estado funcional](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Estado En Mantención](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![Instalar chatGPT-web con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarchatGPT-web rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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


**Versión actual:** 2024.07.22~ynh1

**Demo:** <https://niek.github.io/chatgpt-web/>

## Capturas

![Captura de chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Características no deseables

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Documentaciones y recursos

- Sitio web oficial: <https://niek.github.io/chatgpt-web/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/Niek/chatgpt-web>
- Catálogo YunoHost: <https://apps.yunohost.org/app/chatgpt-web>
- Reportar un error: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [`branch testing`](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
o
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
