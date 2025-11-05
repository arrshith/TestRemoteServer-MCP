# KarchuluTracker — Expense Tracker MCP Server

**KarchuluTracker** is a lightweight, asynchronous **Model Context Protocol (MCP)** server built using **FastMCP** and **SQLite**.  
It allows AI assistants (like **Claude Desktop**) to **track, list, and summarize expenses** through natural language, without writing SQL queries manually.

---

## Features

- **AI-Controllable Backend** — Claude (or any MCP-compatible model) can call functions like `add_expense`, `list_expenses`, and `summarize`.
- **SQLite Database** — Lightweight, persistent local database for expense tracking.
- **Async I/O with aiosqlite** — Ensures smooth concurrent access to your DB.
- **Dynamic Expense Categories** — Loaded from a customizable `categories.json` file.
- **Deployable to FastMCP Cloud** — Host and expose your MCP server securely online.
- **Safe Read/Write Operations** — Protected from corruption using `PRAGMA journal_mode=WAL`.

---

