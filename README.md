<div align="center">

# Supun ERP — Fuji Industries

**Retail & wholesale ERP for day-to-day business operations**

<img src="https://img.shields.io/badge/Laravel-9-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" />
<img src="https://img.shields.io/badge/PHP-8.0-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
<img src="https://img.shields.io/badge/MariaDB-10.4-003545?style=flat-square&logo=mariadb&logoColor=white" alt="MariaDB" />
<img src="https://img.shields.io/badge/Bootstrap-UI-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap" />

</div>

---

## Overview

A local ERP system for **electronics retail and wholesale operations**. It brings purchasing, inventory, sales and customer finance into one system.

## Main Modules

- Product and master data
- Purchase Orders and GRN
- Inventory with weighted-average costing
- Sales and POS
- Customer receipts and allocations
- Customer advances
- Customer ledgers
- Receivables aging

## Business Flow

```text
Purchase → Receive Stock → Sell → Receive Payment → Allocate → Track Balance
```

## Local Setup

1. Start Apache and MySQL/MariaDB in XAMPP.
2. Copy `.env.example` to `.env`.
3. Configure the database.
4. Install dependencies and run migrations.

```powershell
composer install
php artisan key:generate
php artisan migrate --seed
php artisan test
```

## Documentation

- `DEVELOPMENT_PLAN.md`
- `DATABASE_DESIGN.md`
- `MODULES.md`
- `RELEASE_CHECKLIST.md`

> **Note:** This project currently uses PHP 8.0 and Laravel 9 for local compatibility. Upgrade the stack before using it as a production system.

---

<div align="center">
  <b>Inventory • Sales • Finance • Operations</b>
</div>
