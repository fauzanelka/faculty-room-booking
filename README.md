# Laravel 7 Room Booking Case

Simple project with ability to search for available room and book them, also see events on the calendar, filtered by room or booked user.

![Laravel Room Booking screenshot](https://quickadminpanel.com/blog/wp-content/uploads/2020/04/Screen-Shot-2020-04-11-at-9.22.39-PM.png)

---

![Laravel Room Booking screenshot](https://quickadminpanel.com/blog/wp-content/uploads/2020/04/Screen-Shot-2020-04-11-at-9.26.46-PM.png)

---

Adminpanel is generated with Laravel generator: [QuickAdminPanel.com](https://quickadminpanel.com)

## Prerequisites

- PHP 7.2

## Quick Start

Clone this project

```bash
git clone https://github.com/fauzanelka/faculty-room-boking.git
```

Copy `.env.example` to `.env` and set your variables

```bash
cp .env.example .env
```

Update composer dependencies

```bash
composer update
```

Generate application key

```bash
php artisan key:generate
```

Run migration

```bash
php artisan migrate --seed
```

Run server

```bash
php artisan serve
```
