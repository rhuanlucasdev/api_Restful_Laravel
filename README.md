# 🚀 Projeto Fullstack — API Restful em Laravel + Frontend em ReactJS

Este repositório contém uma aplicação **Fullstack**, composta por:

- **Backend:** API Restful desenvolvida em Laravel
- **Frontend:** SPA (Single Page Application) desenvolvida em ReactJS
- Comunicação via **JSON**, seguindo boas práticas de arquitetura, versionamento e organização.

---

## 📁 Estrutura do Repositório

```
/backend → API Laravel (servidor, autenticação, banco de dados)
/frontend → Aplicação ReactJS (interface, consumo da API)
```

Cada parte possui seu próprio README detalhado.

---

## 🛠 Tecnologias Utilizadas

### ✅ Backend (Laravel)

- PHP 8+
- Laravel 10+
- Laravel Sanctum ou JWT
- Eloquent ORM
- SQLite / MySQL
- Migrations & Seeders

### ✅ Frontend (ReactJS)

- React 18+
- Axios
- React Router
- Vite
- Context API / Redux (opcional)

---

## ▶️ Como rodar o projeto completo

### 🔹 1. Backend

```
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

A API iniciará em:
**http://127.0.0.1:8000**

---

### 🔹 2. Frontend

```
cd frontend
npm install
npm run dev
```

O frontend iniciará em:
**http://localhost:5173**

---

## 🔗 Comunicação Frontend ⇄ Backend

O frontend consome a API utilizando Axios.  
A URL da API deve ser definida no `.env` do frontend:
`VITE_API_URL=http://127.0.0.1:8000/api`

---

## 📄 Licença

Projeto distribuído sob licença **MIT**.

---

## 👤 Autor

**Rhuan Lucas**  
GitHub: https://github.com/rhuanlucasdev
