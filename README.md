# ☕ Iced Coffee API

A simple CRUD API built with **Node.js + Express + SQLite** that manages iced coffee menu items.

---

## Features
- Add new iced coffee (Create)
- Get all iced coffees (Read)
- Get one coffee by ID (Read)
- Update coffee (Update)
- Delete coffee (Delete)

---

## Coffee Model (5+ Columns)
- `id` (UUID)
- `name` (string) → Coffee name
- `size` (string) → Small, Medium, Large
- `price` (number) → Example: 120.00
- `description` (string) → Short details
- `available` (boolean) → true / false

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/iced-coffee-api.git
   cd iced-coffee-api
