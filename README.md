# Jeux de réflexion

Ce dépôt contient deux jeux jouables dans le navigateur, sans installation ni dépendance.

## Morpion

[Jouer au morpion](https://oceanehes.github.io/Morpion/morpion.html)

Deux joueurs jouent à tour de rôle sur une grille de 3 × 3. X commence. Trois symboles alignés font gagner la partie ; une grille pleine sans alignement donne un match nul. **Nouvelle partie** remet la grille à zéro.

## Code secret

[Jouer au Code secret](https://oceanehes.github.io/Morpion/code-secret.html)

Trouvez le code caché de quatre couleurs en dix essais au maximum. Les répétitions sont permises. Après chaque proposition, le jeu indique le nombre de couleurs bien placées et mal placées.

### API de test 0.2

L’API de test est accessible dans le navigateur à l’adresse [code-secret.html?test=1](https://oceanehes.github.io/Morpion/code-secret.html?test=1), via `window.codeSecretTest`. Sans le paramètre `test=1`, cet objet n’est pas exposé. L’API et l’interface utilisent le même état et le même moteur.

Méthodes : `getConfig()`, `startGame(options?)`, `submitGuess(guess)` et `getState()`. Les appels de mutation sont asynchrones ; attendez leur promesse avant le prochain appel.

