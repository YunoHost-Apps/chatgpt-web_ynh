<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# chatGPT-web YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![Instalatu chatGPT-web YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek chatGPT-web YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

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


**Paketatutako bertsioa:** 2024.08.26~ynh1

**Demoa:** <https://niek.github.io/chatgpt-web/>

## Pantaila-argazkiak

![chatGPT-web(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## :red_circle: Ezaugarri zalantzagarriak

- **Libreak ez diren sareko zerbitzuak**: Librea ez den sare-zerbitzu bat sustatzen du edo horren mende dago erabat.

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://niek.github.io/chatgpt-web/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/Niek/chatgpt-web>
- YunoHost Denda: <https://apps.yunohost.org/app/chatgpt-web>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
edo
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
