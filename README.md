# ❄️ Le Grand Quiz des 60 ans de Xavier

Quiz interactif façon plateau TV, ambiance Grand Nord.

- **La TV** (un ordinateur branché dessus) affiche les questions, les réponses et le classement.
- **Les invités** scannent le QR code et répondent sur leur téléphone. Chacun joue pour soi, sans chrono.
- **Xavier** scanne son propre QR code : son téléphone devient la télécommande. Il lance les questions (elles s'enchaînent dans l'ordre, manche après manche), révèle les bonnes réponses, choisit ses réponses préférées aux questions ouvertes et peut contester (+1 / −1 point).

Tout tient dans un seul fichier : `index.html`.

## Mettre en ligne (Netlify, comme le quiz du judo)

1. Sur Netlify : **Add new site → Import an existing project → GitHub → Xavier60ans**.
2. Pas de commande de build, dossier de publication : `/` (la racine).
3. Le site est en ligne : ouvre son adresse sur l'ordinateur branché à la TV.

## Le soir de la fête

1. Sur l'ordinateur de la TV, ouvre le site puis clique sur **Lancer la soirée**.
2. Les invités scannent le grand QR code et tapent leur prénom.
3. Xavier scanne le petit QR code « Télécommande de Xavier ».
4. Xavier appuie sur **C'est parti !** : la première question s'affiche directement.
5. Après chaque révélation, **Question suivante**. Les questions s'enchaînent dans l'ordre de l'éditeur, puis le podium s'affiche tout seul à la fin.

En secours, le bouton **🎮 Piloter ici** de l'ordinateur ouvre la même télécommande sur l'écran de l'ordinateur.
Si la page de la TV se recharge par erreur, **Reprendre la partie** garde les scores, et les invités se reconnectent tout seuls.

## Types de questions

| Type | Les invités | Xavier |
|---|---|---|
| Choix multiples (2 à 5 réponses) | touchent une réponse | touche la ou les bonnes réponses, puis « Révéler » |
| Vrai / Faux | touchent Vrai ou Faux | révèle la bonne |
| Réponse libre | écrivent ce qu'ils veulent | choisit ses coups de cœur (+1 point chacun) |
| Nombre à deviner | tapent un nombre | tape la vraie valeur (ou elle est déjà enregistrée) : le plus proche gagne |

On peut changer de réponse tant que Xavier n'a pas révélé.

## Modifier les questions

Accueil → **✏️ Modifier les questions**. Tout est enregistré dans le navigateur de l'ordinateur, photos comprises.
Pour jouer sur un autre ordinateur : **Exporter** ici, puis **Importer** là-bas.

L'ordre des manches et des questions dans l'éditeur (flèches ↑ ↓) est l'ordre du jeu. Les manches vides sont sautées.
Les manches bonus « Vrai ou faux express », « Photo mystère », « Qui a dit ça ? » et « Le Grand Nord en chiffres » sont vides au départ, à remplir dans l'éditeur.

## Tester avant la fête

Accueil → **🧪 Tester sur cet ordi** : les boutons « Ouvrir un invité » et « Ouvrir la télécommande » ouvrent des onglets qui jouent entre eux sans internet. À faire depuis le site en ligne (pas en double-cliquant sur le fichier).
