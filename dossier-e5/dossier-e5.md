---
documentclass: article
lang: fr-FR
papersize: a4
geometry:
  - a4paper
  - margin=2.2cm
  - top=2.5cm
  - bottom=2.5cm
fontsize: 11pt
mainfont: "Helvetica Neue"
monofont: "Menlo"
linkcolor: "blue!60!black"
urlcolor: "blue!60!black"
toccolor: "black"
colorlinks: true
header-includes:
  - \usepackage{fancyhdr}
  - \usepackage{titlesec}
  - \usepackage{array}
  - \usepackage{longtable}
  - \usepackage{booktabs}
  - \usepackage{xcolor}
  - \usepackage{colortbl}
  - \usepackage{tcolorbox}
  - \tcbuselibrary{skins,breakable}
  - \usepackage{amssymb}
  - \usepackage{pifont}
  - \newcommand{\cmark}{\ding{51}}
  - \pagestyle{fancy}
  - \fancyhead[L]{\textsc{Maxime Louis François Mansiet}}
  - \fancyhead[R]{\textsc{BTS SIO SLAM — E5}}
  - \fancyfoot[C]{\thepage}
  - \renewcommand{\headrulewidth}{0.4pt}
  - \renewcommand{\footrulewidth}{0pt}
  - \titleformat{\section}{\Large\bfseries\color{black!85}}{\thesection}{1em}{}
  - \titleformat{\subsection}{\large\bfseries\color{black!75}}{\thesubsection}{1em}{}
  - \titleformat{\subsubsection}{\normalsize\bfseries\color{black!65}}{\thesubsubsection}{1em}{}
  - \setlength{\parskip}{0.6em}
  - \setlength{\parindent}{0pt}
  - \renewcommand{\contentsname}{Sommaire}
  - \AtBeginDocument{\hypersetup{pdftitle={Dossier professionnel — Épreuve E5 — BTS SIO SLAM}, pdfauthor={Maxime Louis François Mansiet}, pdfsubject={Support et mise à disposition de services informatiques (Bloc 1)}}}
---

\thispagestyle{empty}
\begin{titlepage}
\centering
\vspace*{1.5cm}

{\fontsize{30}{36}\selectfont\textbf{Dossier professionnel}}

\vspace{0.5cm}
{\Large Épreuve E5}

\vspace{0.3cm}
{\large \textit{Support et mise à disposition de services informatiques (Bloc 1)}}

\vspace{1.8cm}
\rule{0.6\textwidth}{0.4pt}

\vspace{0.8cm}
{\Large\textbf{Maxime Louis François MANSIET}}

\vspace{0.4cm}
{\large BTS SIO option SLAM}\\
{\large EPSI Bordeaux — Promotion 2024–2026}

\vspace{0.4cm}
\rule{0.6\textwidth}{0.4pt}

