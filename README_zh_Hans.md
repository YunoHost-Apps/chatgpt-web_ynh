<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 chatGPT-web

[![集成程度](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://ci-apps.yunohost.org/ci/apps/chatgpt-web/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![使用 YunoHost 安装 chatGPT-web](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 chatGPT-web。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

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


**分发版本：** 2024.09.26~ynh1

**演示：** <https://niek.github.io/chatgpt-web/>

## 截图

![chatGPT-web 的截图](./doc/screenshots/screenshot.png)

## :red_circle: 负面特征

- **Non-free Network Services**: Promotes or depends entirely on a non-free network service.

## 文档与资源

- 官方应用网站： <https://niek.github.io/chatgpt-web/>
- 上游应用代码库： <https://github.com/Niek/chatgpt-web>
- YunoHost 商店： <https://apps.yunohost.org/app/chatgpt-web>
- 报告 bug： <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
或
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
