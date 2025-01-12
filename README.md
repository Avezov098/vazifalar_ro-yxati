# Laravel asosida qurilgan Task Manager

Bu **Task Manager** ilovasi Laravel frameworkida yaratilgan. Foydalanuvchilar bir-birlariga topshiriq berishlari, topshiriqlarni boshqarishlari va admin panel orqali umumiy ma'lumotlarni ko‘rishlari mumkin. 

## Xususiyatlari

-   Topshiriqlarni CRUD (Create, Read, Update, Delete) orqali boshqarish.
-   Admin panel orqali umumiy harakatlarni ko‘rib chiqish.

---

## O‘rnatish bo‘yicha yo‘riqnoma

Loyihani o‘rnatish va ishga tushirish uchun quyidagi bosqichlarni bajaring:

### 1. Repozitoriyani klonlash

```bash
git clone git remote add origin https://github.com/Avezov098/vazifalar_ro-yxati.git
cd vazifalar_ro-yxati
composer install
cp .env.example .env
php artisan key:generate
php artisan storage:link
npm install
npm run dev
```


```bash
php artisan migrate --seed
php artisan serve

```

Admin ma'lumotlari: Dastlabki admin hisob ma'lumotlari:

Email: avezovelyor@gmail.com
Parol: password


O'quvchi ma'lumotlari:
Email => worker@gmail.com
password => password
