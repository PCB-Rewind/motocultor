# 🤘 Running Motocultor 2026

Appli web de notation partagée pour préparer le **Motocultor Festival 2026** (Carhaix, 13–16 août).
Note les ~108 groupes (A+ / A / B / C / X), suis ton écoute des albums sur 8 semaines, et génère ton running perso — à plusieurs.

**→ [Ouvrir l'appli](https://TON-PSEUDO.github.io/motocultor/)**

---

## Ce que ça fait

- **Notation par jour** des 4 journées du festival, têtes d'affiche repérées (★).
- **5 niveaux** : A+ (incontournable), A, B, C, X (zappe).
- **Running auto** : ton parcours trié par tes priorités, A+ d'abord, C et X écartés. Les jours à plusieurs A+ sont signalés pour anticiper les conflits d'horaires.
- **Multi-personnes** : toi, Marine, les potes notez dans le même seau. Les avis des autres s'affichent à côté de chaque groupe, ton running reste basé sur **tes** notes.
- **Suivi d'écoute** : coche les groupes écoutés, barre de progression, planning d'écoute réparti sur 8 semaines (`sem. 1` = à faire en priorité).
- **Lien Spotify** sur chaque groupe.
- Fonctionne sur **Mac, iPhone, Android** — une seule URL, notes synchronisées.

---

## Premier lancement

À l'ouverture, l'appli demande trois choses :

| Champ | Quoi |
|---|---|
| **Prénom** | Pour distinguer tes notes de celles des autres. |
| **Bin ID** | L'identifiant du seau partagé (voir ci-dessous). |
| **Master Key** | La clé d'accès au seau. |

Tout est mémorisé sur l'appareil : tu ne le tapes qu'une fois.

### Créer le seau partagé (2 min, gratuit, sans carte bancaire)

1. Va sur [jsonbin.io](https://jsonbin.io) et crée un compte gratuit.
2. **Create Bin**, colle `{}` comme contenu, sauve. Le **Bin ID** est dans l'URL.
3. Menu **API Keys** → copie ta **Master Key** (commence par `$2a$`).
4. Donne le **Bin ID** + la **Master Key** aux autres (en privé) pour qu'ils notent dans le même seau.

> ⚠️ La Master Key donne accès en écriture au seau. À partager uniquement avec ton cercle de confiance, jamais en public.

---

## Mettre à jour l'appli

L'appli est un seul fichier : `index.html`.
Pour publier une nouvelle version, remplace `index.html` dans ce dépôt — GitHub Pages republie tout seul en ~1 min. L'URL ne change pas.

---

## Technique

- HTML / CSS / JS purs, **aucune dépendance**, un seul fichier.
- Stockage des notes via [JSONBin.io](https://jsonbin.io) (seau JSON partagé).
- Hébergé sur **GitHub Pages**.
- Thème clair chaleureux, accessible, responsive, `prefers-reduced-motion` respecté.

---

*Line-up à jour au moment de la création. Quand les horaires officiels par scène sortiront (souvent en juillet), le running pourra intégrer les créneaux pour arbitrer les chevauchements.*
