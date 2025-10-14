# 🧠 Code Intervention — SQL Edition  

> *“Every dataset tells a story. SQL helps you ask the right questions.”*  
> — Quadri Onigbanjo  

---

## 🎯 Overview  

Welcome to **Code Intervention: SQL Edition** — a live, hands-on experience designed to make SQL practical, visual, and beginner-friendly.  
This deck walks you step by step through everything from *what SQL is* to *how to perform analysis on real-world data.*  

You’ll learn using the **Games + Sales** dataset — simple, clear, and ideal for understanding how data connects and scales.  

---

## 🧱 What’s Inside the Deck  

| Section | Focus | Description |
|----------|--------|-------------|
| **1. History of SQL** | Context | Where SQL came from and why it’s still used today. |
| **2. From Real Life to Database** | Foundations | How apps store data in structured tables. |
| **3. What Is SQL / What Is a Query** | Syntax | Understanding SELECT, FROM, WHERE, and ORDER BY. |
| **4. Tables & Data Types** | Structure | Defining columns, data types, and primary keys. |
| **5. Foreign Keys & Identity** | Relationships | How tables connect and how IDs are generated. |
| **6. Core SQL Commands** | Practice | The 5 core clauses every query uses. |
| **7. Warm-Up Queries** | Hands-On | Practice with SELECT, WHERE, DISTINCT, and ORDER BY. |
| **8. Joins (INNER, LEFT, RIGHT, FULL)** | Relationships | Combine tables to unlock richer data. |
| **9. Aliases** | Clean Queries | Shorten table names and improve readability. |
| **10. GROUP BY & Aggregates** | Summarization | Turn raw data into insights with COUNT, SUM, AVG, MIN, MAX. |
| **11. HAVING vs WHERE** | Logic | Learn when to filter rows vs groups. |
| **12. TOP / FETCH** | Ranking | Limit results and show top performers. |
| **13. SQL Execution Order** | Sequence | See how SQL actually processes your query. |
| **14. Challenge Round** | Practice | Solve real business-style problems. |
| **15. AI Enhancements** | Future Skills | How AI can draft, debug, and optimize SQL. |
| **16. Summary & Feedback** | Reflection | Review all concepts and next steps. |

---

## 🧩 Practice Dataset  

### Games Table  
| Column | Type | Description |
|---------|------|-------------|
| GameID | INT (PK) | Unique ID |
| Title | NVARCHAR | Game title |
| Genre | NVARCHAR | Category |
| ReleaseYear | INT | Year released |
| Price | DECIMAL | Price of game |

### Sales Table  
| Column | Type | Description |
|---------|------|-------------|
| SaleID | INT (PK) | Unique ID |
| GameID | INT (FK) | Linked game |
| SaleDate | DATE | Date sold |
| Quantity | INT | Units sold |
| Country | NVARCHAR | Country of sale |

---

## 🧠 Session Flow  

### Part 1 — Foundations  
Understand tables, keys, and data types.  
👉 Learn `SELECT`, `FROM`, `WHERE`, `ORDER BY`, and `DISTINCT`.  

### Part 2 — Joins & Relationships  
Combine related data using `INNER`, `LEFT`, `RIGHT`, and `FULL` joins.  
👉 Use table aliases (`g`, `s`) for cleaner queries.  

### Part 3 — Aggregations & Grouping  
Summarize data using `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`.  
👉 Explore `GROUP BY` and `HAVING` side by side.  

### Part 4 — Ranking & Filtering  
Use `TOP`, `OFFSET`, and `FETCH` to rank or limit results.  
👉 Discuss SQL execution order — how SQL actually reads your query.  

### Part 5 — Challenge Round  
8 challenge questions combining all key concepts:  
- Total revenue per game  
- Games sold more than 2 copies  
- Top 2 best-selling genres  
- Unsold games  
- Distinct countries  
- 2023 sales (most recent first)  
- Total units per game  
- Genres with average price > £40  

### Part 6 — AI Enhancement (Optional)  
Learn how AI tools like **ChatGPT** or **Copilot** can:  
- Generate draft queries from natural language  
- Explain query errors or suggest optimizations  
- Convert syntax across databases (LIMIT → TOP)  

---

## ⚙️ How to Run the Examples  

### Option 1: SQL Server (Recommended)  
1. Open **SQL Server Management Studio** or **Azure Data Studio**.  
2. Create a new database (e.g., `CodeInterventionDB`).  
3. Run the `Games` and `Sales` table creation scripts.  
4. Copy and run the queries from your handout.  

### Option 2: SQLiteOnline (Quick Start)  
1. Go to [sqliteonline.com](https://sqliteonline.com).  
2. Select **SQL Server** mode.  
3. Paste in your tables and queries.  
4. Hit **Run** — no setup needed.  

---

## 💬 Closing Message  

> “SQL is the foundation of every data system you’ll ever use.  
> Once you understand how to query data, everything else — analytics, AI, automation — becomes easier.”  

**– Code Intervention Team**  

