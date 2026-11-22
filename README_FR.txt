AL-QURAN — VERSION 2 (PWA / BASE ANDROID)
=========================================

Cette archive contient le code source d'une application web progressive (PWA)
conçue pour Android. Ce n'est PAS encore un APK compilé ou signé.

FONCTIONS DE CETTE VERSION
- Interface française, thème clair/sombre et navigation mobile.
- Liste des 114 sourates.
- Texte arabe Uthmani et traduction française Muhammad Hamidullah.
- Choix de plusieurs récitateurs arabes via AlQuran Cloud.
- Lecture audio arabe verset par verset.
- Téléchargement des fichiers audio arabes d'une sourate dans IndexedDB.
- Bouton FR : lecture vocale de la traduction via la synthèse vocale Android / navigateur.
- Hadiths avec références de recueils.
- Invocations tirées du Coran et de la Sunna, avec références.
- Tasbih numérique avec compteur mémorisé sur l'appareil.
- Mise en cache de l'interface et des textes/fichiers demandés.

IMPORTANT — AUDIO FRANÇAIS
La voix française est la synthèse vocale du téléphone (SpeechSynthesis), et non un
fichier de récitation français fourni avec l'application. La disponibilité et la
qualité dépendent du moteur vocal installé sur Android. Installer une voix française
dans les paramètres de synthèse vocale du téléphone peut être nécessaire. Le bouton
FR ne crée pas un fichier audio MP3 téléchargeable. Le téléchargement proposé dans
cette version concerne les récitations arabes.

HORS LIGNE
- La première connexion Internet est nécessaire pour charger les données.
- Le texte et les récitations arabes doivent être chargés/téléchargés avant l'usage hors ligne.
- Les voix françaises dépendent du moteur vocal Android et ne sont pas garanties hors ligne.
- Les téléchargements sont conservés dans IndexedDB du navigateur/PWA. Ne pas effacer
  les données du navigateur si l'on souhaite les conserver.

SOURCES ET DROITS
- Texte arabe : Tanzil Project, texte Uthmani. https://tanzil.net
- Traduction : Muhammad Hamidullah via AlQuran Cloud. Vérifier les conditions de
  redistribution et d'utilisation commerciale avant publication.
- Récitations : AlQuran Cloud / Islamic Network CDN. Les enregistrements peuvent
  rester soumis aux droits des récitateurs et ayants droit. Obtenir les autorisations
  nécessaires avant de redistribuer les fichiers dans une application commerciale.
- Hadiths : références indiquées à côté de chaque texte. Vérifier les traductions,
  numérotations et éditions avant publication définitive.

PUBLICITÉ
Aucun identifiant publicitaire actif n'est inclus. L'espace d'accueil est un simple
emplacement réservé. Pour une application Android, utiliser AdMob et ses identifiants
réels après configuration du compte, consentement et politique de confidentialité.
Ne pas afficher d'annonce pendant la lecture, l'écoute ou les invocations.

INSTALLATION DE TEST
Héberger le dossier sur un domaine HTTPS, puis ouvrir l'adresse dans Chrome Android.
Utiliser le menu Chrome > Installer l'application / Ajouter à l'écran d'accueil.

COMPILATION APK
Pour obtenir un APK Android, empaqueter cette PWA avec Bubblewrap (TWA) ou Capacitor,
puis compiler et signer avec Android SDK / Android Studio. Le SDK Android n'est pas
présent dans cet environnement : aucun APK n'a été généré dans cette archive.
