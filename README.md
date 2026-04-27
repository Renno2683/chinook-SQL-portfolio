# 🎵 Chinook Music Store — SQL Data Analysis Portfolio

**Tools:** SQL (SQLite / PostgreSQL / MySQL compatible) | **Database:** Chinook Sample Database  
**Author:** Ranim | **Focus:** Business Insights through SQL

---

## 📌 Project Overview

This project explores the **Chinook digital music store database** to uncover actionable business insights using SQL. The analysis simulates real-world tasks a Data Analyst might perform — from revenue tracking to customer behaviour and employee performance.

The Chinook database models a digital media store, including tables for artists, albums, tracks, invoices, customers, and employees.

---

## 🗂️ Database Schema (Key Tables)

| Table | Description |
|---|---|
| `Customer` | Customer info including country and support rep |
| `Invoice` | Sales transactions with totals and dates |
| `InvoiceLine` | Line items per invoice (track + quantity + price) |
| `Track` | Song details including genre, media type, composer |
| `Album` | Albums linked to artists |
| `Artist` | Artist names |
| `Genre` | Music genres |
| `Employee` | Staff info including title and reporting structure |
| `Playlist` | Curated playlists |

---

## 🔍 Business Questions Answered

### 💰 1. Sales & Revenue Analysis
- What is the total revenue generated?
- Which countries generate the most sales?
- What are the monthly sales trends?
- Which invoice had the highest total?

### 🎵 2. Track & Genre Performance
- Which genres are the most purchased?
- What are the top 10 best-selling tracks?
- Which media type drives the most revenue?

### 👤 3. Customer Behaviour
- Who are the top 10 customers by spend?
- Which customers have made only one purchase?
- How much has each customer spent on average per invoice?

### 🧑‍💼 4. Employee Performance
- Which sales support agent has generated the most revenue?
- How many customers does each employee manage?

---

## 📁 Files in This Repository

```
chinook-sql-portfolio/
│
├── README.md                  ← You are here
├── chinook_analysis.sql       ← All queries, organised by theme
└── schema_diagram.png         ← (Optional) Entity Relationship Diagram
```

---

## ▶️ How to Run

1. Download the Chinook database:
   - SQLite version: [chinook.db](https://github.com/lerocha/chinook-database/releases)
   - PostgreSQL / MySQL scripts also available at the same repo

2. Open with your preferred tool:
   - **DB Browser for SQLite** (free, beginner-friendly)
   - **DBeaver** (works with all databases)
   - **pgAdmin** (for PostgreSQL)

3. Open `chinook_analysis.sql` and run any query section

---

## 📊 Key Insights

> Here are some of the most interesting findings from the analysis:

- 🇺🇸 **USA leads in total sales**, followed by Canada and France
- 🎸 **Rock is the dominant genre**, accounting for the majority of track purchases
- 💡 Top 3 customers each spent over **$40 USD** in the store
- 📅 Sales show a **relatively consistent monthly pattern**, with minor seasonal peaks
- 🏆 **Jane Peacock** (Sales Support Agent) leads in total revenue among employees

---

## 🚀 About This Project

This portfolio project was built as part of my transition into a **Data Analyst** role. It demonstrates:

- Writing clean, readable SQL with comments
- Thinking in business questions, not just queries
- Organising and presenting analysis professionally

---

## 🔗 Connect With Me

- 💼 [LinkedIn](https://linkedin.com/in/ranim-c-07571836a)
- 🐙 [GitHub](https://github.com/Renno2683)
