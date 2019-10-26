# TYPO3 PWA Demo Distribution
 It allows to start exploring PWA solution for TYPO3.
It's based on 

- https://github.com/TYPO3-Initiatives/headless
- https://github.com/TYPO3-Initiatives/nuxt-typo3
- https://github.com/TYPO3-Initiatives/create-nuxt-typo3

## Requirements
All you need is [ddev](https://ddev.readthedocs.io/en/stable/) in version at least v1.11.2 and mkcert as dependency, because we have to provide valid SSL certificate.

## Installation
First of all, make sure that you have installed ddev and you have generated certificates with mkcert.

Then, clone this repository, ``cd pwa-demo`` and run ``chmod 775 .ddev/import-if-empty.sh``.

Execute ``ddev start``, and you are ready to go.

Access frontend from ```pwa-demo.ddev.site```.

Access TYPO3 backend from ```api.pwa-demo.ddev.site/typo3```.

Credentials: ```admin:password```

## Development
Development for this extension is happening as part of the TYPO3 PWA initiative, see https://typo3.org/community/teams/typo3-development/initiatives/pwa/
