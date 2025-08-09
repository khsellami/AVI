# AVI Project
**Assistant Vocal Intelligent (AVI)** is a smart voice assistant project that combines Python backend processing with a modern web frontend. AVI is designed to interpret voice commands, perform intelligent actions, and provide interactive feedback through both audio and visual interfaces.

## Structure
```
infos.txt
main.py
engine/
    command.py
    config.py
    features.py
    __pycache__/
www/
    controller.js
    index.html
    main.js
    script.js
    style.css
    assets/
        audio/
            start_sound.mp3
        img/
            logo.ico
        vendore/
            texllate/
                animate.css
                jquery.fittext.js
                jquery.lettering.js
                style.css
```
### Détails sur la structure

- **infos.txt** : Fichier d'informations ou de configuration pour le projet.
- **main.py** : Point d'entrée principal du backend Python. Lance l'assistant vocal et gère la logique centrale.
- **engine/** : Contient les modules Python pour le traitement des commandes vocales et la configuration.
    - `command.py` : Analyse et exécute les commandes vocales reçues.
    - `config.py` : Gère les paramètres et options de configuration de l'assistant.
    - `features.py` : Implémente des fonctionnalités intelligentes supplémentaires.
    - `__pycache__/` : Fichiers compilés Python pour accélérer l'exécution.
- **www/** : Interface web pour l'utilisateur.
    - `index.html` : Page principale de l'application web.
    - `controller.js` : Gère la communication entre le frontend et le backend, ainsi que les interactions utilisateur.
    - `main.js`, `script.js` : Scripts JavaScript pour l'animation, la logique de l'interface et la gestion des événements.
    - `style.css` : Feuille de style pour l'apparence de l'interface web.
    - **assets/** : Ressources statiques pour l'interface web.
        - **audio/** : Fichiers audio utilisés pour les notifications ou le retour vocal (ex : `start_sound.mp3`).
        - **img/** : Images et icônes pour le branding (ex : `logo.ico`).
        - **vendore/** : Librairies et plugins tiers.
            - **texllate/** : Effets d'animation et de texte (`animate.css`, `jquery.fittext.js`, `jquery.lettering.js`, `style.css`).

Cette organisation permet de séparer le traitement backend (Python) de la présentation frontend (web), facilitant la maintenance et l'évolution du projet. Le backend gère l'interprétation des commandes vocales et la logique intelligente, tandis que le frontend offre une interface interactive et visuelle à l'utilisateur.

## Getting Started

### Python Backend
- Entry point: `main.py`
- Modules: `engine/command.py`, `engine/config.py`, `engine/features.py`

To run the backend:

```powershell
python main.py
- Open `www/index.html` in your browser to view the web interface.

## Assets
- Audio: `www/assets/audio/start_sound.mp3`
- Vendor libraries: `www/assets/vendore/texllate/`


