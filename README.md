# Project Title

https://xxyyzz.com website

## Description

The best bank with the best loans. Opening soon in a city near you.

## Getting Started

### Dependencies

The website is currently hosted on Firebase within Google Cloud infrastruture. It is deployed via Jenkins.

Local
* Modern IDE (Visual Studio Code, PyCharm, etc)
* Node JS 18.12+
* firebase-tools

Remote (Jenkins)
* Jenkins (latest version preferred)
* Node JS 18.12+ (installed as a Global Tool)
* firebase-tools (installed as a Global npm within the NodeJS setup)

### Deploying

Deploy locally
* Clone repo `git clone https://github.com/swerenfl/www-xxyyzz`
* Run `firebase init` and follow prompts
    * NOTE: Must be able to authenicate to the project in Firebase
* Make changes and save locally
* Run `firebase deploy`

Deploy via Jenkins
* Clone repo `git clone https://github.com/swerenfl/www-xxyyzz`
* Make changes and commit code to the remote repository
* Jenkins will pick up the change via webhook and automatically deploy

## FAQ

What about SSL?
* Firebase automatically provisions SSL certificates for all your domains so that all your content is served securely.

Can I test before going live?
* Yes! Using the Firebase Local Emulator Suite, you can emulate your app and backend resources at a locally hosted URL.

Can I connect my own domain name?
* Yes! Directions can be found here: https://firebase.google.com/docs/hosting/custom-domain

Does Firebase include a CDN?
* Yes! All content is served over an SSL connection from the closest edge server at Google's global CDN.

What else can Firebase do?
* Beyond serving static content, you can use Cloud Functions for Firebase or Cloud Run to serve dynamic content and host microservices on your sites.


## Authors

Richard Staehler III  

## Version History

* 0.2 (main)
    * Various alignment issues, optimizations, unfurling
    * Added images including favicon
    * See [commit change](https://github.com/swerenfl/www-xxyyzz/commits/main) for further changes
* 0.1 (main)
    * Initial Release

## License

This project is licensed under the CCA 3.0 license (html5up.net/license) License - see the LICENSE.txt file for details

## Acknowledgments

Design, images, etc.
* [Eventually by HTML5 UP](https://html5up.net)
* [Dall-E-2](https://openai.com/product/dall-e-2)
* [Pexels](https://www.pexels.com/search/bank/)
* [Firebase](https://firebase.google.com/docs/hosting)
* [Jenkins](https://www.jenkins.io/)