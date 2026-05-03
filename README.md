# Portfolio E5 — Maxime Mansiet

**BTS SIO SLAM · EPSI Bordeaux · Promotion 2024–2026**

Ce dépôt contient le **portfolio professionnel** servant de support à l'**épreuve E5 — Support et mise à disposition de services informatiques (Bloc 1)** du BTS Services Informatiques aux Organisations (option SLAM).

Le site est un dossier numérique interactif qui présente mon parcours de professionnalisation et les réalisations couvrant les **six compétences du Bloc 1**.

**Site en ligne :** [e5.maximemansiet.fr](https://e5.maximemansiet.fr)

---

## Contexte de l'épreuve

L'épreuve E5 (référentiel BTS SIO 2026, coefficient 4, durée 40 min) évalue le candidat sur les compétences du **Bloc 1 — Support et mise à disposition de services informatiques** (commun aux deux options SISR et SLAM). Le support à fournir doit permettre au jury d'apprécier :

- le parcours de professionnalisation du candidat
- les réalisations professionnelles et/ou personnelles mobilisées
- la couverture des six compétences du Bloc 1

Ce portfolio fait office de support numérique et est complété par le **dossier professionnel PDF** (BTSSIDOPROFE5) déposé sur Cyclade, accompagné des **attestations de stage** (BTSSIPRESENTE5).

---

## Compétences du Bloc 1 couvertes

| Code | Compétence |
|------|------------|
| **B1-C1** | Gérer le patrimoine informatique |
| **B1-C2** | Répondre aux incidents et aux demandes d'assistance et d'évolution |
| **B1-C3** | Développer la présence en ligne de l'organisation |
| **B1-C4** | Travailler en mode projet |
| **B1-C5** | Mettre à disposition des utilisateurs un service informatique |
| **B1-C6** | Organiser son développement professionnel |

Chaque compétence est détaillée sur le site avec les réalisations professionnelles et associatives qui la couvrent, ainsi que les outils et technologies mobilisés.

---

## Structure du dossier numérique

Le site est organisé en sections qui correspondent aux attendus de l'épreuve :

- **Parcours** — timeline des expériences professionnelles (Hop Hop Immo, Verana / 2060.io, Klyx, Reciproq, PKBA)
- **Projets** — fiches détaillées des réalisations principales avec technologies, rôle et compétences couvertes
- **Compétences Bloc 1** — présentation des six compétences et rattachement aux réalisations
- **Veille technologique** — outils et stratégie de veille (OpenClaw, GDG Bordeaux, communautés tech)
- **Tableau de synthèse** — matrice réalisations × compétences (document obligatoire E5)
- **Contact** — formulaire et coordonnées

Les **attestations de stage** sont fournies séparément en annexe du dossier remis sur Cyclade (BTSSIPRESENTE5).

---

## Stack technique

| Domaine | Technologie |
|---------|-------------|
| Framework | Next.js 15 (App Router) |
| Langage | TypeScript |
| UI | React 19, Tailwind CSS 4 |
| Animations | Motion (Framer Motion) |
| Icônes | Lucide React |
| Déploiement | Netlify (build + déploiement automatiques sur `main`) |

---

## Développement local

### Prérequis
- Node.js 18+
- npm

### Installation

```bash
git clone https://github.com/AirKyzzZ/e5-portfolio.git
cd e5-portfolio
npm install
npm run dev
```

Le site est accessible sur [http://localhost:3000](http://localhost:3000).

### Scripts

```bash
npm run dev      # Serveur de développement
npm run build    # Build de production
npm run start    # Serveur de production
npm run lint     # Vérification du code (ESLint)
```

---

## Organisation du code

```
src/
├── app/
│   ├── page.tsx              # Page d'accueil (Hero principal)
│   └── project/[id]/         # Fiche détaillée par projet
├── components/ui/
│   ├── Competences/          # Grille des 6 compétences du Bloc 1
│   ├── TableauSynthese/      # Tableau de synthèse réalisations × compétences
│   ├── VeilleTech/           # Section veille technologique
│   ├── Timeline/             # Parcours professionnel
│   ├── Projects/             # Cartes et pages projets
│   ├── ContactForm/          # Formulaire de contact
│   └── ...                   # Composants UI (Navbar, Footer, etc.)
└── data/
    ├── competences.ts        # Données des 6 compétences du Bloc 1
    └── projects.ts           # Données des projets
```

Les **données du dossier** (compétences, projets, réalisations) sont centralisées dans `src/data/` pour être facilement modifiables sans toucher aux composants.

---

## Auteur

**Maxime Mansiet** — étudiant BTS SIO SLAM à l'EPSI Bordeaux (2024–2026).

- Développeur fullstack chez **Verana / 2060.io**
- Ingénieur logiciel chez **Hop Hop Immo** (stage → alternance 2026)
- Fondateur de **Klyx** (agence de création digitale)
- Co-fondateur & trésorier de **PKBA** (Parkour Bassin d'Arcachon)

[LinkedIn](https://linkedin.com/in/maxime-mansiet) · [GitHub](https://github.com/AirKyzzZ) · [maximemansiet.fr](https://maximemansiet.fr)
