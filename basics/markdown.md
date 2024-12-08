---
icon: sliders-up
---

# Configurer son serveur Nova-Life: Amboise

Comment configurer son serveur Nova-Life: Amboise ?



Nous allons vous montrez les configurations suivantes que vous deviez modifiez sur votre serveur !

<figure><img src="https://gitbookio.github.io/onboarding-template-images/markdown-hero.png" alt=""><figcaption></figcaption></figure>

## Configurations du ports :

Nous allons commencé par ce rendre dans l'onglet suivant :&#x20;

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2024-11-29 223854.png" alt=""><figcaption></figcaption></figure>

Puis nous allons crée une nouvelle "Allocation" comme ceci :&#x20;

<figure><img src="../.gitbook/assets/Capture d&#x27;écran 2024-11-29 224119.png" alt=""><figcaption></figcaption></figure>

### Configuration dans le fichier server.json

Nous allons modifier le "steamPort" par "l'allocation" qu'on a crée juste au dessus. (27374)

```
{
    "serverName": "nastiheberg",
    "serverListName": "Héberger par nastiheberg.fr",
    "serverSlot": 25,
    "serverPort": 27202,
    "queryPort": 27015,
    "steamPort": 27016,
    "isPublicServer": false,
    "useAdminPinAuth": false,
    "tabletUrl": "",
    "isWhitelisted": false,
    "useWhitelistProtection": false,
    "whitelist": {
        "intro": "",
        "questions": [],
        "date": ""
    },
    "autoSaveIntervalSeconds": 1800.0,
    "disconnectClientsBeforeStop": true,
    "mapId": 0,
    "serverFramerate": 60,
    "hasShop": false
}
```
