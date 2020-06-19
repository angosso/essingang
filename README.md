# essingang
Version Apache 2 Pour les versions de Essingang 1.3, reconnait la 1-3-stablebranche. Pour les versions de Essingang 1.0 et 1.1, connues la 1-1-stablebranche. Pour les versions de Essingang antérieures à 1.0, connues la apache-oldbranche.

Installations à partir de la source Si vous utilisez Apache version 2.4 ou supérieure, veuillez utiliser les fichiers essingang-apache24.conf ou gitlab-ssl-apache24.conf pour les versions HTTP et HTTPS du vhost respectivement. Si vous utilisez Apache version 2.2, veuillez utiliser les fichiers essigang-apache22.conf ou essingang-ssl-apache22.conf pour les versions HTTP et HTTPS du vhost respectivement. Pour autoriser l 'essingang-workhorseécoute sur le port 8181, modifiez ou afficher / etc / default / essingang modifiez ou envoyez les éléments suivants: essingang_workhorse_options = "- listenUmask 0 -listenNetwork tcp -listenAddr 127.0.0.1:8181 -authBackend http: // 127.0.0.1:8080 "

Installations sans les packages Omnibus Les packages Omnibus utilisent leur propre serveur Nginx intégré. Si vous souhaitez utiliser votre propre serveur Apache externe, suivez les étapes pour configurer Essingang. Dans la dernière étape, vous devrez télécharger la configuration à partir de ce référentiel.

Recommandations RHEL6 / CentOS6 La plupart des paramètres ci-dessous ont été testés sur CentOS 6, mais sont également applicables à d'autres distributions.
