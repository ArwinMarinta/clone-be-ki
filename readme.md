<h1 align="center">BE-KI-ITK</h1>

<p align="center">
  <i>Empowering Innovation, Accelerating Impact, Unleashing Potential</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/last-commit/NARajab/BE-KI-ITK?style=flat-square" />
  <img src="https://img.shields.io/github/languages/top/NARajab/BE-KI-ITK?style=flat-square" />
  <img src="https://img.shields.io/github/languages/count/NARajab/BE-KI-ITK?style=flat-square" />
  <img src="https://img.shields.io/github/license/NARajab/BE-KI-ITK?style=flat-square" />
</p>

<p align="center"><i>Built with the tools and technologies:</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/Express-black?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/JSON-000000?style=for-the-badge&logo=json&logoColor=white" />
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" />
  <img src="https://img.shields.io/badge/.ENV-yellowgreen?style=for-the-badge&logo=dotenv&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Nodemon-76D04B?style=for-the-badge&logo=nodemon&logoColor=white" />
  <img src="https://img.shields.io/badge/Sequelize-03AFEF?style=for-the-badge&logo=sequelize&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Axios-6E6EFD?style=for-the-badge&logo=axios&logoColor=white" />
</p>

---

## 📖 Description

<p align="justify">
  <strong>BE-KI-ITK</strong> adalah backend web service untuk sistem inovasi kampus yang dibangun menggunakan Node.js dengan framework Express. Proyek ini menyediakan REST API yang dapat digunakan untuk mengelola data inovasi, autentikasi pengguna, dan pengiriman email notifikasi.
</p>

## ⚙️ Features

- 💻 RESTful API with Express
- 🔐 User authentication with JWT
- 🗄️ Database migrations and seeders using Sequelize CLI
- 🛡️ Rate limiting and security best practices
- 📤 File upload support with Multer\_
- 📧 Email notifications with Nodemailer

### Prerequisites

- Node.js (v16+ recommended)
- PostgreSQL database

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/project-hki.git
   cd project-hki
   ```

2. Install dependencies

   ```bash
   npm install
   ```

3. Create a `.env` file in the root of your project with the following content:
    ```env
    # Server configuration
    PORT=3000
    HOST=localhost

    # Database configuration
    DB_USERNAME=your_db_username
    DB_PASSWORD=your_db_password
    DB_HOST=localhost
    DB_PORT=5432

    # JWT & Security
    PASSWORD_HASH=your_password_hash_key
    SALT_ROUNDS=10
    JWT_SECRET=your_jwt_secret_key
    ```

4. Setup the database
   ```bash
   npm run db:create
   npm run db:migrate
   npm run db:seed
   ```

### Running the app

1. To start the server in production mode:
    ```bash
    npm start
    ```
2. To start the server in development mode with auto-reload:
    ```bash
    npm run dev
    ```
1. To start the server in production mode:
    ```bash
    npm start
    ```

### Other useful scripts
- Drop the database:
    ```bash
    npm run db:drop
    ```
- Undo all migrations::
    ```bash
    npm run db:migrate:undo
    ```
- Run all migrations and seeds:
    ```bash
    npm run db:init
    ```
