SHALOM — Projet Android natif (WebView hors ligne)

CE QUE CONTIENT CE PROJET
- Un projet Android Studio/Kotlin qui enveloppe le prototype SHALOM V3.
- L'interface HTML/CSS/JavaScript est embarquée dans l'application : elle s'ouvre sans hébergement web.
- JavaScript et stockage local activés pour les contenus et réglages de l'application.
- Sélecteur Android de fichiers pour importer les contenus.
- Navigation retour Android.

IMPORTANT
Ce dossier est un projet Android Studio prêt à être compilé, pas encore un APK compilé.
L'environnement de préparation ne possède pas le SDK Android ni Gradle installés, donc je ne peux pas produire ni vérifier un fichier .apk ici.
L'authentification de la version actuelle reste locale à l'appareil; elle ne constitue pas une authentification serveur.
La synchronisation cloud entre appareils n'est pas incluse.
Les fichiers importés sont stockés dans le stockage WebView et restent soumis aux limites de stockage du téléphone.

POUR COMPILER L'APK
1. Installer Android Studio sur un ordinateur.
2. Ouvrir le dossier SHALOM-Android dans Android Studio.
3. Laisser Android Studio installer le SDK Android 35 et synchroniser Gradle.
4. Choisir Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Récupérer l'APK dans app/build/outputs/apk/debug/app-debug.apk.
6. Pour distribuer publiquement, créer une version signée via Build > Generate Signed Bundle / APK.

Configuration : applicationId org.shalom.app, version 3.0, minSdk 23 (Android 6.0+).
