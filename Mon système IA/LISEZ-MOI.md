# Mon système IA

Votre second cerveau : un dossier de fichiers texte (`.md`) qui vous appartient. Vous l'écrivez avec **Obsidian**, et l'IA le relit pour travailler avec vous.

Vous décrivez une fois qui vous êtes et comment vous travaillez ; ensuite, chacune de vos demandes en profite. Si l'outil change demain, vos fichiers restent : c'est ce qui vous rend autonome.

> **La règle d'or** : ne déléguez jamais à l'IA une compétence que vous n'avez pas encore acquise.

---

## Ce qu'il y a dedans

```
Mon système IA/
├─ LISEZ-MOI.md          ← vous êtes ici
├─ CLAUDE.md             ← les instructions que l'IA lit avant chaque tâche
├─ 00 - Moi/
│   ├─ contexte.md       ← qui je suis, mon poste, mon entreprise d'accueil
│   ├─ ton.md            ← ma façon d'écrire
│   ├─ valeurs.md        ← ce qui compte pour moi (personnel)
│   └─ Ma charte IA.md   ← mes règles d'usage de l'IA
├─ 01 - Skills/
│   ├─ socratique/       ← m'aide à trouver mes propres réponses
│   ├─ challenge/        ← met mon travail à l'épreuve
│   ├─ ton/              ← crée mon fichier ton.md
│   ├─ valeurs/          ← découvre mes valeurs (méthode Demartini)
│   ├─ demandes-clients/ ← prépare une réponse aux demandes et réclamations de clients B2B
│   └─ etude-de-marche/  ← mène une étude de marché sourcée, en trois temps
├─ 02 - Cours/           ← mes notes de chaque module
└─ 03 - Artefacts/       ← ce que l'IA produit pour moi
    ├─ Brainstorms/      ← les comptes rendus du skill Challenge
    └─ Rapports/         ← les livrables (étude de marché…)
```

Un **skill**, c'est un prompt écrit une fois, rangé dans un fichier (`SKILL.md`), que l'IA relit à chaque fois que vous l'appelez.

---

## Installer (15 minutes)

### 1. Obsidian
1. Téléchargez Obsidian sur obsidian.md (gratuit).
2. Choisissez **« Ouvrir un dossier comme coffre »** et sélectionnez le dossier `Mon système IA`.

### 2. Brancher l'IA : choisissez une voie

**Voie A · en salle (recommandée) : Claude, application ou site web**
1. Créez un projet « Mon système IA ».
2. Collez le contenu de [[CLAUDE]] dans les instructions du projet.
3. Ajoutez les fichiers de `00 - Moi/` aux connaissances du projet. Pensez à les remettre à jour quand vous les modifiez.
4. Pour chaque skill : compressez son dossier (`01 - Skills/socratique` → `socratique.zip`) et importez-le dans les paramètres de Claude, rubrique **Skills**. Si votre compte ne le permet pas, collez le contenu du `SKILL.md` au début de votre conversation.

**Voie B · pour les avancés : Claude Code**
1. Ouvrez Claude Code dans le dossier `Mon système IA`. Il lit `CLAUDE.md` tout seul.
2. Copiez les dossiers de `01 - Skills/` dans un dossier `.claude/skills/` à la racine.
3. Claude Code lit et écrit directement dans vos fichiers.

**Voie C · repli : ChatGPT**
Créez un projet et collez le contenu d'un `SKILL.md` dans ses instructions. La méthode est la même : seul l'outil change.

### 3. Tester
Tapez : `/socratique Je veux améliorer mon persona.` L'IA doit vous répondre par **une seule question**.

---

## Dans quel ordre le remplir

| Quand | Quoi | Avec |
|---|---|---|
| Atelier 1 | `ton.md` | le skill **ton**, sur 3 textes que vous avez écrits vous-même |
| Atelier 1 | premier essai de **socratique** et de **challenge** | votre PESTEL et votre persona du M2 |
| Mission A1 → A2 | `valeurs.md` | le skill **valeurs**, chez vous, au calme |
| Mission A1 → A2 | `contexte.md` | le skill **socratique**, puis relecture par votre tuteur |
| Au fil des modules | `02 - Cours/` | une note par module |

---

## Trois règles avant de commencer
1. **Aucune donnée client réelle** dans ces fichiers ni dans une IA personnelle. Des personas et des faits publics, oui ; des noms, téléphones ou emails de clients, non.
2. **Vous vérifiez avant de transmettre** : l'IA produit du plausible, pas du vrai.
3. **Vous signez ce que vous transmettez** : vous en assumez le contenu.

Le détail est dans [[Ma charte IA]].
