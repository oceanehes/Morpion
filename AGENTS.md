# Consignes du projet

- Le dépôt contient le morpion et le jeu Code secret ; chacun garde sa page autonome.
- Le Code secret est une PWA : conserver le manifeste, les icônes et le service worker fonctionnels sous le chemin GitHub Pages `/Morpion/`.
- Préserver les règles, l’interface française, l’accessibilité clavier et les libellés accessibles.
- Garder une mise en page utilisable sur mobile et ordinateur et respecter la préférence de réduction des animations.
- Pour le Code secret, l’interface et l’API 0.2 doivent partager le même moteur et le même état. Ne jamais exposer le code secret dans l’API.
- `window.codeSecretTest` ne doit être exposé que lorsque l’URL contient `?test=1`.
- Les pages fonctionnent sans dépendance ni étape de compilation.
