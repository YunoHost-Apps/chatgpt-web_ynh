<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# chatGPT-web untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![Pasang chatGPT-web dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang chatGPT-web secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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


**Versi terkirim:** 2024.11.11~ynh1

**Demo:** <https://niek.github.io/chatgpt-web/>

## Tangkapan Layar

![Tangkapan Layar pada chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Antifitur

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://niek.github.io/chatgpt-web/>
- Depot kode aplikasi hulu: <https://github.com/Niek/chatgpt-web>
- Gudang YunoHost: <https://apps.yunohost.org/app/chatgpt-web>
- Laporkan bug: <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
atau
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
