**Agents de l'Imperium**

Capacités & Règles de faction

| **Note de cohérence (portage adapté au système 500 Worlds)** |
| --- |
| Portage **bloc par bloc** : le **wording officiel FR** des effets (doc agents-imperium) est repris tel quel, seules les mécaniques incompatibles étant converties au système maison. Couche système appliquée : « phase Psychique » → **action psychique** (« valeur de charge warp » → **valeur de manifestation** ; durée « jusqu'à la prochaine phase Psychique » → **jusqu'au début de votre prochaine phase de Commandement**) ; « test de Moral » → **Ébranlement** ; « Overwatch » → **Tirs en État d'Alerte** ; « phase de Tir » → **Phase d'Action (Tir)** ; « point de Commandement » → **PC**. Les textes d'ambiance des fiches d'unité ne sont pas repris ; les intitulés d'invocation (encadrés d'Ordo) le sont. |
| **Passe de cohérence vs `regles_wh40k_v4.md` (version à jour du repo) — décisions appliquées :** |
| **1. Sous-système psychique — `[OK]`.** La section **« Actions Psychiques »** du core définit le cadre : action de la **Phase d'Action** ; manifestation sur **2D6 ≥ valeur de manifestation** ; annulation par **Test de Refus** ; un PSYKER choisit un **domaine** et connaît **1 pouvoir** (1D6). Discipline Téléthésie et terme « valeur de manifestation » cohérents. *(Réserve : le core limite un PSYKER à 1 pouvoir ; les fiches accordant plusieurs pouvoirs relèvent des datasheets, hors périmètre.)* |
| **2. Terreur — `[RÉSOLU]`.** L'Ébranlement se réussit sur **2D6 ≥ Cd** (Cd haut = plus dur) : le modificateur d'origine **-1 Cd** est **inversé en +1 Cd** pour conserver l'effet pénalisant. |
| **3. Interrogation Mentale — `[RÉSOLU]`.** « Gagnez 1 PC » (sans objet en jeu) remplacé par **regain de l'activation d'un Stratagème coûtant ≤ 1 PC**. |
| **4. Inclusion des Agents — `[RÉSOLU]`.** Règle **conservée telle quelle** (exploitable en l'état). Détachements maintenus : **Patrouille, Bataillon, Brigade**. Retirés car absents du core : Patrouille d'Abordage, Les Arches Fatidiques, et l'interdiction Frères de Couvain. |
| **5. Entrée en réserve (Agent Indépendant) — `[RÉSOLU]`.** Renvoyée à **Frappe en Profondeur** ; note de reconversion supprimée. À vérifier au niveau des datasheets : elles doivent posséder la règle Frappe en Profondeur. |
| **6. Non-Aligné — `[RÉSOLU]`.** « Neutre » (VF officielle) remplacé par le mot-clé maison **Non-Aligné** dans *Proie* (Ordo Xenos). |
| **7. Traçage Psychique — `[RÉSOLU]`.** L'ignorance de « Attention, Monsieur ! » (règle absente) est remplacée par l'octroi du mot-clé **[PRÉCISION]** aux tirs de l'unité amie contre le Personnage désigné. |
| **8. Divers — `[RÉSOLU]`.** Mot-clé **Motard → MONTÉ** (Incantation Protectrice). Condition « Si votre armée est Réglementaire » omise (toujours vraie). *Reste ouvert :* le core mentionne les Transports Dédiés sans procédure d'embarquement détaillée, dont dépend *Autorité de l'Inquisition*. |
| **Conventions système appliquées :** « phase Psychique » → **action psychique** / durée → **jusqu'au début de votre prochaine phase de Commandement** ; « valeur de charge warp » → **valeur de manifestation** ; « test de Moral » → **Ébranlement** ; « phase de Tir » → **Phase d'Action (Tir)** ; « Overwatch » → **Tirs en État d'Alerte** ; « point de Commandement » → **PC**. Datasheets et profils d'armes non inclus. |

# Mot-clé `<ORDO>`

Certaines unités ont le mot-clé `<ORDO>`. À l'inclusion d'une telle unité, choisissez son Ordo et remplacez `<ORDO>` par ce nom partout sur sa fiche. Ordos disponibles : **ORDO HERETICUS**, **ORDO MALLEUS**, **ORDO XENOS**, **ORDO MINORIS**.

# Capacités Communes

*Aptitudes partagées par plusieurs unités de la faction.*

## Agent de l'Imperium

Vous pouvez inclure 1 unité Agent de l'Imperium (hormis les unités Déchus) dans chaque Détachement de Patrouille, Bataillon et Brigade Imperium de votre armée, sans que ces unités n'occupent de choix de Rôle sur le Champ de Bataille dans ces Détachements. L'inclusion d'une unité Agent de l'Imperium n'empêche pas les autres unités de son Détachement de bénéficier de leurs aptitudes de Détachement, et elle n'empêche pas d'autres unités de votre armée de bénéficier d'aptitudes requérant que chaque figurine de votre armée ait l'aptitude en question.

Une unité Agent de l'Imperium incluse de la sorte est ignorée pour les règles qui exigent que toutes les unités d'un Détachement partagent au moins 1 mot-clé de Faction en commun, et lorsque vous déterminez la Faction de votre armée.

| *Note (point 4) : conservé tel quel, exploitable en l'état. Seuls les Détachements d'origine absents du système maison ont été retirés de la liste (Patrouille d'Abordage, Les Arches Fatidiques) ainsi que l'interdiction Frères de Couvain (Détachement inexistant). La condition « Si votre armée est Réglementaire » est omise (toujours vraie : armées toujours Battle-forged).* |
| --- |

## Proie

Les unités ayant le mot-clé Ordo Malleus, Ordo Hereticus, Ordo Xenos ou Ordo Minoris gagnent l'aptitude correspondante ci-dessous :

- **Ordo Malleus** : Quand vous résolvez une attaque d'une figurine de cette unité qui cible une unité Chaos ou Démon, vous pouvez relancer le jet de touche et vous pouvez relancer le jet de blessure.
- **Ordo Hereticus** : Quand vous résolvez une attaque d'une figurine de cette unité qui cible une unité Chaos ou Psyker, vous pouvez relancer le jet de touche et vous pouvez relancer le jet de blessure.
- **Ordo Xenos** : Quand vous résolvez une attaque d'une figurine de cette unité qui cible une unité qui n'est pas une unité Chaos, Imperium ou Non-Aligné, vous pouvez relancer le jet de touche et vous pouvez relancer le jet de blessure.
- **Ordo Minoris** : Quand vous résolvez une attaque d'une figurine de cette unité qui cible une unité Personnage, vous pouvez relancer le jet de touche et vous pouvez relancer le jet de blessure.

## Assignation Secrète

Les unités ayant le mot-clé Officio Assassinorum gagnent les aptitudes suivantes :

- Cette figurine ne peut jamais avoir de Trait de Seigneur de Guerre.
- Si la Faction de votre armée est Agents de l'Imperium, lors de l'étape Déclarer les Formations de Bataille, vous pouvez remplacer une figurine dotée de cette aptitude par une autre figurine Officio Assassinorum, à condition que la valeur en points de la nouvelle figurine ne dépasse pas celle de la figurine remplacée. Votre armée ne peut pas inclure de doublons de la même figurine (au maximum 1 Vindicare Assassin, 1 Culexus Assassin, 1 Eversor Assassin et 1 Callidus Assassin).

*(Note : l'entrée en réserve des Assassins est désormais couverte par la règle **Frappe en Profondeur** ; s'assurer que les fiches concernées en disposent.)*

## Autorité de l'Inquisition

Les unités Infanterie ayant cette aptitude peuvent embarquer dans n'importe quelle figurine Transport Imperium, même si cette dernière ne permet normalement pas à des figurines ayant d'autres mots-clés de Faction de le faire. Toutes les autres restrictions s'appliquent (ex : les figurines Terminator peuvent seulement embarquer dans des Transports permettant aux figurines Terminator de le faire).

Vous ne pouvez pas inclure plus de 1 unité Inquisiteur dans un détachement composé uniquement d'unités Inquisition.

| *Note (point 8) : les règles de base mentionnent les Transports Dédiés mais pas de procédure d'embarquement détaillée ; cette aptitude est portable mais en dépend. Condition « Si votre armée est Réglementaire » omise (toujours vraie côté maison).* |
| --- |

## Sagesse Incontestable (Aura)

Tant qu'une unité Imperium amie est à 6" de cette figurine, les figurines de l'unité peuvent utiliser la caractéristique de Commandement de cette figurine au lieu de la leur.

# Discipline Psychique : Téléthésie

*Téléthésie est un **domaine de pouvoirs psychiques** au sens de la section « Actions Psychiques » des règles de base. Une unité PSYKER qui choisit ce domaine lance **1D6** sur la table ci-dessous pour déterminer l'unique pouvoir qu'elle connaît (le core limite un PSYKER à 1 pouvoir). Une unité appartenant à un Ordo peut connaître à la place le pouvoir propre à cet Ordo (encadrés « Pouvoirs d'Ordo »). On manifeste un pouvoir en action psychique : **2D6 ≥ valeur de manifestation**.*

> **Conversions maison appliquées aux pouvoirs ci-dessous :** « valeur de charge warp de X » → **valeur de manifestation de X** (2D6 ≥ valeur, cf. core) ; durée « jusqu'à la prochaine phase Psychique » → **jusqu'au début de votre prochaine phase de Commandement** ; « test de Moral » → **test d'Ébranlement** ; « phase de Tir » → **Phase d'Action (Tir)** ; « point de Commandement » → **PC**. Le reste du texte est repris tel quel.

**1 — Terreur**
*Malédiction :* Terreur a une valeur de manifestation de 6. S'il est manifesté, choisissez 1 unité ennemie à 18" et visible de ce Psyker. Jusqu'au début de votre prochaine phase de Commandement :

- Ajoutez 1 à la caractéristique de Commandement des figurines de l'unité.
- L'unité ne peut pas tirer en État d'Alerte.

*(Adaptation maison : l'Ébranlement se réussit sur 2D6 ≥ Cd, un Cd plus élevé étant plus difficile à réussir ; le modificateur d'origine -1 Cd est donc **inversé en +1 Cd** pour conserver l'effet pénalisant voulu.)*

**2 — Force Psychique**
*Bénédiction :* Force Psychique a une valeur de manifestation de 4. S'il est manifesté, choisissez 1 unité Imperium amie à 12" de ce Psyker. Jusqu'au début de votre prochaine phase de Commandement, à chaque test d'Ébranlement pour l'unité choisie, ne jetez pas le dé ; le test est automatiquement réussi.

**3 — Domination**
*Malédiction :* Domination a une valeur de manifestation de 6. S'il est manifesté, choisissez 1 figurine ennemie (hormis les figurines Véhicule) à 12" de ce Psyker et jetez 3D6. Si le résultat est supérieur ou égal à la caractéristique de Commandement de la figurine ennemie, elle peut immédiatement tirer avec 1 arme comme à votre Phase d'Action (Tir), ou effectuer 1 attaque comme à la Phase de Combat. Dans tous les cas, traitez la figurine ennemie comme une unité séparée faisant partie de votre armée tant qu'elle tire ou effectue l'attaque de corps à corps.

**4 — Interrogation Mentale**
*Malédiction :* Interrogation Mentale a une valeur de manifestation de 6. S'il est manifesté, choisissez 1 figurine Personnage ennemie à 12" et visible de ce Psyker.

- Jusqu'au début de votre prochaine phase de Commandement, à chaque attaque de la figurine ennemie, soustrayez 1 au jet de touche.
- Jetez 3D6 : si le résultat est supérieur ou égal à la caractéristique de Commandement de la figurine ennemie, vous regagnez l'activation d'un Stratagème coûtant au maximum 1 PC (ce Stratagème peut être activé une fois de plus ce round).

*(Adaptation maison : côté 500 Worlds les PC ne sont pas dépensés en jeu ; le gain « 1 PC » d'origine est converti en regain d'activation d'un Stratagème à ≤ 1 PC.)*

**5 — Traçage Psychique**
*Bénédiction :* Traçage Psychique a une valeur de manifestation de 7. S'il est manifesté, choisissez 1 unité Personnage ennemie ne contenant que des figurines ayant une caractéristique de Points de Vie de 9 ou moins et étant à 18" et visible de ce Psyker. Puis, choisissez 1 unité Infanterie `<ORDO>` amie à 6" de ce Psyker. Jusqu'à la fin de votre prochaine Phase d'Action (Tir), chaque fois qu'une figurine de l'unité Infanterie `<ORDO>` amie choisie sélectionne l'unité Personnage ennemie désignée comme cible d'une de ses attaques de tir, cette attaque gagne le mot-clé **[PRÉCISION]**.

*(Adaptation maison : l'effet d'origine ignorait « Attention, Monsieur ! » (règle absente du core). Il est converti en octroi de **[PRÉCISION]** — le tireur peut allouer la blessure directement à un modèle visible de son choix — pour permettre de viser le Personnage désigné.)*

**6 — Castigation**
*Feu Sorcier :* Castigation a une valeur de manifestation de 6. S'il est manifesté, choisissez 1 unité ennemie à 18" et visible de ce Psyker et jetez 3D6 : si le résultat est supérieur à la plus basse caractéristique de Commandement de l'unité ennemie choisie, celle-ci subit D3 blessures mortelles.

## Pouvoirs d'Ordo

**Ordo Hereticus — Purge**
*Le psyker se fait un fouet de la culpabilité de l'ennemi, et lacère l'esprit de sa victime avec.*
*Malédiction :* Purge a une valeur de manifestation de 6. S'il est manifesté, choisissez 1 unité ennemie à 12" de ce Psyker.

- Jusqu'au début de votre prochaine phase de Commandement, soustrayez 1 à la caractéristique d'Attaques des figurines de l'unité ennemie (jusqu'à un minimum de 1).
- Jetez 2D6 ; si le résultat est supérieur ou égal à la plus haute caractéristique de Commandement de l'unité ennemie choisie, jusqu'au début de votre prochaine phase de Commandement, à chaque attaque d'une figurine de l'unité ennemie choisie, soustrayez 1 au jet de touche.

**Ordo Xenos — Voile Psychique**
*Le psyker invoque un voile scintillant qui protège ses alliés.*
*Bénédiction (Aura) :* Voile Psychique a une valeur de manifestation de 5. S'il est manifesté, jusqu'au début de votre prochaine phase de Commandement, les unités Ordo Xenos amies à 6" de ce Psyker peuvent être choisies comme cibles d'attaques seulement si elles sont l'unité ennemie visible la plus proche, et peuvent être choisies comme cible d'une charge seulement si elles sont à 6" de l'unité qui charge.

**Ordo Malleus — Incantation Protectrice**
*Le psyker entonne une invocation et dresse un rempart empyréen autour de ses alliés.*
*Bénédiction :* Incantation Protectrice a une valeur de manifestation de 6. S'il est manifesté, choisissez 1 unité Infanterie Imperium ou Monté Imperium amie à 12" de ce Psyker. Jusqu'au début de votre prochaine phase de Commandement, les figurines de l'unité ont une sauvegarde invulnérable de 5+.