\vspace{1.8cm}
\textbf{Portfolio en ligne :} \href{https://e5.maximemansiet.fr}{e5.maximemansiet.fr}

\vspace{0.3cm}
\textbf{Session :} 2026

\vfill
{\small Document numérique conforme à la circulaire nationale BTS SIO 2026 — Annexe VI.}

\end{titlepage}

\thispagestyle{fancy}
\tableofcontents
\clearpage

# Présentation du candidat

**Maxime Louis François Mansiet** — étudiant en deuxième année du **BTS SIO option SLAM** (Solutions Logicielles et Applications Métiers) à l'**EPSI Bordeaux**, promotion 2024–2026.

| | |
|---|---|
| **Nom, Prénoms** | MANSIET, Maxime Louis François |
| **N° candidat** | 02248411067 |
| **Établissement** | EPSI Bordeaux |
| **Diplôme préparé** | BTS Services Informatiques aux Organisations — option SLAM |
| **Promotion** | 2024–2026 |
| **Session d'examen** | 2026 |
| **Email** | maxime.mansiet@gmail.com |
| **LinkedIn** | linkedin.com/in/maxime-mansiet |
| **GitHub** | github.com/AirKyzzZ |
| **Portfolio en ligne** | https://e5.maximemansiet.fr |

\vspace{0.5cm}

Mon parcours combine une **expérience professionnelle dense** (stage, alternance, entrepreneuriat, freelance) et un **engagement associatif structurant** (co-fondation et trésorerie d'un club sportif de 60+ licenciés, communauté tech GDG Bordeaux). Cette diversité m'a permis de mobiliser et de couvrir l'ensemble des **six compétences du Bloc 1** dans des contextes professionnels variés : édition logicielle, identité numérique décentralisée, agence digitale, plateforme santé mentale, association sportive.

Mes domaines de spécialisation actuels :

- **Développement web fullstack** (Next.js, React, TypeScript, Node.js)
- **Infrastructure & DevOps** (Docker, Kubernetes, Helm, CI/CD GitHub Actions)
- **Identité numérique décentralisée** (DIDs, Verifiable Credentials, DIDComm) chez Verana / 2060.io
- **IA appliquée** (LLM, agents conversationnels, MCP) chez Hop Hop Immo

\newpage

# Parcours de professionnalisation

Le tableau ci-dessous récapitule les expériences mobilisées dans ce dossier, par ordre chronologique.

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{05 janvier — 13 février 2026 · Hop Hop Immo / LES CLES DU NEUF (Saint-Médard-en-Jalles)} \\
\textit{Stage ingénieur logiciel — convention BTS SIO. Alternance prévue septembre 2026.} \\
Développement de \textit{Hoppy}, premier assistant immobilier vocal (ElevenLabs + LLM) disponible 24/7 sur une base de 28\,000+ annonces. Conception d'agents IA autonomes pour l'automatisation marketing. Refonte de la homepage Next.js avec triplement du trafic organique en 3 mois.

\end{tcolorbox}

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Septembre 2025 — en cours · Verana / 2060.io (full remote)} \\
\textit{Développeur fullstack — édition logicielle, identité numérique décentralisée.} \\
Conception et développement de briques clés du \textit{Verana Verifiable Trust Network} : applications web (Verana Visualizer pour explorer DIDs, Verifiable Credentials et trust registries), APIs, services backend, SDKs. Stack : Next.js, React, TypeScript, Tailwind, Node.js. Déploiements via Docker, Kubernetes/Helm et CI/CD. Conception de \textit{Concieragent}, agent IA orchestrant 6 serveurs MCP via DIDComm chiffré.

\end{tcolorbox}

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Juillet 2025 — en cours · PKBA — Parkour Bassin d'Arcachon} \\
\textit{Co-fondateur \& trésorier — association sportive (60+ licenciés).} \\
Plus grand club de parkour de Nouvelle-Aquitaine. Conception de l'identité visuelle, développement du site web (inscriptions en ligne, boutique Stripe, dons), gestion de la communication digitale, organisation d'événements, structuration administrative et trésorerie.

\end{tcolorbox}

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Avril 2025 — en cours · Klyx} \\
\textit{Fondateur \& dirigeant — agence de création digitale.} \\
Pilotage de 5+ projets clients en méthodologie Agile. Développement de sites performants en Next.js avec scores Lighthouse supérieurs à 95/100, +80\% de trafic organique et +35\% de leads générés pour les clients. Conception UI/UX sur-mesure et optimisation des performances.

\end{tcolorbox}

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{22 avril — 30 mai 2025 · Reciproq} \\
\textit{Stage de découverte / Développeur web — plateforme santé mentale.} \\
Plateforme de mise en relation entre professionnels de santé mentale et particuliers. Développement des pages clés du site vitrine en Next.js et Tailwind, adaptation de la charte graphique Figma, design mobile-first, méthodologie Agile en équipe pluridisciplinaire (dev + design + produit).

\end{tcolorbox}

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Octobre 2024 — en cours · GDG Bordeaux} \\
\textit{Membre actif — Google Developer Group, communauté tech.} \\
15+ meetups et codelabs suivis (Flutter, TensorFlow, Angular, PWA). Co-animation d'un mini-atelier Flutter. Réseau de 100+ contacts tech en Nouvelle-Aquitaine. Veille technologique structurée et entretien d'un environnement d'apprentissage personnel continu.

\end{tcolorbox}

\begin{tcolorbox}[
  enhanced,breakable,
  colback=black!2,colframe=black!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Septembre 2024 — Juin 2026 · EPSI Bordeaux} \\
\textit{Étudiant — BTS SIO option SLAM.} \\
Formation en ingénierie informatique : algorithmique, structures de données, bases de données, développement web, services réseau, gestion de projet, droit du numérique. Cursus complété par la certification \textbf{Harvard CS50x} (août 2025 — janvier 2026) et la certification \textbf{EFSET C2 Proficient} (87/100) en anglais.

\end{tcolorbox}

\newpage

# Compétences du Bloc 1

