<!--
N.B.: Questo README è stato automaticamente generato da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
NON DEVE essere modificato manualmente.
-->

# Matrix IRC Bridge per YunoHost

[![Livello di integrazione](https://dash.yunohost.org/integration/matrix-appservice-irc.svg)](https://dash.yunohost.org/appci/app/matrix-appservice-irc) ![Stato di funzionamento](https://ci-apps.yunohost.org/ci/badges/matrix-appservice-irc.status.svg) ![Stato di manutenzione](https://ci-apps.yunohost.org/ci/badges/matrix-appservice-irc.maintain.svg)

[![Installa Matrix IRC Bridge con YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=matrix-appservice-irc)

*[Leggi questo README in altre lingue.](./ALL_README.md)*

> *Questo pacchetto ti permette di installare Matrix IRC Bridge su un server YunoHost in modo semplice e veloce.*  
> *Se non hai YunoHost, consulta [la guida](https://yunohost.org/install) per imparare a installarlo.*

## Panoramica

This is an IRC bridge for Matrix. 

This bridge will pass all IRC messages through to Matrix, and all Matrix messages through to IRC.
It is highly configurable and is currently used on the matrix.org homeserver to bridge a number of popular IRC networks.

### Features

- Merge Matrix rooms to IRC channels
- Full two-way communication in channels and direct messages
- Well-formated replies


**Versione pubblicata:** 0.36.0~ynh1
## Documentazione e risorse

- Documentazione ufficiale per gli utenti: <https://matrix-org.github.io/matrix-appservice-irc/latest/usage>
- Documentazione ufficiale per gli amministratori: <https://matrix-org.github.io/matrix-appservice-irc/latest/bridge_setup>
- Repository upstream del codice dell’app: <https://github.com/matrix-org/matrix-appservice-irc>
- Store di YunoHost: <https://apps.yunohost.org/app/matrix-appservice-irc>
- Segnala un problema: <https://github.com/YunoHost-Apps/matrix-appservice-irc_ynh/issues>

## Informazioni per sviluppatori

Si prega di inviare la tua pull request alla [branch di `testing`](https://github.com/YunoHost-Apps/matrix-appservice-irc_ynh/tree/testing).

Per provare la branch di `testing`, si prega di procedere in questo modo:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/matrix-appservice-irc_ynh/tree/testing --debug
o
sudo yunohost app upgrade matrix-appservice-irc -u https://github.com/YunoHost-Apps/matrix-appservice-irc_ynh/tree/testing --debug
```

**Maggiori informazioni riguardo il pacchetto di quest’app:** <https://yunohost.org/packaging_apps>
