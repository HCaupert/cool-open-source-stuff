# Cool Open Source Stuff

I often find/use great open source tools, but I also often forget their names. This repository should help.

## Complete Solutions/Platforms/Saas

- [Internationalization](#internationalization)
- [Orchestration](#orchestration)
- [Notification](#notification)
- [Billing](#billing)
- [Webhook](#webhook)
- [Pdf](#pdf)

### Internationalization

#### [Tolgee](https://tolgee.io)
[![GitHub stars](https://img.shields.io/github/stars/tolgee/tolgee-platform.svg?style=social)](https://github.com/tolgee/tolgee-platform)


###### Official Description

Tolgee is a localization platform that allows you to translate your application into any language without modifying your
code. It is designed to be used with web applications, but it can be used also with mobile apps and desktop
applications.

###### My Description 

Basically a way to manage your translations outside your app. Basic workflow could be:

- Adding a new translation key to `base_language.json`
- Pushing the new file to Tolgee (prob on merged PR through CI).
- See new key on Tolgee dashboard, add translations for other languages.
- On release, pull the translations from Tolgee and add them to your app. 

###### Opinion
Just used in a POC but would reuse in a real project.
Looks cool ! Quite young yet but repo is really active and project is promising. 
Fancy features like auto-translation from different sources (Google, DeepL, etc.). Handles pluralization, etc.

###### Developer Experience

Many integrations for different web runtimes as well as Figma & Unreal. 
Documentation is short but clear and probably enough.

###### Ops Experience

Never deployed, used the free Saas version. 
They offer an uber docker image where everything is embedded. 
Database (Postgresql) can be self-managed outside as well.
It might not be necessary since your whole project (translations) is duplicated in a git repo.
No kube/helm resources available yet.


### Orchestration
#### [Temporal](https://temporal.io/) 
[![GitHub stars](https://img.shields.io/github/stars/temporalio/temporal.svg?style=social)](https://github.com/temporalio/temporal)

### Notification
#### [Novu](https://novu.co/)
[![GitHub stars](https://img.shields.io/github/stars/novuhq/novu.svg?style=social)](https://github.com/novuhq/novu)

### Billing
#### [Lago](https://www.getlago.com/)
[![GitHub stars](https://img.shields.io/github/stars/getlago/lago.svg?style=social)](https://github.com/getlago/lago)

### Webhook
#### [Svix](https://www.svix.com/)
[![GitHub stars](https://img.shields.io/github/stars/svix/svix-webhooks.svg?style=social)](https://github.com/svix/svix-webhooks)

### Pdf
#### [Gotenberg](https://gotenberg.dev/)
[![GitHub stars](https://img.shields.io/github/stars/gotenberg/gotenberg.svg?style=social)](https://github.com/gotenberg/gotenberg)
