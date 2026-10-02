# BP — De meilleurs prompts

Skill en français pour créer, améliorer et simplifier des prompts à partir des bonnes pratiques OpenAI.

BP préserve votre intention et vos contraintes, clarifie le résultat attendu et produit un prompt prêt à copier. Il améliore le prompt sans exécuter la tâche décrite, sauf demande explicite.

## Installation dans Codex

Copiez `SKILL.md` et le dossier `agents` dans un dossier `bp` sous votre répertoire personnel de skills (`$CODEX_HOME/skills`, ou `~/.codex/skills` si cette variable n’est pas définie). Ouvrez ensuite un nouveau chat.

Structure attendue :

```text
bp/
├── SKILL.md
└── agents/
    └── openai.yaml
```

## Utilisation

```text
$bp Améliore ce prompt : [votre prompt]
```

```text
$bp Simplifie ce prompt en conservant toutes mes contraintes : [votre prompt]
```

```text
$bp Crée un prompt pour [résultat souhaité]. Contexte : [informations utiles].
```

Dans un autre chat, vous pouvez joindre `SKILL.md` et demander d’en appliquer les instructions. L’installation locale ne constitue pas une installation automatique dans votre compte ChatGPT.

## Sources

- [Bonnes pratiques de prompt engineering — OpenAI](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-the-openai-api)
- [Recommandations pour les modèles de raisonnement — OpenAI](https://developers.openai.com/api/docs/guides/reasoning-best-practices)

Projet indépendant, sans affiliation officielle avec OpenAI. Aucun script, clé API ou service externe n’est nécessaire pour utiliser les instructions du skill.