L'épreuve E5 évalue les six compétences officielles du Bloc 1 « Support et mise à disposition de services informatiques », commun aux options SISR et SLAM.

\begin{longtable}{p{0.18\textwidth} p{0.78\textwidth}}
\toprule
\textbf{Code} & \textbf{Compétence} \\
\midrule
\textbf{B1-C1} & Gérer le patrimoine informatique \\
\textbf{B1-C2} & Répondre aux incidents et aux demandes d'assistance et d'évolution \\
\textbf{B1-C3} & Développer la présence en ligne de l'organisation \\
\textbf{B1-C4} & Travailler en mode projet \\
\textbf{B1-C5} & Mettre à disposition des utilisateurs un service informatique \\
\textbf{B1-C6} & Organiser son développement professionnel \\
\bottomrule
\end{longtable}

Chaque réalisation présentée dans la section suivante précise les compétences mobilisées. Le **tableau de synthèse** en fin de dossier (page \pageref{tableau-synthese}) récapitule la matrice complète **réalisations × compétences**.

\newpage

# Réalisations professionnelles

Cette section présente les **huit réalisations** mobilisées dans le portfolio. Chaque fiche suit une structure normalisée : contexte, productions, compétences mobilisées, outils, lien.

L'ensemble couvre les six compétences du Bloc 1 et permet de présenter des contextes professionnels variés (édition logicielle, identité décentralisée, agence digitale, plateforme web, association, projet personnel).

---

## Réalisation 1 — Hop Hop Immo : Hoppy & SEO

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C2, B1-C3, B1-C4, B1-C5

\textbf{Organisation :} Hop Hop Immo / LES CLES DU NEUF — Saint-Médard-en-Jalles \quad
\textbf{Période :} 5 janvier — 13 février 2026 (stage) · alternance prévue 09/2026 \quad
\textbf{Modalité :} En équipe (équipe produit + marketing)

