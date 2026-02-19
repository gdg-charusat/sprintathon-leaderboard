# 🏆 GDG CHARUSAT Open Source Contri Sprintathon — Leaderboard

This repository is the **central leaderboard** for the GDG CHARUSAT Sprintathon.  
Points are collected automatically from all 9 participating repositories when PRs are merged.

## 📊 Live Leaderboard

👉 **[View leaderboard.md](./leaderboard.md)**

## 📦 Tracked Repositories

| Repo | Type |
|------|------|
| [Zaplink_frontend](https://github.com/gdg-charusat/Zaplink_frontend) | Frontend |
| [Zaplink_backend](https://github.com/gdg-charusat/Zaplink_backend) | Backend |
| [CareXpert_frontend](https://github.com/gdg-charusat/CareXpert_frontend) | Frontend |
| [CareXpert_backend](https://github.com/gdg-charusat/CareXpert_backend) | Backend |
| [Code_duel_frontend](https://github.com/gdg-charusat/Code_duel_frontend) | Frontend |
| [Code_duel_backend](https://github.com/gdg-charusat/Code_duel_backend) | Backend |
| [FMEA_SupplyChain](https://github.com/gdg-charusat/FMEA_SupplyChain) | ML |
| [super-roast-bot](https://github.com/gdg-charusat/super-roast-bot) | ML |
| [PDF_QA_Bot](https://github.com/gdg-charusat/PDF_QA_Bot) | ML |

## ⚙️ How It Works

1. A contributor opens a PR in any of the 9 repos with their **Team Number** in the description
2. The PR Validator bot labels and validates the PR automatically
3. When an admin merges the PR, the Points Calculator workflow fires
4. Points are written to `leaderboard.json` in **this repo**
5. `leaderboard.md` is regenerated with both team and individual rankings

## Points System

| Level | Label | Points |
|-------|-------|:------:|
| Beginner | `level-1` / `good-first-issue` | 5 pts |
| Intermediate | `level-2` / `intermediate` | 20 pts |
| General Improvement | Admin assigns level on PR | 5 or 20 pts |

---
*Maintained by GDG CHARUSAT · Auto-updated on every merged PR*
