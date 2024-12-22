# CooperApp/KopeAp

## English Version

### Overview
CooperApp (English/French) / KopeAp (Creole) is an open-source app suite designed to empower cooperative institutions in Haiti by modernizing their operations and expanding the range of services offered to their members. Hosted on GitHub, this project provides a scalable and transparent platform for financial and administrative tasks.

### Features

#### 1. KopeCloud
- Modernizes cooperative data systems by migrating them to the cloud.
- Enhances data accessibility, security, and scalability.

#### 2. KopeKach
- Functions like Zelle, allowing instant money transfers within the same cooperative.
- Secure with PIN and biometric authentication.

#### 3. KopeSol
- Facilitates group savings programs ("Sòl") to promote mutual financial support among members.
- Tracks contributions and manages payout schedules.

#### 4. KopeTrans
- Manages international money transfers from countries like the US, Canada, France, and South America to local cooperative accounts.
- Ensures real-time tracking for both members and administrators.

#### 5. KopeBil
- Enables members to pay bills (e.g., internet, phone) directly from their cooperative accounts.

---

### Architecture
- **Frontend**: Built with React.js for web and mobile platforms.
- **Backend**: Node.js/Express.js APIs with PostgreSQL for database management or/and DynamoDB as no.
- **Cloud Integration**: Supports AWS or similar providers for secure hosting.
- **Authentication**: Includes PIN, OTP, and biometric options.

---

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/cooperapp/cooperapp.git
   cd cooperapp
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure environment variables:
   ```env
   DATABASE_URL=postgres://user:password@localhost:5432/cooperapp
   CLOUD_PROVIDER=AWS
   ```

4. Run the application:
   ```bash
   npm start
   ```

---

### Contribution Guidelines
1. Fork the repository and create a feature branch:
   ```bash
   git checkout -b feature/your-feature
   ```
2. Commit your changes and open a pull request.

---

### License
This project is licensed under the MIT License. See the LICENSE file for details.

---

## Version Française

### Aperçu
CooperApp (Anglais/Français) / KopeAp (Créole) est une suite d’applications open source conçue pour renforcer les institutions coopératives en Haïti en modernisant leurs opérations et en élargissant les services offerts à leurs membres. Hébergée sur GitHub, cette solution offre une plateforme transparente et extensible pour les tâches financières et administratives.

### Fonctionnalités

#### 1. KopeCloud
- Modernise les systèmes de données des coopératives en les migrés vers le cloud.
- Améliore l'accessibilité, la sécurité et la scalabilité des données.

#### 2. KopeKach
- Fonctionne comme Zelle, permettant des transferts d’argent instantanés au sein d’une même coopérative.
- Sécurisé avec un code PIN et une authentification biométrique.

#### 3. KopeSol
- Facilite les programmes d'épargne collective (« Sòl ») pour promouvoir l'entraide financière entre les membres.
- Suit les contributions et gère les paiements.

#### 4. KopeTrans
- Gère les transferts d'argent internationaux depuis des pays comme les États-Unis, le Canada, la France et l’Amérique du Sud vers les comptes locaux des coopératives.
- Offre un suivi en temps réel pour les membres et les administrateurs.

#### 5. KopeBil
- Permet aux membres de payer leurs factures (internet, téléphone) directement depuis leurs comptes coopératifs.

---

### Architecture
- **Frontend**: Construit avec React.js pour les plateformes web et mobiles.
- **Backend**: APIs Node.js/Express.js avec PostgreSQL pour la gestion des bases de données.
- **Intégration Cloud**: Prend en charge AWS ou d'autres fournisseurs pour un hébergement sécurisé.
- **Authentification**: Inclut des options PIN, OTP et biométriques.

---

### Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/cooperapp/cooperapp.git
   cd cooperapp
   ```

2. Installez les dépendances :
   ```bash
   npm install
   ```

3. Configurez les variables d'environnement :
   ```env
   DATABASE_URL=postgres://user:password@localhost:5432/cooperapp
   CLOUD_PROVIDER=AWS
   ```

4. Exécutez l'application :
   ```bash
   npm start
   ```

---

### Lignes directrices pour la contribution
1. Forkez le dépôt et créez une branche pour votre fonctionnalité :
   ```bash
   git checkout -b feature/votre-fonctionnalite
   ```
2. Validez vos modifications et ouvrez une pull request.

---

### Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.

