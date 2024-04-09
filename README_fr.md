<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# chatGPT-web pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/chatgpt-web.svg)](https://dash.yunohost.org/appci/app/chatgpt-web) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/chatgpt-web.maintain.svg)

[![Installer chatGPT-web avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=chatgpt-web)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer chatGPT-web rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

ChatGPT-web est une simple interface Web d'une page pour l'API OpenAI ChatGPT. Pour l'utiliser, vous devez d'abord vous inscrire à une clé API OpenAI. Tous les messages sont stockés dans le stockage local de votre navigateur, donc tout est privé. Vous pouvez également fermer l'onglet du navigateur et revenir plus tard pour poursuivre la conversation.

**Version incluse :** 2024.04.08~ynh1

**Démo :** <https://niek.github.io/chatgpt-web/>

## Captures d’écran

![Capture d’écran de chatGPT-web](./doc/screenshots/screenshot.png)

## :red_circle: Anti-fonctionnalités

- **Services réseau non libres **: Promeut ou utilise des services réseau non libres.

## Documentations et ressources

- Site officiel de l’app : <https://niek.github.io/chatgpt-web/>
- Dépôt de code officiel de l’app : <https://github.com/Niek/chatgpt-web>
- YunoHost Store : <https://apps.yunohost.org/app/chatgpt-web>
- Signaler un bug : <https://github.com/YunoHost-Apps/chatgpt-web_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
ou
sudo yunohost app upgrade chatgpt-web -u https://github.com/YunoHost-Apps/chatgpt-web_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
