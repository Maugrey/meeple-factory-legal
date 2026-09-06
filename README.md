# Documents légaux publics — Meeple Factory

Socle public de l’issue #61 : informations légales FR/EN et contrats utilisables
par les intégrations avant la finalisation de conformité de #58.
Ce dépôt ne contient ni code privé du jeu, ni données de joueurs, ni identifiants
de production. Les numéros d’issues désignent le suivi du projet principal.

## URLs stables

| Document | Français | English |
| --- | --- | --- |
| Accueil | [Accueil](https://maugrey.github.io/meeple-factory-legal/) | [Home](https://maugrey.github.io/meeple-factory-legal/en/) |
| Confidentialité | [Politique](https://maugrey.github.io/meeple-factory-legal/privacy/) | [Privacy](https://maugrey.github.io/meeple-factory-legal/en/privacy/) |
| Conditions | [CGU](https://maugrey.github.io/meeple-factory-legal/terms/) | [Terms](https://maugrey.github.io/meeple-factory-legal/en/terms/) |
| Support | [Contact](https://maugrey.github.io/meeple-factory-legal/support/) | [Support](https://maugrey.github.io/meeple-factory-legal/en/support/) |
| Intégration | [Contrats](https://maugrey.github.io/meeple-factory-legal/contracts/) | [Contracts](https://maugrey.github.io/meeple-factory-legal/en/contracts/) |

GitHub Pages publie la racine de `main` avec HTTPS forcé. Les pages sont du HTML
statique et une feuille CSS locale, sans dépendance de build ni JavaScript.
Aucune collecte applicative, publicité, cookie applicatif, formulaire, compte,
vente ou ressource tierce intégrée. GitHub conserve ses propres journaux de
sécurité, comme expliqué dans la politique : « sans tracker ajouté » ne signifie
pas « aucune donnée traitée par l’hébergeur ».

## Statut et responsabilités

- Les comportements du jeu décrivent la **cible v1.0**, pas une attestation des
  fonctions disponibles dans toute build de test.
- Les contrats v0.2 fixent catégories et résolution d’âge, routage UGS/Aptabase,
  ordre initial, UMP, correction, suppression, réglages et hors ligne. #33/#34
  peuvent les consommer sans attendre la livraison de l’UX finale.
- Le [registre de finalisation](https://maugrey.github.io/meeple-factory-legal/contracts/#finalization)
  appartient à **#58** : chaque entrée reste ouverte jusqu’à preuve et mise à jour
  des deux langues. #36 répète les contrôles sur la release candidate.
- L’identité légale et le contact privé de l’éditeur restent à fournir. Ne pas
  inventer de coordonnées ni orienter les demandes individuelles vers des issues
  publiques. Ce manque doit être levé avant diffusion hors piste interne.
- Les dates affichées sont les dates de publication préparatoire. L’entrée en
  vigueur des documents définitifs reste à confirmer. Ce socle ne clôt pas #58
  et ne remplace pas une validation juridique.

## Points de vigilance de contenu

- Aptabase est prévu pour tous les profils et reste indépendant du choix UGS.
  Le fonctionnement sans consentement doit être justifié sur l’inventaire réel,
  notamment pour les enfants ; le qualificatif « anonyme » ne suffit pas.
- La politique Aptabase consultée le 7 septembre 2026 annonce jusqu’à cinq ans
  de conservation et l’absence de suppression individuelle. Ne pas transformer
  ce maximum fournisseur en durée validée pour le jeu.
- Une catégorie techniquement inconnue avec parcours achevé reste protégée ;
  elle ne doit pas être confondue avec un parcours d’âge inachevé, qui bloque
  l’initialisation AdMob. Aucun état corrompu ne vaut écran validé.
- La dimension de placement Aptabase vient d’un catalogue fermé. L’interdiction
  d’identifiants vise les personnes, installations et occurrences métier ; elle
  ne doit pas rejeter cette dimension autorisée au seul motif du suffixe `_id`.
- Arrêt UGS, suppression distante et effacement de progression sont distincts.
  Ne pas promettre l’effacement de tous les fournisseurs par une seule action.

## Maintenance

Modifier directement les `index.html` concernés et leur équivalent dans `en/`.
Conserver les chemins, les ancres `history` et `finalization`, les liens de langue
vers le même document et les versions/dates synchronisées. Documenter toute
évolution des invariants pour les intégrations ; ne pas la faire passer pour une
simple modification de traduction.

Avant publication, vérifier les dix pages sur mobile et ordinateur, la navigation
et les ancres, l’absence de ressources externes intégrées, de script, formulaire
ou stockage applicatif, puis les URL HTTPS après déploiement. Les liens vers les
politiques des fournisseurs ne remplacent pas l’inventaire du build.

## Références de la revue du 7 septembre 2026

- [GitHub Pages — collecte des IP](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection)
- [Confidentialité GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)
- [Google Play — données utilisateur et politique de confidentialité](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en)
- [AdMob Unity — informations Data safety](https://developers.google.com/admob/unity/privacy/play-data-disclosure)
- [Politique Aptabase](https://aptabase.com/legal/privacy)
- [Politique Unity pour les joueurs](https://unity.com/legal/game-player-and-app-user-privacy-policy)
- [CNIL — conditions de mesure d’audience](https://www.cnil.fr/fr/cookies-solutions-pour-les-outils-de-mesure-daudience)
- [CNIL — droits des personnes](https://www.cnil.fr/fr/mes-demarches/les-droits-pour-maitriser-vos-donnees-personnelles)

Les documentations fournisseur peuvent décrire des versions plus récentes que le
SDK retenu : #58 doit les rapprocher des versions et configurations effectivement
livrées. Aucune durée, base juridique ou déclaration store n’est validée par défaut.

## Historique

- 2026-09-07 — v0.2 préparatoire : contenu FR/EN étoffé, hébergeur et services
  distingués, inventaires initiaux, arrêt/suppression, CGU et support précisés,
  contrats opérationnels et registre de finalisation #58.
- 2026-09-06 — v0.1 préparatoire : première publication bilingue et contrats.
