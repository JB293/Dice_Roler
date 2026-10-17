# Dice Roler 🎲

**Dice Roler** est une application Android moderne et interactive développée avec **Jetpack Compose**. Elle permet aux utilisateurs de lancer un dé virtuel d'un simple clic. Ce projet sert d'exemple pratique pour illustrer la gestion d'état (*state management*) et la construction d'interfaces déclaratives.

## 🚀 Fonctionnalités

*   **Lancer de dé aléatoire** : Génère un nombre entre 1 et 6 à chaque clic sur le bouton.
*   **Interface Réactive** : L'image du dé et sa description s'actualisent instantanément grâce à la recomposition de Compose.
*   **Design Material 3** : Utilisation des derniers standards de design Android pour une interface épurée et moderne.
*   **Optimisé pour la performance** : Utilise les délégués de propriété pour une gestion efficace de la mémoire.

## 🛠 Stack Technique

*   **Langage** : [Kotlin 2.0.21](https://kotlinlang.org/)
*   **UI Framework** : [Jetpack Compose](https://developer.android.com/jetpack/compose) avec Material 3.
*   **Gestion d'état** : Utilisation de `remember` et `mutableIntStateOf` avec les opérateurs `getValue` et `setValue`.
*   **Outils de build** : Gradle (Kotlin DSL) avec le système de **Version Catalogs** (`libs.versions.toml`).
*   **Compatibilité** : Compile SDK 35, Target SDK 35, Min SDK 24.

## 📋 Prérequis

*   **Android Studio Ladybug** (2024.2.1) ou une version plus récente.
*   **JDK 11** ou supérieur.
*   **SDK Android 35** installé via le SDK Manager.
*   Un appareil physique Android ou un émulateur (API 24 minimum).

## ⚙️ Installation et Configuration

1.  **Cloner le dépôt** :
    ```bash
    git clone https://github.com/votre-utilisateur/DiceRoler.git
    ```
2.  **Ouvrir le projet** :
    *   Lancez Android Studio.
    *   Sélectionnez `File > Open` et choisissez le dossier du projet.
3.  **Synchroniser Gradle** :
    *   Android Studio devrait détecter le fichier `build.gradle.kts`. Cliquez sur "Sync Project with Gradle Files" si nécessaire.
4.  **Exécuter l'application** :
    *   Connectez un appareil ou lancez un émulateur.
    *   Cliquez sur le bouton **Run** (flèche verte) en haut d'Android Studio.

## 🧩 Aperçu du Code (Logic)

Le cœur de l'application se trouve dans `MainActivity.kt`.