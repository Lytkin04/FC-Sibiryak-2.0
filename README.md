# ⚽ FC Sibiryak Bratsk — Сайт фан-клуба

Это простой сайт для фанатов футбольного клуба **FC Sibiryak Bratsk**, реализованный на **PHP + MySQL**. Поддерживает вход по ролям: **администратор** и **фанат**.

## 📂 Структура

- `index.php` — страница входа
- `/pages/fan.php` — фанатская страница с информацией о клубе
- `/pages/admin.php` — панель администратора со списком фанатов
- `/includes/db.php` — подключение к базе данных
- `/includes/login.php` — логика авторизации
- `/includes/logout.php` — выход из системы
- `sibiryak.sql` — SQL-дамп для phpMyAdmin

## 🔧 Установка и запуск (через XAMPP)

1. Скачайте и установите [XAMPP](https://www.apachefriends.org/index.html)
2. Скопируйте проект в папку `htdocs`:

3. Запустите **Apache** и **MySQL** через панель XAMPP
4. Импортируйте базу данных:
- Перейдите в [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
- Создайте базу `sibiryak`
- Перейдите в неё → "Import" → выберите `sibiryak.sql` из архива проекта

5. Откройте сайт:
http://localhost/fc_sibiryak_php_site


## 👤 Данные для входа

### Админ
- **Email:** `admin@sibiryak.ru`
- **Пароль:** `admin123`

### Фанат
- **Email:** `fan1@sibiryak.ru`
- **Пароль:** `fan123`

## ✅ Возможности

- Авторизация через email
- Разделение доступа по ролям (админ, фанат)
- Статическая информация о клубе
- Список зарегистрированных фанатов (для админа)
