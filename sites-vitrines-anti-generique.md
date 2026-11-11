---
name: sites-vitrines-anti-generique
description: Construit des sites web d'entreprise professionnels qui ne ressemblent pas à un gabarit générique, de niveau marque établie (figma.com, x.ai) – texte simple et direct, un système visuel unique, une section par écran, vraies photographies et vraie interface produit, entrée de héros soignée, micro-interactions discrètes. À utiliser dès que l'utilisateur crée, refait, restyle, peaufine ou revoit une landing page ou un site d'entreprise, de produit, de boutique, de café, d'hôtel, de studio, de clinique, d'agence, de SaaS, d'IA, d'outil développeur ou de jeu, en HTML/CSS statique ou dans un projet React, Next.js, Vue, Svelte, Astro ou Tailwind existant. Use for "make my site look professional", "anti-slop", "generic AI look", "redesign my landing page". Ne couvre pas le back-end.
---

# Sites vitrines non génériques

Objectif : le site qu'une bonne entreprise publierait vraiment. Il dit simplement ce qui est vendu, montre la vraie chose à chaque écran, et paraît fait pour **ce** client : ni gabarit, ni pièce d'art. Version autonome (sans scripts, sans hook), inspirée de la méthode de la skill publique taste-skill, rédigée de façon indépendante.

## Les neuf règles de la maison (elles priment sur tout le reste)

1. **Aucune légende ni description sous une image ou un visuel.** Les crédits de licence vont dans une seule ligne de pied de page.
2. **Chaque visuel s'affiche vraiment**, jamais un cadre vide, à 1440, 1024, 768 et 390 px.
3. **Une section par écran** : le héros seul sur le premier écran, chaque section fait un ou deux écrans de haut à 1440×900, sans que le titre de la section suivante dépasse en bas. Exception possible : une séquence photo de trois ou quatre écrans, voulue.
4. **Bords gauche et droit identiques** pour le contenu (mêmes marges des deux côtés).
5. **Micro-animations au survol** : une carte cliquable se soulève de 2 px, une photo zoome de 1,02 à 1,03 dans son cadre, les boutons réagissent au survol et à l'appui, les soulignements se dessinent. Pas d'inclinaison 3D, pas de carrousels, pas d'onglets automatiques. Le héros entre une seule fois au chargement, et chaque page porte **un** moment fort (deux sur une page longue).
6. **De vraies photographies** partout où elles ont leur place, de meilleurs fonds, de meilleurs héros, de meilleures polices.
7. **De vraies icônes en couleur** (l'icône réelle d'un produit connu, jamais une icône dessinée à la main) ; petits schémas dans les cartes si utile (un point central avec des branches, une entrée vers trois voies parallèles).
8. **Les grands effets (shaders, scènes 3D) uniquement pour les sujets techniques** : logiciel, IA, outils développeur, jeu vidéo, fintech, matériel. Jamais sur un café, une boulangerie, une pension ou une boutique : eux ont des photographies.
9. **Adresses et coordonnées** : rue et quartier seulement (sans numéro, code postal ni coordonnées GPS), pas de numéro d'enregistrement ni de TVA, pas de téléphone au format réel dans les maquettes, contacts d'exemple sur un domaine factice (`.example`). Le client remplace par ses vraies données.

## 1. Le type d'activité décide de tout

Écrire le type sur la première ligne du plan.

| Brief | Type |
|---|---|
| Application, SaaS, IA, outil développeur, fintech, studio qui vend son logiciel | **Logiciel** |
| Un jeu, un studio qui lance son jeu | **Jeu** |
| Matériel ou appareil technique (drone, bras robotique, clavier) | **Matériel** |
| Autre produit physique ou marque (chaise, vélo, café vendu en ligne) | **Produit** |
| On engage des gens : clinique, cabinet d'avocats, agence, studio créatif, artisan | **Service** |
| On vient sur place : café, bar, boulangerie, restaurant, pension, petit hôtel, boutique, fleuriste, salle de sport | **Lieu** |

