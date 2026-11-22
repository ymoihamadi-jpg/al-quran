AL-QURAN — VERSION 3 (PWA / BASE ANDROID)
=========================================

Cette archive contient le code source d'une application web progressive (PWA).
Ce n'est PAS encore un APK Android compilé ou signé.

AMÉLIORATIONS DE LA VERSION 3
- Interface mobile retravaillée : vert profond, or, cartes, navigation et mode sombre.
- Liste dynamique des 114 sourates depuis AlQuran Cloud.
- Texte arabe Uthmani et traduction française Muhammad Hamidullah.
- Choix de cinq récitateurs arabes via AlQuran Cloud.
- Lecture audio arabe verset par verset et téléchargement des audios d'une sourate.
- Lecture française par synthèse vocale, avec réglage de voix grave et masculine si le moteur Android fournit une voix française masculine.
- 12 fiches de hadiths avec références de recueils.
- 11 invocations avec références coraniques ou de hadiths.
- Tasbih numérique avec compteur conservé sur l'appareil.
- Mise en cache de l'interface et stockage local des textes, audios et favoris de versets.
- Recherche parmi les sourates, reprise de la dernière lecture et favoris par verset.

IMPORTANT — VOIX FRANÇAISE
La voix française est générée par le moteur de synthèse vocale installé sur le téléphone.
L'application règle une tonalité plus grave et cherche une voix française masculine quand
le système en propose une. Les noms et le genre des voix disponibles dépendent d'Android.
Ce n'est PAS un enregistrement humain fourni avec l'application, ni un fichier MP3.
Pour une vraie voix humaine enregistrée, il faudra obtenir des fichiers audio de traduction
française dont les droits de diffusion et de redistribution sont explicitement autorisés.

CORAN COMPLET ET HORS LIGNE
La liste contient les 114 sourates. Les textes et audios de chaque sourate sont chargés
à la demande. La connexion est nécessaire au premier chargement de chaque contenu.
Le texte et les récitations arabes téléchargés sont conservés dans IndexedDB. La voix
française dépend du moteur vocal Android et n'est pas garantie hors ligne.

SOURCES ET DROITS
- Texte arabe : Tanzil Project, texte Uthmani. https://tanzil.net
- Traduction : Muhammad Hamidullah via AlQuran Cloud. Vérifier les conditions de
  redistribution et d'utilisation commerciale avant publication.
- Récitations : AlQuran Cloud / Islamic Network CDN. Les enregistrements peuvent rester
  soumis aux droits des récitateurs et ayants droit. Obtenir les autorisations nécessaires.
- Hadiths et invocations : références affichées dans l'application. Vérifier les traductions,
  numérotations et éditions avant publication définitive ou usage d'étude religieuse.

PUBLICITÉ
Aucun identifiant publicitaire actif n'est inclus. L'emplacement de l'accueil est décoratif.
Pour une application Android, configurer AdMob avec de vrais identifiants, les consentements
et une politique de confidentialité complète. Ne pas afficher d'annonce pendant la lecture.

COMPILATION APK
Cette archive n'est pas un APK. Pour produire un APK, il faut empaqueter la PWA avec
Bubblewrap/TWA ou Capacitor, puis compiler et signer avec Android SDK. La version hébergée
sur un domaine HTTPS peut servir à tester la PWA et à préparer un paquet Android.
