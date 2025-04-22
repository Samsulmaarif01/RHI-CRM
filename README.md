
## ⚙️ Instalasi (Local Development)

### 1. Clone Repository
```bash
git clone https://github.com/Samsulmaarif01/RHI-Build-Project-Management.git
```
```bash
cd RHI-Build-Project-Management
```

### 2. Install Dependensi Laravel
```bash
composer install
```
```bash
npm install && npm run build
```

### 3. Konfigurasi Environment
```bash
cp .env.example .env
```
```bash
php artisan key:generate
```

Edit file `.env` seperti berikut:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=project-management
DB_USERNAME=root
DB_PASSWORD=
```

### 4. Jalankan Migrasi & Seeder
```bash
php artisan migrate --seed
```

### 5. Jalankan Server
```bash
php artisan serve
```

---

## 🔐 Login Admin (Filament)
- **URL:** `/admin`  
- **Email:** `admin@rhibuild.test`  
- **Password:** `password`  

> 💡 *Data admin bisa diubah lewat seed atau perintah artisan.*

---