Un artisan qui reçoit aussi du public ou donne des cours (atelier de céramique, boulangerie avec boutique en ligne) est un **lieu** ; sa boutique devient la section « produits ». Il n'est « produit » que s'il ne se passe rien à sa porte.

**Technique** = logiciel, jeu, matériel. **Autre** = tout le reste. Les effets, scènes, boucles animées, compteurs, fonds en CSS, pages sombres et héros sombres sont réservés aux sites techniques. Les autres sites sont faits de photographies, d'aplats de couleur, de typographie, de vraies icônes, de l'entrée du héros, d'un moment fort (photo ou typographie) et des survols.

## 2. Le plan de page selon le type

- **Lieu** : les photographies mènent (12 à 20 sur la page complète, 8 à 12 en version compacte, moins de 8 pour une page courte de 3 écrans). Pas de photos du client : photos de remplacement de même nature, listées dans le compte rendu. Héros en photo dès qu'un cadre convient (un lieu isolé : le paysage de sa région). Bloc « venir » dès le deuxième écran, puis l'offre, le lieu, commande ou réservation. Compositions différentes pour l'offre et le lieu, pas deux sections autour de la même image. Une seule action principale par écran. Aplats de couleur, photos carrées, un seul style de bouton, barre téléphone sur mobile. Aucun effet, boucle, diagramme ni onglet.
- **Produit et service** : photographies d'abord (le produit, les gens, les pièces, le travail), deux ou plus par écran sur une page produit. Vraies icônes pour les outils réellement utilisés, un schéma fixe au plus. Fonds plats, une bande de couleur de marque. Pas de shader, grain, dégradé ni scène. **Produit sans photos fournies** : montrer des photos de remplacement du même type d'objet, jamais un dessin, une ambiance en photo d'archive ou des accessoires. Un rendu 3D seulement si le brief le demande.
- **Chaque page produit** : le produit **grand**, entier, occupant l'essentiel du cadre (pas moyen dans un panneau gris arrondi sur fond gris) ; une image **différente** par section ; chaque promesse du titre illustrée ; compositions variées ; **chaque fait une seule fois** ; le choix de couleur change l'image.
- **Technique** : le sujet du client mène, à taille réelle. Logiciel : sa propre interface en HTML réel montrant ce sur quoi il travaille (un outil de revue de code : un diff rouge et vert avec son bouton « Accepter »), dans un seul cadre d'application, jamais un tableau de bord générique ni de simples fragments sur panneaux. Matériel : ses photos ou des photos de remplacement. Jeu : son nom dans le h1, une ligne de lancement, son monde en visuel plein cadre. **60 à 80 mots par écran** hors maquettes d'interface. **Un seul effet** (fond animé du héros, cadre visuel unique, pièce 3D) et un ou deux moments forts dans leurs propres sections.
- **Un objet ne porte jamais toute la page** : il mène le héros et deux sections au plus ; d'autres types de visuels portent le reste.
- **Les éléments du client ont leur place** : bande-annonce, visuels, captures, rendus CAO, vidéo : chacun reçoit un cadre qui paraît fini dès maintenant (une vraie balise vidéo avec une affiche provisoire, un bouton lecture seulement s'il y a quelque chose à lire), signalé dans un commentaire pour que le client y mette son fichier. Jamais vide.

## 3. Textes

- Dire simplement ce qui est vendu, à qui, et ce que la personne peut faire ensuite. Phrases courtes, verbes concrets, voix propre à la marque.
- Pas de formules creuses (« solutions innovantes », « expérience unique », « passion et expertise »), pas de superlatifs sans preuve, pas de faux témoignages ni de faux chiffres. Un chiffre, une certification ou un témoignage non fourni par le client : le signaler comme à compléter, ne pas l'inventer.
- Un titre, une promesse, une action. Libellés de boutons qui disent l'action (« Réserver une chambre », « Commander un gâteau », « Démarrer l'essai gratuit »).
- Même vocabulaire d'un bout à l'autre ; chaque fait apparaît une fois.
- Langue du client. Pour un site bilingue, les deux versions ont la même structure et la même qualité, pas une traduction automatique brute.

