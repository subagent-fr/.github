# Subagent

L'e-mail pour agents IA.

Chaque agent a sa boîte mail. Il écrit, reçoit et répond avec sa propre adresse.

Subagent Mail est un service d'e-mail conçu pour être utilisé par un agent IA : il crée sa boîte, envoie, lit ses fils et répond. Le serveur règle les envois (montée progressive, quota du jour, heures ouvrées, validation humaine, désinscription). Tout passe par le MCP : il n'y a pas de console, vous passez par votre assistant IA.

**Ouvert à tous depuis le 14 octobre 2026.** Sans clé, l'agent s'inscrit lui-même avec `sign_up` ; votre humain reçoit un code à 6 chiffres par e-mail.

## Brancher un agent

```text
https://api.subagent.fr/mcp
```

Le guide pas à pas : [subagent.fr/brancher](https://subagent.fr/brancher).

## Serveur fermé, clients ouverts

Les règles d'envoi tournent sur notre serveur. Ce qui sert à s'y brancher est ici, sous licence MIT, généré depuis le même registre d'opérations que le serveur.

| Dépôt | Rôle |
| --- | --- |
| [`subagent-mcp`](https://github.com/subagent-fr/subagent-mcp) | Brancher le MCP à Claude Code, Cursor ou tout client MCP |
| [`subagent-python`](https://github.com/subagent-fr/subagent-python) | SDK Python |
| [`subagent-node`](https://github.com/subagent-fr/subagent-node) | SDK TypeScript |
| [`subagent-cli`](https://github.com/subagent-fr/subagent-cli) | Ligne de commande |
| [`subagent-skills`](https://github.com/subagent-fr/subagent-skills) | Recettes pour agents |
| [`subagent-plugins`](https://github.com/subagent-fr/subagent-plugins) | Plugin Claude Code |
| [`subagent-examples`](https://github.com/subagent-fr/subagent-examples) | Exemples à lancer, en Python et pour Node |

Les SDK et la ligne de commande s'installent pour l'instant depuis GitHub : chaque README donne la commande. Les paquets PyPI et npm viendront ensuite.

## Liens

[Site](https://subagent.fr) · [Documentation](https://subagent.fr/docs/) · [Pour les agents : llms.txt](https://subagent.fr/llms.txt)
