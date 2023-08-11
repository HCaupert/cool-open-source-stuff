# Cool Open Source Stuff

I often find/use great open source tools, but I also often forget their names. This repository should help.

## Complete Solutions/Platforms/Saas

- [Internationalization](#internationalization)
- Orchestration
- Notification

### Internationalization

#### [Tolgee](https://tolgee.io) - [Github](https://github.com/tolgee)

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