## 4. Système visuel unique

- Définir une fois : couleurs (fond, texte, accent, états), deux polices maximum, échelle typographique, espacements (multiples de 8), rayons, boutons, navigation, pied de page. Ensuite, rien ne sort du système.
- Un contraste texte/fond d'au moins 4,5:1. Texte de liste à 16 px.
- Un seul style de bouton principal, un secondaire. Une seule action principale visible par écran.
- Navigation courte (5 liens au plus) plus une action principale. Pied de page utile : contact, liens, mentions.

## 5. Mouvement

- Le héros entre une fois, de façon sobre (fondu + léger déplacement, 400 à 700 ms).
- Un moment fort par page : un grand titre composé, une séquence photo, un chiffre mis en scène, une image qui se révèle. Sur un site « autre », ce moment est photo ou typographie, jamais un effet de shader.
- Survols selon la règle 5, uniquement sur appareils qui survolent (`@media (hover: hover)`).
- `prefers-reduced-motion` respecté. Animer `transform` et `opacity`. Pas de mouvement lié au défilement sur les cartes.

## 6. Photographies

- Une photographie réelle bat toujours une illustration générique. Sans photos du client, utiliser des photos de remplacement **réellement libres de droits** (licence vérifiée et notée dans la ligne de crédit du pied de page), du même type de sujet que le client (même sorte de lieu, de produit, de métier).
- Pas de photos d'archive « ambiance » sans rapport (poignée de main, bureau vide, ordinateur sur fond de ville).
- Chaque photo : dimensions réservées, `alt` utile, `loading="lazy"` hors premier écran, format moderne (WebP ou AVIF), cadrage choisi pour mobile et pour grand écran.
- Ne jamais présenter une photo de remplacement comme une photo du client. Le dire dans le compte rendu : le client doit la remplacer.

## 7. Le déroulé

1. **Lire le brief** et noter : le type d'activité, ce qui est vendu, qui achète, l'action principale (réserver, commander, démarrer un essai, obtenir l'itinéraire), les vrais matériaux (logo, captures, photos, prix, adresse, horaires).
2. **Écrire le plan** : type, sections dans l'ordre (une par écran), idée visuelle en une phrase, palette, polices, moment fort, photos nécessaires.
3. **Construire** : dossier vide = page statique propre ; projet existant = dans sa propre pile (React, Next.js, Vue, Svelte, Astro, Tailwind), en réutilisant ses composants et son système.
4. **Vérifier** aux quatre largeurs (1440, 1024, 768, 390) : aucun visuel vide, une section par écran, bords égaux, aucune légende sous les images, survols en place, textes sans coquilles.
5. **Contrôle final** :
   - [ ] Les neuf règles de la maison sont respectées.
   - [ ] Le type d'activité est correct et les effets ne sont présents que sur un site technique.
   - [ ] Aucune donnée inventée (chiffres, adresse, téléphone, certifications, témoignages).
   - [ ] Les photos de remplacement sont signalées et créditées.
   - [ ] Contraste, focus clavier, `alt`, `prefers-reduced-motion`, performance (poids des images, polices limitées).
6. **Compte rendu court** : ce qui a été construit, les hypothèses, la liste exacte de ce que le client doit fournir (logo, photos, textes officiels, coordonnées).

## Communication

- Répondre dans la langue de l'utilisateur.
- Si la demande est floue, choisir une direction raisonnable, l'annoncer en une phrase, et avancer. Une seule question à la fois, seulement si la réponse change vraiment le résultat.
- Dire franchement quand une demande dégrade le site (trop d'effets pour un commerce local, texte trop long) et proposer mieux.
- Ne jamais copier le code, les textes ni les visuels protégés d'un autre site : s'inspirer des principes.
