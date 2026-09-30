# Révision DP-600

Cinquante-cinq questions d'entraînement à l'examen **DP-600 (Microsoft Fabric Analytics Engineer)**, réparties en quatre tests par domaine, avec correction détaillée de chaque option. Bilingue français / anglais.

- **`index-revise.html`** — les 125 questions, réparties par domaine d'examen
- **`reflexes.html`** — la fiche des formulations d'énoncé et du réflexe à déclencher pour chacune

Deux fichiers statiques, sans dépendance ni build. Les seules ressources externes sont les polices Google Fonts ; la page reste lisible sans elles.

## Contenu

| Test | Domaine | Questions |
|---|---|---|
| 1 | Planifier, implémenter et gérer une solution | 10 |
| 2 | Préparer et servir les données | 26 |
| 3 | Implémenter et gérer des modèles sémantiques | 12 |
| 4 | Explorer et analyser les données | 7 |

Onze questions s'appuient sur les études de cas Contoso et Litware, repliées en haut des tests concernés. Sept questions portent la mention **contestée** : leur corrigé diverge selon les sources, et les deux raisonnements sont exposés.

## Fonctionnement

- Le sélecteur **FR / EN** en haut à droite bascule l'intégralité du contenu, y compris les corrections. Les énoncés anglais sont les textes originaux de l'examen.
- Les réponses et le choix de langue sont conservés dans le `localStorage` du navigateur. Rien n'est envoyé nulle part, et rien ne suit d'un appareil à l'autre.
- Thème clair et sombre automatiques, selon le réglage du système.

## Déploiement

Le site est entièrement statique. Sur GitHub Pages :

1. *Settings → Pages*
2. **Source** : `Deploy from a branch`
3. **Branch** : `main`, dossier `/ (root)`

La page sera disponible à `https://<utilisateur>.github.io/<dépôt>/` après une minute ou deux.

## Sources et limites

Les énoncés proviennent de recueils d'examen dont les corrigés divergent parfois entre eux. Vérifiez toujours contre [Microsoft Learn](https://learn.microsoft.com/certifications/exams/dp-600/).
