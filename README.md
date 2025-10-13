

# 🎯 The Code Intervention — Workshop Series

Welcome to **The Code Intervention** GitHub repository — a hands-on series of beginner-friendly coding workshops led by **Quadri Onigbanjo (@quadrifolo)**.  
Each session focuses on breaking down core programming and data concepts through live, practical projects that you can follow along and build yourself.

# Session 1 
# 🔮 Quote Generator Workshop

Build a Quote Generator using **HTML**, **CSS**, and **JavaScript** — perfect for beginners learning web development basics! Created for a live coding workshop to help new devs understand:

- 🧱 HTML: how to structure a webpage  
- 🎨 CSS: how to style it  
- ⚙️ JavaScript: how to make it interactive  
- 🔌 BONUS: API integration using OpenAI 

## 📁 Project Structure

- `starter/` — Starter version (basic layout for live coding)
- `final/` — Fully working quote generator (local quote data)
- `openai-demo/` — Bonus version using OpenAI API (for demo purposes only)



## 🚀 Getting Started

1. **Clone or download** this repository:


2. Open the `starter` folder in **VS Code**  
3. Use **Live Server** or open `index.html` directly in your browser

## ⚠️ About the OpenAI Demo

The `openai-demo` version shows how to call the OpenAI API from the frontend. This is only for demonstration purposes during the workshop — you should **never expose your API key** in a live or public project.

In a future session, we’ll show you how to:
- Use `.env` files properly
- Set up a secure backend to handle API requests
- Protect your keys and keep things safe 🔐

## 🧠 Helpful Resources

- [HTML Cheat Sheet](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [OpenAI API Docs](https://platform.openai.com/docs)


##Session 2

### 🧩 2. SQL Project — *Games & Sales Analysis*
A beginner-level introduction to **SQL** using two tables: `Games` and `Sales`.

**Key Learnings**
- Understanding `SELECT`, `WHERE`, `ORDER BY`, and `DISTINCT`
- Using aggregate functions: `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`
- Grouping data with `GROUP BY` and filtering with `HAVING`
- Writing readable queries using aliases
- Building mini reports (e.g., best-selling games, top genres, total revenue)

**Setup**
1. Visit [SQLite Online](https://sqliteonline.com)
2. Create two tables:
   - `Games` — for storing game info (Title, Genre, Price)
   - `Sales` — for recording quantity sold per game
3. Run the provided SQL setup scripts from the `sql/` folder.

**Example Query**
```sql
SELECT g.Title, SUM(g.Price * s.Quantity) AS TotalRevenue
FROM Games g
INNER JOIN Sales s ON g.GameID = s.GameID
GROUP BY g.Title
ORDER BY TotalRevenue DESC;


