# 🛒 Aplikacja ZamówieniaApp

Aplikacja do zarządzania zamówieniami, która umożliwia pobieranie towarów z zewnętrznego API, ich zatwierdzanie i zapisywanie do lokalnej bazy danych.

---

## 📦 Technologie

### Backend (ASP.NET Core Web API)

- C# (.NET 8)
- Entity Framework Core
- SQL Server
- Redis (opcjonalnie – cache)
- SignalR (opcjonalnie – live updates)
- Serilog (logowanie)

### Frontend (Next.js)

- Next.js + TypeScript
- Tailwind CSS + shadcn/ui
- Axios (do komunikacji z API)
- SignalR (opcjonalnie – live updates)

---

## ⚙️ Funkcjonalności

- ✅ Pobieranie towarów z zewnętrznego API
- ✅ Prezentacja listy towarów użytkownikowi
- ✅ Możliwość zatwierdzenia wybranych towarów jako zamówienia
- ✅ Zapis zamówienia do lokalnej bazy danych
- ♻️ Buforowanie danych towarów (opcjonalnie – Redis)
- 🔄 Podgląd zamówień na żywo (opcjonalnie – SignalR)

---

## 🧱 Struktura folderów

ZamowieniaApp/
│
├── client/ # Aplikacja frontendowa (Next.js)
│ └── ...
│
├── server/ # Backend ASP.NET Core
│ ├── Controllers/
│ ├── DTOs/
│ ├── Entities/
│ ├── Services/
│ ├── Data/
│ └── Program.cs
│
├── README.md
└── docker-compose.yml (opcjonalnie)
