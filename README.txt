------------------------------------------------------------
                   LED Matrix Control via STM32
------------------------------------------------------------

Description:
-------------
Ce projet permet de contrôler une matrice de LEDs 4x4 à l'aide d'un microcontrôleur **STM32F410**. Un programme en **C** ou **Python** sur un ordinateur permet d'envoyer des commandes pour afficher des messages ou des animations sur la matrice de LEDs. Les commandes peuvent inclure l'affichage de caractères, la création d'animations ou l'effet de lumière.

Fonctionnalités:
----------------
- **Affichage de caractères** : Envoyer des commandes pour afficher des lettres ou chiffres sur la matrice de LEDs.
- **Animations LED** : Créer des animations simples comme des effets de clignotement ou des déplacements de lumière.
- **Contrôle depuis un PC** : Envoi de commandes depuis un ordinateur en utilisant un programme en C ou Python.
- **Personnalisation** : Modification du code sur l'ordinateur pour personnaliser l'affichage de la matrice LED.

Matériel utilisé:
-----------------
- **Microcontrôleur STM32F410** : Le microcontrôleur qui pilote la matrice de LEDs 4x4.
- **Matrice de LEDs 4x4 RGB** : Matrice contenant 16 LEDs de différentes couleurs.
- **Driver de LEDs STP04CM05XTTR** : Circuit intégré utilisé pour contrôler les LEDs de la matrice.
- **Résistances** : Utilisées pour limiter le courant passant par les LEDs.
- **Oscilloscope / Multimètre** : Pour tester et déboguer les signaux électriques.

Logiciel:STM32CubeIDE
---------
- **Programme en C ** : Permet de contrôler la matrice de LEDs via le microcontrôleur STM32. Le programme communique avec le microcontrôleur par une interface série (UART ou USB, selon la configuration)..
- Le programme C permet d'envoyer des commandes telles que :
  - Affichage de texte sur la matrice.
  - Contrôle de l'intensité lumineuse des LEDs.
  - Création d'animations simples.


  Plus de détail dans le fichier pdf "Rapport" ou "Présentation de projet".