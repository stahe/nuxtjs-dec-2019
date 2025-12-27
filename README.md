# Introduction au framework NUXT.JS par l'exemple

📘 **Accéder à la documentation du cours :** [https://stahe.github.io/nuxtjs-dec-2019/](https://stahe.github.io/nuxtjs-dec-2019/)

---

Ce document présente des exemples d'utilisation framework NUXT.JS.

Le framework [Nuxt.js](https://fr.nuxtjs.org/) va nous permettre d’implémenter le fonctionnement suivant :

- La 1ère page de l’application web est délivrée par exemple par un serveur [node.js]. Par ailleurs les autres pages de l’application sont également présentes sur ce même serveur. Elles sont délivrées lorsque l’utilisateur tape leur URL à la main dans le navigateur. Ces pages embarquent une application [vue.js] (approximativement).
- Une fois la 1ère page chargée dans le navigateur, l’application se comporte comme une application [vue.js] classique.

Au final, l’application se comporte comme une application [vue.js] sauf pour la 1ère page et lorsque l’utilisateur tape des URL à la main. Dans ces cas, la page est cherchée sur le serveur. 

Lorsque qu’un moteur de recherche demande les différentes pages de l’application, il reçoit les pages du serveur. Celles-ci ont pu être optimisées pour le SEO (Search Engine Optimization). Dans une application [vue.js] classique, le moteur de recherche reçoit une page avec peu de signification SEO.

## Méthodologie

Les scripts du document sont commentés et leur exécution reproduite. Des explications supplémentaires sont parfois fournies. Le document nécessite une lecture active : pour comprendre un script, il faut à la fois lire son code, ses commentaires et ses résultats d'exécution.