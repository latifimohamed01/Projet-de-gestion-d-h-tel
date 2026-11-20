PMS/
├── pms-mobile/                 ← Application mobile Flutter (Client)
│   ├── lib/
│   │   ├── core/
│   │   ├── data/
│   │   └── presentation/
│   └── pubspec.yaml
├── pms-web/                    ← Tableaux de bord web React
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── admin/
│   │   │   ├── manager/
│   │   │   └── receptionist/
│   │   └── services/
│   └── package.json
├── pms-backend/                ← API Node.js + Express
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── config/
│   ├── .env
│   └── package.json
└── database/
    └── schema.sql

---

## 🖥 Écrans de l'application

### Mobile (Client)
| Écran | Description |
|---|---|
| Connexion | Authentification par email / mot de passe |
| Inscription | Création de compte (nom, prénom, email, téléphone, mot de passe) |
| Découvrir | Catégories de chambres et chambres les mieux notées |
| Détails de la chambre | Photos, description, prix, capacité, bouton de réservation |
| Mes réservations | Liste des réservations du client |
| Profil | Informations personnelles et actions |
| Modifier mon profil | Mise à jour du nom, de l'email, du téléphone et de la photo |

### Web (Personnel)
| Écran | Rôle | Description |
|---|---|---|
| Connexion du personnel | Tout le personnel | Authentification par email / mot de passe |
| Vérification du code | Tout le personnel | Code à 6 chiffres reçu par email |
| Nouveau mot de passe | Tout le personnel | Réinitialisation du mot de passe |
| Tableau de bord administrateur | Admin | Chambres, réservations, occupation, revenus |
| Gestion des utilisateurs | Admin | Tableau des utilisateurs avec modification / suppression |
| Liste des chambres / Ajouter une chambre | Admin | CRUD complet des chambres |
| Problèmes | Admin | Problèmes signalés |
| Employés | Gestionnaire | Employés et salaires |
| Planning | Gestionnaire | Planification sous forme de calendrier |
| Budget | Gestionnaire | Synthèse financière |
| Ajouter une réservation | Réceptionniste | Formulaire de réservation avec calcul du prix |
| Liste des réservations | Réceptionniste | Consultation / modification / annulation |
| Programme des employés | Réceptionniste | Horaires du personnel |

---

## 🔮 Perspectives

- Intégration avec des services externes (calendriers, messageries)
- Analyses et rapports avancés
- Système d'avis et de retours clients
- Intégration d'une passerelle de paiement en ligne
- Prise en charge multilingue (arabe / français / anglais)

---

## 📄 Licence

Ce projet a été développé à des fins académiques.
