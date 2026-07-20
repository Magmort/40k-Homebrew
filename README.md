# Front de Vespator

Règles maison de Warhammer 40,000 pour la campagne **Front de Vespator**, système 500 Worlds.
Hybride entre la V7 et la V10, remanié pour une activation alternée.

## Organisation du dépôt

- **`md/`** : la version lisible en ligne. Cliquez sur un fichier, GitHub l'affiche directement.
  C'est ici qu'on relit, qu'on commente et qu'on propose des corrections.
- **`docx/`** : les documents Word d'origine, avec la mise en page. C'est la version à imprimer
  et à emmener sur la table de jeu.

Les deux contiennent le même texte. Le `.docx` fait foi pour la mise en page, le `.md` pour la
relecture. Toute correction validée doit être reportée dans les deux.

| Document | Contenu |
| --- | --- |
| `regles_wh40k_v4` | Règles de base. Le document central. |
| `VespatorFront_Missions_FR` | Les 6 missions de campagne, avec leurs cartes. |
| `Theatres_CinqCentsMondes_FR` | Les 9 théâtres et leurs modificateurs de monde. |
| `AdMech_Abilities_FR` | Faction Adeptus Mechanicus. Révisée. |
| `Votann_Abilities_FR` | Faction Leagues of Votann. Révisée. |
| `Tau_Abilities_FR` | Faction T'au Empire. Nettoyée, mais pas encore révisée sur le fond. |

## Structure des règles

Une partie se joue en rounds de trois phases : **Commandement**, **Action**, **Combat**.
Les joueurs activent leurs unités **en alternance** pendant la phase d'Action : il n'y a pas
de « tour du joueur », donc pas de formulation du type « votre phase ».

## Conventions de rédaction

Ces règles ont été appliquées à l'ensemble des fichiers. Merci de les respecter en contribuant.

- On écrit **modèle**, jamais « figurine ».
- Les mots-clés d'arme s'écrivent en majuscules entre crochets : `[ASSAUT]`, `[TOUCHES FATALES]`,
  `[TOUCHES SOUTENUES X]`, `[BLESSURES DÉVASTATRICES]`, `[LOURD]`, `[ATTAQUES BONUS]`, `[DANGEREUX]`.
  La liste complète fait foi dans la section « Aptitudes d'Arme » des règles de base.
- Le tiret cadratin `—` est banni. On utilise `:` ou `,`.
- Terminologie : **Ébranlement** (et non « test de moral »), **Désengagement** (et non « repli »),
  **blessures mortelles**, **Couvert Léger** et **Couvert Complet**, **Portée d'Engagement**.
- `CORE` n'existe pas : il se traduit par **INFANTERIE, MARCHEUR ou MONTÉ**.
  Exception : là où la source anglaise écrivait `CORE INFANTRY`, on garde **INFANTERIE** seule.
- Une règle non validée est marquée `[À COMPLÉTER]`.

## Contribuer

Les fichiers `.docx` sont binaires : Git ne sait pas fusionner deux modifications simultanées
du même fichier. **Annoncez sur quel fichier vous travaillez avant de commencer**, ou passez par
une branche et une Pull Request.

Aucune règle n'est ajoutée sans avoir été discutée et validée au préalable.