\textbf{Démo :} \href{https://hophopimmo.com}{hophopimmo.com}

\end{tcolorbox}

### Contexte

Stage ingénieur logiciel (convention BTS SIO, du 5 janvier au 13 février 2026 ; alternance prévue à compter de septembre 2026). **Hop Hop Immo** (marque commerciale opérée par la société **LES CLES DU NEUF**) est une plateforme immobilière proposant un assistant vocal d'IA — **Hoppy** — capable de qualifier les prospects sur une base de 28 000+ annonces, disponible 24/7. L'entreprise développe également une suite d'agents IA pour automatiser le marketing.

### Description de la réalisation

Trois axes de travail durant le stage :

1. **Hoppy — assistant vocal immobilier.** Conception et développement du service vocal s'appuyant sur l'API ElevenLabs (TTS/STT) et un LLM pour la qualification conversationnelle. Intégration à la base d'annonces, gestion des sessions, monitoring production.
2. **Agents IA marketing.** Développement d'agents autonomes pour la génération de contenu et l'animation des réseaux sociaux.
3. **Refonte SEO de la homepage.** Refonte architecturale en Next.js avec optimisation Core Web Vitals (scores Lighthouse > 95/100), balisage sémantique, optimisation du parcours utilisateur. **Triplement du trafic organique en 3 mois.**

### Productions et livrables

- Service Hoppy en production (API publique, dashboard de supervision)
- Documentation développeur (architecture, déploiement, intégrations)
- Pipeline CI/CD GitHub Actions vers Vercel
- Suivi d'incidents via GitHub Issues / Linear

### Outils et technologies

`Next.js` · `Node.js` · `TypeScript` · `ElevenLabs API` · `LLM (GPT-4 / Claude)` · `PostgreSQL` · `Vercel` · `GitHub Actions` · `Lighthouse` · `Google Search Console` · `Linear`

\newpage

## Réalisation 2 — Verana Visualizer

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C1, B1-C4, B1-C5

\textbf{Organisation :} Verana / 2060.io — full remote \quad
\textbf{Période :} Septembre 2025 — en cours \quad
\textbf{Modalité :} En équipe distribuée (full remote, équipe internationale)

\textbf{Démo :} \href{https://verana.io}{verana.io}

\end{tcolorbox}

### Contexte

Verana développe le **Verifiable Trust Network**, infrastructure d'identité numérique décentralisée (DIDs, Verifiable Credentials, trust registries) pour permettre aux organisations d'émettre, vérifier et révoquer des références numériques cryptographiquement signées. Le **Verana Visualizer** est l'application web qui permet d'explorer ce réseau (registres de confiance, DIDs, credentials, schémas).

### Description de la réalisation

- Conception et développement du Visualizer en Next.js / React / TypeScript / Tailwind, en interaction avec les APIs blockchain et les services backend Node.js
- Mise en place de l'infrastructure de déploiement : **Docker, Kubernetes/Helm**, pipelines CI/CD GitHub Actions, gestion d'environnements multi-cloud (staging, production)
- Recensement et documentation du **patrimoine numérique** : référentiels d'APIs, normes (W3C DIDs, VC Data Model), registres de schémas
- Stratégies de caching, gestion robuste des erreurs, télémétrie et logs

### Productions et livrables

- Application Verana Visualizer en production
- Charts Helm et manifests Kubernetes versionnés
- Documentation technique (README, architecture, runbook)
- Pull Requests revues par l'équipe lead

### Outils et technologies

`Next.js` · `React` · `TypeScript` · `Tailwind` · `Node.js` · `Docker` · `Kubernetes` · `Helm` · `GitHub Actions` · `CI/CD` · `Slack` · `Linear` · `Notion`

\newpage

## Réalisation 3 — Concieragent (orchestration MCP × DIDComm)

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C4, B1-C5

\textbf{Organisation :} Verana / 2060.io \quad
\textbf{Période :} Octobre 2025 — en cours \quad
\textbf{Modalité :} En équipe (POC interne)

\textbf{Code :} \href{https://github.com/AirKyzzZ/concieragent-hologram-demo}{github.com/AirKyzzZ/concieragent-hologram-demo}

\end{tcolorbox}

### Contexte

Concieragent est un agent IA conversationnel orchestrant 6 serveurs **MCP (Model Context Protocol)** — vols, hôtels, météo, devises, etc. — via le protocole **DIDComm** chiffré pour la communication agent-à-agent. Il supporte plusieurs LLM (GPT-4, Claude, Ollama) et constitue un cas d'usage concret de l'identité numérique décentralisée appliquée aux agents autonomes.

### Description de la réalisation

- Architecture multi-LLM avec sélection dynamique du modèle selon la tâche
- Orchestration des 6 serveurs MCP avec gestion des erreurs et retry
- Communication DIDComm chiffrée entre l'agent client et les serveurs
- Interface de démonstration (hologramme) pour présentations clients
- Tests d'intégration et d'acceptation, déploiement et accompagnement utilisateurs lors des démonstrations

### Productions et livrables

- Code source publié sur GitHub
- Documentation d'utilisation et d'architecture
- Démonstrations clients en conditions réelles

### Outils et technologies

`MCP` · `DIDComm` · `Claude API` · `GPT-4` · `Ollama` · `TypeScript` · `Node.js`

\newpage

## Réalisation 4 — Klyx (agence digitale)

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C2, B1-C3, B1-C4, B1-C5, B1-C6

\textbf{Organisation :} Klyx — agence indépendante \quad
\textbf{Période :} Avril 2025 — en cours \quad
\textbf{Modalité :} Seul, en relation directe avec les clients

\textbf{Démo :} \href{https://klyx.fr}{klyx.fr}

\end{tcolorbox}

### Contexte

Klyx est une **agence de création digitale** que j'ai fondée et que je dirige. Elle accompagne les TPE/PME dans la conception de sites web élégants, performants et conformes (RGPD, accessibilité). Plus de 5 clients accompagnés, scores Lighthouse systématiquement supérieurs à 95/100, **+80% de trafic organique** et **+35% de leads** générés en moyenne pour les clients.

### Description de la réalisation

- **Pilotage projet en mode Agile** : sprints, livrables contractuels, daily avec les clients, rétrospectives, gestion du backlog (Notion / Trello)
- **Maintenance corrective et évolutive** des sites clients : tickets via GitHub Issues / Linear, mises à jour de dépendances, ajout de nouvelles fonctionnalités
- **Référencement et présence en ligne** : optimisation SEO, intégration Google Analytics, conformité RGPD (mentions légales, politique de confidentialité, gestion des cookies)
- **Développement professionnel continu** : montée en compétence sur les nouvelles versions de Next.js, React, intégration des LLM dans les workflows, lecture de spécifications W3C

### Productions et livrables

- 5+ sites clients en production
- Charte de service (devis, contrat, conditions générales)
- Templates internes Next.js 15 + Tailwind 4 + shadcn/ui
- Documentation processus (onboarding client, livraison, maintenance)

### Outils et technologies

`Next.js` · `TypeScript` · `Tailwind CSS` · `shadcn/ui` · `WordPress` · `Vercel` · `Trello` · `Notion` · `Figma` · `Google Analytics` · `GitHub Issues` · `Linear`

\newpage

## Réalisation 5 — PKBA (Parkour Bassin d'Arcachon)

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C1, B1-C3, B1-C4, B1-C5, B1-C6

\textbf{Organisation :} PKBA — association sportive \quad
\textbf{Période :} Juillet 2025 — en cours \quad
\textbf{Modalité :} En équipe (bureau associatif), rôle de co-fondateur \& trésorier

\textbf{Démo :} \href{https://pkba.vertiflow.fr/}{pkba.vertiflow.fr}

\end{tcolorbox}

### Contexte

Co-fondateur et trésorier du **plus grand club de parkour de Nouvelle-Aquitaine** (60+ licenciés). En charge de la structuration administrative, de la communication digitale et du système d'information de l'association.

### Description de la réalisation

- **Gestion du patrimoine informatique de l'association** : inventaire des ressources (hébergement, noms de domaine, comptes réseaux sociaux), définition des droits d'accès par rôle (président, trésorier, communication), plan de sauvegarde du site web
- **Site web** : développement Next.js avec inscriptions en ligne, boutique Stripe, gestion de dons défiscalisables
- **Communication digitale** : identité visuelle (logo, charte graphique), animation des réseaux sociaux, newsletters
- **Mode projet associatif** : assemblées générales, ordre du jour, comptes-rendus, suivi budgétaire

### Productions et livrables

- Site PKBA en production
- Charte graphique et identité visuelle complète
- Comptabilité associative (livre de recettes/dépenses, bilan)
- Plan de communication et calendrier éditorial

### Outils et technologies

`Next.js` · `Stripe` · `Airtable` · `Tailwind CSS` · `WordPress` · `Cloudflare` · `Canva` · `Instagram` · `Mailchimp`

\newpage

## Réalisation 6 — OpenClaw (veille IA personnelle)

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C5, B1-C6

\textbf{Organisation :} Projet personnel \quad
\textbf{Période :} 2025 — en cours \quad
\textbf{Modalité :} Seul

\end{tcolorbox}

### Contexte

OpenClaw est mon **outil de veille technologique IA personnel**. Il agrège chaque matin les sources tech les plus fiables (RSS, X/Twitter, blogs spécialisés), les analyse avec un LLM, et génère un rapport personnalisé envoyé chaque matin par email. Cette réalisation matérialise ma stratégie de veille structurée (compétence B1-C6).

### Description de la réalisation

- Agrégation de sources : RSS (HackerNews, blogs Vercel, Anthropic, OpenAI), API X/Twitter (comptes curés)
- Analyse avec un LLM : déduplication, tri par pertinence, génération de résumés contextualisés
- Génération du rapport quotidien personnalisé envoyé par email
- Mise en production : tâche cron, monitoring, journal des envois

### Productions et livrables

- Service OpenClaw en production (rapport quotidien)
- Code source TypeScript / Node.js
- Configuration des sources et des prompts d'analyse

### Outils et technologies

`Node.js` · `TypeScript` · `LLM API (Claude / GPT)` · `RSS` · `X API` · `Cron` · `Email`

\newpage

## Réalisation 7 — Reciproq

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C2, B1-C4, B1-C5

\textbf{Organisation :} Reciproq \quad
\textbf{Période :} 22 avril — 30 mai 2025 \quad
\textbf{Modalité :} En équipe pluridisciplinaire (dev + design + produit), méthodologie Agile

\textbf{Démo :} \href{https://reciproq.com}{reciproq.com}

\end{tcolorbox}

### Contexte

Reciproq est une **plateforme de mise en relation entre professionnels de santé mentale et particuliers**. Stage de découverte permettant un premier contact avec une équipe produit en méthodologie Agile.

### Description de la réalisation

- Développement des **pages clés du site vitrine** en Next.js et Tailwind
- Adaptation de la **charte graphique Figma** à l'interface web
- Mise en place d'un **design mobile-first** pour une expérience utilisateur optimale
- Création de **modules dynamiques** pour témoignages et offres
- **Identification et résolution rapide de bugs** signalés pendant les tests utilisateurs
- Itérations hebdomadaires en mode Agile, démo finale au Product Owner

### Productions et livrables

- Pages du site vitrine en production
- Modules dynamiques (témoignages, offres) intégrés au CMS
- Suivi des tickets via GitHub Issues / Slack

### Outils et technologies

`Next.js` · `Tailwind CSS` · `Figma` · `GitHub` · `Slack` · `Méthodologie Agile`

\newpage

## Réalisation 8 — Side Projects \& Open Source

\begin{tcolorbox}[
  enhanced,breakable,
  colback=blue!3,colframe=blue!40,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]

\textbf{Compétences mobilisées :} B1-C4, B1-C5, B1-C6

\textbf{Organisation :} Projets personnels \& open source \quad
\textbf{Période :} 2024 — en cours \quad
\textbf{Modalité :} Seul ou en collaboration ouverte

\textbf{GitHub :} \href{https://github.com/airkyzzz}{github.com/airkyzzz}

\end{tcolorbox}

### Contexte

Plus de 15 projets personnels et contributions open source qui matérialisent mon engagement dans le **développement professionnel continu** (compétence B1-C6) et la mise à disposition de services concrets (compétence B1-C5).

### Réalisations principales

- **Credat.io** — SDK open source publié sur npm (`@credat/sdk`, licence Apache 2.0). Trust layer pour agents IA autonomes : émission, vérification et révocation de credentials par les agents. Mise à disposition à la communauté avec documentation et exemples.
- **PKVision** — détection automatique de tricks parkour par vision par ordinateur (Python, ViTPose). Pipeline d'extraction de poses, classification des mouvements, génération de statistiques.
- **Claw4S** — projet présenté lors du **hackathon Stanford / Princeton 2026**.
- **Certifications** : Harvard CS50x (août 2025 — janvier 2026), EFSET C2 Proficient (87/100).

### Productions et livrables

- Package npm `@credat/sdk` (Apache 2.0)
- Repository GitHub PKVision
- Présentation Claw4S au hackathon Stanford / Princeton
- Certificats CS50x et EFSET C2

### Outils et technologies

`TypeScript` · `Python` · `SD-JWT` · `DIDs` · `LangGraph` · `ViTPose` · `npm` · `GitHub`

\newpage

# Veille technologique

La compétence **B1-C6 — Organiser son développement professionnel** mobilise une stratégie de veille structurée et continue. Mon dispositif s'appuie sur trois piliers complémentaires.

## OpenClaw — agrégateur quotidien IA

Outil personnel développé pour agréger les sources tech fiables, les analyser avec un LLM et générer un rapport quotidien personnalisé. Détaillé en réalisation 6.

## GDG Bordeaux — communauté tech

Membre actif depuis octobre 2024 du **Google Developer Group Bordeaux**. 15+ meetups et codelabs suivis (Flutter, TensorFlow, Angular, PWA, Firebase). Co-animation d'un mini-atelier Flutter. Réseau de 100+ contacts tech en Nouvelle-Aquitaine.

## Sources de référence suivies

| Catégorie | Sources |
|-----------|---------|
| Web moderne | Vercel Blog, Next.js releases, React, MDN |
| IA & LLM | Anthropic, OpenAI, Hugging Face, Hacker News |
| SSI / DIDs | W3C VC Data Model, DIF, OpenID Connect |
| DevOps | Kubernetes Blog, GitHub Changelog |
| Veille français | Bortzmeyer, Korben, FrenchWeb |

\newpage

# Tableau de synthèse \label{tableau-synthese}

\textbf{Document obligatoire de l'épreuve E5} — modèle officiel \textbf{Annexe VI-1} de la circulaire nationale BTS SIO 2026.

\vspace{0.3cm}

\begin{tcolorbox}[
  enhanced,
  colback=black!2,colframe=black!50,
  boxrule=0.4pt,arc=2pt,
  left=8pt,right=8pt,top=8pt,bottom=8pt
]
\textbf{NOM et prénoms :} MANSIET Maxime Louis François \hfill \textbf{N° candidat :} 02248411067\\
\textbf{Centre de formation :} EPSI Bordeaux \hfill \textbf{Option :} \(\square\) SISR \quad \(\blacksquare\) SLAM\\
\textbf{Adresse URL du portfolio :} \href{https://e5.maximemansiet.fr}{https://e5.maximemansiet.fr}
\end{tcolorbox}

\vspace{0.3cm}

\renewcommand{\arraystretch}{1.3}
\footnotesize

\begin{longtable}{p{0.36\textwidth} p{0.10\textwidth} *{6}{>{\centering\arraybackslash}p{0.05\textwidth}}}
\toprule
\textbf{Réalisations professionnelles}\newline\textit{(intitulé et productions associées)} & \textbf{Période} & \textbf{C1} & \textbf{C2} & \textbf{C3} & \textbf{C4} & \textbf{C5} & \textbf{C6} \\
\midrule
\endhead

\multicolumn{8}{l}{\cellcolor{black!10}\textbf{Réalisations en cours de formation}}\\
\midrule

\textbf{Side Projects \& Open Source} — Credat.io (SDK \texttt{@credat/sdk} publié sur npm, Apache 2.0), PKVision (détection IA tricks parkour Python/ViTPose), Claw4S Hackathon Stanford/Princeton 2026.\newline\textit{Productions :} packages npm, repositories GitHub, présentations.
& 09/2024\newline $\to$ 06/2026
& & & & \cmark & \cmark & \cmark \\
\addlinespace[2pt]

\textbf{OpenClaw} — outil personnel de veille technologique IA (agrégation RSS + X + LLM, rapport quotidien personnalisé).\newline\textit{Productions :} service en production, code source TypeScript/Node.js, pipeline cron.
& 09/2025\newline $\to$ 06/2026
& & & & & \cmark & \cmark \\
\addlinespace[2pt]

\textbf{Veille technologique structurée} — GDG Bordeaux (15+ meetups Flutter/TensorFlow/Angular/PWA), animation mini-atelier Flutter, réseau 100+ contacts tech.\newline\textit{Productions :} compte-rendus, présentations.
& 10/2024\newline $\to$ 06/2026
& & & & & & \cmark \\
\midrule

\multicolumn{8}{l}{\cellcolor{black!10}\textbf{Réalisations en milieu professionnel — 1\textsuperscript{ère} année}}\\
\midrule

\textbf{Reciproq} — Plateforme santé mentale. Développement frontend Next.js/Tailwind, charte Figma, design mobile-first, modules dynamiques, méthodologie Agile, résolution bugs.\newline\textit{Productions :} pages site en production (\url{https://reciproq.com}), modules dynamiques, tickets résolus.
& 22/04/2025\newline $\to$ 30/05/2025
& & \cmark & & \cmark & \cmark & \\
\addlinespace[2pt]

\textbf{Klyx} — Agence de création digitale (fondateur). Pilotage 5+ projets clients en Agile, sites Next.js, scores Lighthouse >95/100, +80\% trafic organique, conformité RGPD, maintenance corrective et évolutive.\newline\textit{Productions :} 5+ sites en production (\url{https://klyx.fr}), templates internes, documentation processus.
& 01/04/2025\newline $\to$ 06/2026
& & \cmark & \cmark & \cmark & \cmark & \cmark \\
\midrule

\multicolumn{8}{l}{\cellcolor{black!10}\textbf{Réalisations en milieu professionnel — 2\textsuperscript{ème} année}}\\
\midrule

\textbf{Verana / 2060.io} — Verana Visualizer (dashboard trust registries / DIDs / VC). Next.js/React/TS, infra Docker/Kubernetes/Helm, CI/CD GitHub Actions, gestion patrimoine numérique en équipe distribuée full remote.\newline\textit{Productions :} application en production (\url{https://verana.io}), charts Helm, manifests K8s, documentation technique.
& 01/09/2025\newline $\to$ 06/2026
& \cmark & & & \cmark & \cmark & \\
\addlinespace[2pt]

\textbf{PKBA — Parkour Bassin d'Arcachon} — Co-fondateur \& trésorier. Gestion patrimoine informatique (inventaire, droits, sauvegardes), site web Next.js (inscriptions, Stripe, dons), identité visuelle, structuration administrative (60+ licenciés).\newline\textit{Productions :} site en production (\url{https://pkba.vertiflow.fr}), charte graphique, comptabilité associative.
& 01/07/2025\newline $\to$ 06/2026
& \cmark & & \cmark & \cmark & \cmark & \cmark \\
\addlinespace[2pt]

\textbf{Hop Hop Immo / LES CLES DU NEUF} — Stage ingénieur logiciel (convention BTS SIO, alternance 09/2026). Hoppy : assistant immobilier vocal IA (ElevenLabs + LLM, base 28k+ annonces, 24/7). Agents IA marketing. Refonte SEO homepage Next.js (trafic organique x3 en 3 mois, Lighthouse >95).\newline\textit{Productions :} Hoppy en production (\url{https://hophopimmo.com}), agents IA marketing, refonte SEO.
& 05/01/2026\newline $\to$ 13/02/2026
& & \cmark & \cmark & \cmark & \cmark & \\
\addlinespace[2pt]

\textbf{Concieragent} — Agent IA orchestrant 6 serveurs MCP (vols, hôtels, météo, devises) via DIDComm chiffré. Architecture multi-LLM (GPT-4, Claude, Ollama). Démos clients en conditions réelles.\newline\textit{Productions :} code source GitHub, documentation, démonstrations.
& 01/10/2025\newline $\to$ 06/2026
& & & & \cmark & \cmark & \\
\bottomrule
\end{longtable}

\normalsize
\renewcommand{\arraystretch}{1.0}

\vspace{0.3cm}

**Légende des compétences du Bloc 1 :**

\footnotesize

| Code | Compétence officielle (référentiel BTS SIO) |
|------|---------------------------------------------|
| **C1** | Gérer le patrimoine informatique |
| **C2** | Répondre aux incidents et aux demandes d'assistance et d'évolution |
| **C3** | Développer la présence en ligne de l'organisation |
| **C4** | Travailler en mode projet |
| **C5** | Mettre à disposition des utilisateurs un service informatique |
| **C6** | Organiser son développement professionnel |

\normalsize

\vspace{0.4cm}

**Couverture du bloc :** les six compétences sont chacune couvertes par au moins deux réalisations. Les compétences C4 (Travailler en mode projet) et C5 (Mettre à disposition un service) sont mobilisées de façon transversale dans la quasi-totalité des contextes professionnels présentés. Le tableau au format `.xlsx` (Annexe VI-1 officielle) sera également apporté imprimé le jour de l'épreuve, conformément aux instructions de la circulaire nationale.

\newpage

# Annexes

## A1 — Portfolio numérique en ligne

Le présent dossier est complété par un **portfolio numérique interactif** accessible à l'adresse :

\begin{center}
\Large \href{https://e5.maximemansiet.fr}{\textbf{e5.maximemansiet.fr}}
\end{center}

Le portfolio en ligne propose :

- une présentation visuelle et animée du parcours de professionnalisation
- des fiches projet détaillées avec galerie d'images
- la grille des six compétences enrichie d'outils interactifs
- le tableau de synthèse dynamique
- les liens directs vers les démos et codes source des réalisations

## A2 — Attestations de présence en entreprise

Conformément à la circulaire nationale BTS SIO 2026 (Annexe IX), les **attestations de stage** sont fournies dans un fichier séparé sur Cyclade :

\begin{center}
\textbf{BTSSIPRESENTE5.pdf}
\end{center}

Il regroupe :

1. Attestation de stage Reciproq (avril–mai 2025)
2. Attestation de stage Hop Hop Immo (janvier 2026 — en cours)

## A3 — Tableau de synthèse au format officiel (.xlsx)

Le tableau de synthèse est également disponible au **format Office Open XML (.xlsx)**, conforme au modèle officiel **Annexe VI-1** fourni avec la circulaire nationale 2026 :

\begin{center}
\textbf{Annexe-VI-1-tableau-synthese.xlsx}
\end{center}

Ce fichier sera apporté imprimé le jour de l'épreuve, conformément aux instructions du document SIEC. Il est également téléchargeable depuis le portfolio en ligne.

## A4 — Conformité de l'environnement technologique

Les réalisations présentées s'inscrivent dans un environnement technologique conforme à l'**Annexe II.E** du référentiel BTS SIO 2020 (option SLAM) :

- **Frameworks de développement web :** Next.js, React, Tailwind CSS
- **Langages :** TypeScript, JavaScript, Python, Node.js
- **Bases de données :** PostgreSQL
- **Conteneurisation et orchestration :** Docker, Kubernetes, Helm
- **CI/CD et versioning :** Git, GitHub, GitHub Actions
- **Hébergement et déploiement :** Vercel, Netlify, multi-cloud Kubernetes
- **Méthodologie de gestion de projet :** Agile (sprints, daily, rétrospectives), outils Notion / Linear / Trello

\vfill

\begin{center}
\rule{0.4\textwidth}{0.4pt}\\[0.3em]
\textit{Fin du dossier — Maxime Mansiet, BTS SIO SLAM, EPSI Bordeaux, session 2026.}
\end{center}
