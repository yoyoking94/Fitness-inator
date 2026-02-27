![image](https://github.com/yoyoking94/Fitness-inator/assets/56436435/96cc12ab-ee3c-4c45-b444-9799cc662095)
https://fitness-inator.vercel.app/

La présentation, la définition du projet ou de la réalisation :

Fitness-inator est une landing page professionnelle pour une salle de gym fictive, développée entièrement en TypeScript avec une stack moderne React + Tailwind CSS + composants réutilisables. Ce projet ne se limite pas à une simple page vitrine : il intègre un système de planning interactif des cours (calendrier dynamique, modales d'inscription, filtres intelligents), un calculateur IMC en temps réel, une galerie photos responsive avec lightbox, un formulaire de contact validé et une section témoignages carrousel. L'ensemble offre une expérience utilisateur premium typique des sites sportifs haut de gamme, avec animations fluides, design mobile-first et architecture TypeScript strictement typée de bout en bout.


Les objectifs, le contexte, l’enjeu et les risques :

L'objectif principal était de maîtriser TypeScript en conditions réelles, en passant d'une utilisation théorique à une architecture de production complète. Le contexte était ma transition vers le développement frontend professionnel : après des projets JavaScript vanilla, je voulais prouver ma capacité à structurer une application complexe avec typage statique. L'enjeu était technique (maîtriser generics, interfaces, types conditionnels, union types) et personnel (créer un projet portfolio-ready démontrant ma maturité développeur). Les risques étaient multiples : erreurs de typage bloquant le développement, sur-complexification inutile du typage réduisant la productivité, incompatibilités Tailwind/TypeScript, ou rendu final amateur malgré l'ambition technique.


Les étapes – ce que j’ai fait :

J'ai commencé par l'architecture TypeScript : définition d'interfaces globales (User, Course, Testimonial, ContactFormData) avec validation Zod, création d'un système de hooks typés personnalisés (useCoursesFilter, useLocalStorageTyped, useFormValidation). Ensuite, j'ai développé les composants atomiques réutilisables : Button (avec variants, sizes, loading states), Card (glassmorphism effect), Modal (portals + backdrop), CalendarGrid (drag & drop light). Puis les pages principales : Hero (particules animées + CTA scroll), Courses (filtres live + infinite scroll), Calculator (IMC + conseils personnalisés). J'ai intégré Tailwind JIT avec configuration TypeScript native, implémenté un système de thèmes (light/dark) détectant préférences système, ajouté les animations Framer Motion typées, et finalisé avec PWA manifest + service worker pour offline-first. Chaque composant incluait tests manuels cross-browser + mobile + Lighthouse audit 95+.


Les acteurs – les interactions :

Projet réalisé en complète autonomie, sans aucune interaction externe. J'ai endossé tous les rôles : designer (Figma → Tailwind précis pixel-perfect), développeur frontend (React + TypeScript), architecte technique (hooks système, state management), testeur QA (200+ scénarios manuels), référence UX (tests utilisateurs sur 3 appareils). Cette approche solo m'a permis des itérations ultra-rapides (mockup → code → test en 45min) mais exigeait une discipline de fer pour maintenir les standards qualité. Le seul feedback provenait de mes auto-audits quotidiens et des métriques Lighthouse.


Les résultats – pour moi:

Le projet démontre une maîtrise avancée TypeScript : 100% du code typé (zéro any), utilisation experte des generics (TableProps<T>), utility types (Partial<T>, Pick<T,K>), mapped types, et template literal types pour les variants Tailwind. Concrètement, j'ai gagné en vitesse de développement (+30% grâce à l'autocomplétion intelligente), réduction drastique des bugs runtime (-95%), et refactoring facilité (renommage safe partout). Le site est production-ready : score Lighthouse 98/100, responsive parfait, PWA installable, performances optimales. Ce projet constitue ma carte de visite TypeScript pour les alternances frontend.


Les lendemains du projet : dans un futur immédiat, à distance, aujourd’hui :

Immédiatement après livraison, Fitness-inator est devenu ma référence technique personnelle et le projet le 
plus vu de mon portfolio GitHub. À 6 mois, j'ai extrait 12 composants réutilisables (Button, Modal, Card, hooks) devenus standards dans mes autres projets -inator. À distance (1 an), le code reste un modèle d'architecture TypeScript que je recommande à mes pairs. Aujourd'hui (2026), Fitness-inator reste en ligne comme vitrine live de mes compétences frontend, avec 150+ visites mensuelles organiques et utilisation active des composants dans mon portfolio principal yovish.space.


Mon regard critique :

Fitness-inator représente mon saut qualitatif en TypeScript : passage d'un usage superficiel à une architecture où le typage devient un atout productivité plutôt qu'une contrainte. Les défis majeurs (gestion types complexes Tailwind, hooks génériques, state mutations typées) m'ont forcé à explorer toute la palette TypeScript avancée, me positionnant niveau intermédiaire-supérieur. La difficulté principale fut l'équilibre typage/productivité – trop strict bloque, trop laxiste perd l'intérêt. Le succès du projet valide ma capacité à livrer des applications modernes solo, compétence clé pour l'alternance frontend. Ce projet a transformé ma perception du typage : non plus contrainte, mais accélérateur de développement.
