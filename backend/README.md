# 🧩 Backend — API Restful em Laravel

Este diretório contém a API Restful construída com **Laravel 10+**, responsável por autenticação, regras de negócio, banco de dados e exposição de endpoints JSON.

---

## 🚀 Tecnologias

-   PHP 8+
-   Laravel 10+
-   Sanctum / JWT
-   Eloquent ORM
-   Migrations & Seeders
-   SQLite / MySQL

---

## ⚙️ Instalação

### ✅ 1. Instale as dependências

```bash
composer install
```

### ✅ 2. Configure o ambiente

```bash
cp .env.example .env
php artisan key:generate
```

Edite no .env:

# SQLite (recomendado para dev):

```ini
DB_CONNECTION=sqlite
DB_DATABASE=database/database.sqlite
```

Crie o arquivo:

```bash
touch database/database.sqlite
```

### 🗃️ Migrations & Seeders

```bash
php artisan migrate --seed
```

### ▶️ Iniciar servidor

```bash
php artisan serve
```

A API estará em:
➡️ http://127.0.0.1:8000/api

### 📡 Endpoints (exemplo)

| Método | Rota            | Descrição        |
| ------ | --------------- | ---------------- |
| GET    | /api/users      | Lista usuários   |
| POST   | /api/users      | Cria usuário     |
| GET    | /api/users/{id} | Exibe usuário    |
| PUT    | /api/users/{id} | Atualiza usuário |
| DELETE | /api/users/{id} | Remove usuário   |
