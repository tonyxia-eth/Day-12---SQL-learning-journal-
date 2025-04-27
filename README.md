# Day-12---SQL-learning-journal-

# ⚾ CS50 Moneyball SQL Review – Bite-Sized Learning (Day 12 Morning Quick Session)

## ✅ Session Overview

Even with only 30 minutes to spare today, I committed to keeping my momentum alive by reviewing critical SQL concepts, focusing on JOIN operations and clean query structure.

---

## 🧠 Skills Practiced

- Understanding how `JOIN` works to connect two tables using IDs
- Writing clean `SELECT ... FROM ... JOIN ... ON ... WHERE ... ORDER BY` queries
- Debugging WHERE vs SELECT mistakes (conditions vs columns)
- Thinking logically about relationships between player data (players) and performance data (performances)

---

## 🛠️ Commands and Queries Used

```bash
sqlite3 moneyball.db
.tables
.schema players
.schema performances
SELECT players.first_name, players.last_name, performances.HR FROM players JOIN performances ON players.id = performances.player_id WHERE performances.year = 2000 AND performances.HR >= 40 ORDER BY players.last_name;

🌱 Reflections
Today I had only 30 minutes free, but I stuck to my commitment to daily learning.
Even short, focused sessions move the needle forward.
I feel much stronger now about how SQL JOINs work — not just in code, but in real thinking: bridging two worlds together via IDs.

📅 Status
📖 Day 12 — Morning Quick Session Completed

🚀 Moneyball Project: Deepening understanding of multi-table SQL queries

🔥 Ready to tackle longer sessions when time allows


