<p align="center">
  <img src="readme-banner.svg" width="100%" alt="Supun ERP" />
</p>

<p align="center"><b>A business operations system for electronics retail and wholesale workflows.</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-9-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/PHP-8.0-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MariaDB-10.4-003545?style=flat-square&logo=mariadb&logoColor=white" alt="MariaDB" />
  <img src="https://img.shields.io/badge/Bootstrap-UI-7952B3?style=flat-square&logo=bootstrap&logoColor=white" alt="Bootstrap" />
</p>

---

## Project Snapshot

| | |
|---|---|
| **Business problem** | Purchasing, stock, sales and customer balances need one connected system. |
| **Solution** | A Laravel ERP that joins inventory, sales and receivables in one workflow. |
| **Business area** | Electronics retail + wholesale. |
| **Main focus** | Operational accuracy, traceability and financial visibility. |

## Business Flow

<p align="center">
  <img src="readme-flow.svg" width="96%" alt="Supun ERP purchase to receivables business flow" />
</p>

## Main Modules

| Operations | Finance & Control |
|---|---|
| Product & master data | Customer receipts |
| Purchase Orders | Payment allocations |
| GRN / stock receiving | Customer advances |
| Weighted-average inventory | Customer ledgers |
| Sales / POS | Receivables aging |

## What This Project Demonstrates

- Mapping a connected purchase-to-payment business process
- Managing stock movement and weighted-average inventory costing
- Linking sales with receipts, allocations and customer balances
- Separating operational modules while keeping one end-to-end workflow
- Using project, database, module and release documentation together

## Engineering Focus

- Weighted-average inventory costing
- Purchase-to-stock traceability
- Sales and customer balance tracking
- Structured database design and migrations
- Seeded development environment
- Automated Laravel tests

## Repository Context

This repository is a **forked/collaborative codebase**. For interview discussion, individual work should be explained using the repository's commit and collaboration history rather than treating the full codebase as single-author work.

## Run Locally

```bash
composer install
php artisan key:generate
php artisan migrate --seed
php artisan test
```

Configure `.env` with the local MariaDB connection before running migrations.

## Project Documentation

- [`DEVELOPMENT_PLAN.md`](DEVELOPMENT_PLAN.md) — implementation roadmap
- [`DATABASE_DESIGN.md`](DATABASE_DESIGN.md) — database structure
- [`MODULES.md`](MODULES.md) — module scope
- [`RELEASE_CHECKLIST.md`](RELEASE_CHECKLIST.md) — release checks

> **Development note:** the current local compatibility stack uses PHP 8.0 and Laravel 9. A production deployment should first upgrade to supported versions.

---

<p align="center"><b>From purchase order to customer balance — one connected operational flow.</b></p>
