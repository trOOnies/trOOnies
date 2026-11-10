# Hi, I'm trOOnies 👋

Lately I've been building a family of **small, local-first personal apps** with
[Claude Code](https://claude.com/claude-code). Each one tracks one part of my life, runs on
my own machine, and keeps its data in files I own.

![Python](https://img.shields.io/badge/Python-3.10%2B-3776ab?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003b57?logo=sqlite&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3366cc?logo=htmx&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0a9edc?logo=pytest&logoColor=white)
![Ruff](https://img.shields.io/badge/Ruff-d7ff64?logo=ruff&logoColor=black)
![Built with Claude Code](https://img.shields.io/badge/built%20with-Claude%20Code-d97757?logo=claude&logoColor=white)

## 🛠️ Recent projects

| | Project | What it does |
| :---: | --- | --- |
| <img src="https://raw.githubusercontent.com/trOOnies/pledger/main/src/pledger/web/static/favicon.svg" width="40" alt=""> | **[pledger](https://github.com/trOOnies/pledger)**<br>*Your money, one movement at a time.* | A double-entry personal ledger kept in plain CSV and YAML files. It works out balances, gains and losses, equity over time, investments, debts, credit cards, salaries and inflation-adjusted currencies, and charts them in a FastAPI + HTMX web app. |
| <img src="https://raw.githubusercontent.com/trOOnies/implicated/main/src/implicated/web/static/favicon.svg" width="40" alt=""> | **[implicated](https://github.com/trOOnies/implicated)**<br>*Your music taste, all in one place.* | A tracker for the artists, albums and songs you love: lyrics, playable guitar tabs, playlists and tier lists, a CD and vinyl budget cart, concerts, a Live Play mode, and a Duo tab to compare tastes with a friend. |
| <img src="https://raw.githubusercontent.com/trOOnies/plasma/main/src/plasma/static/plasma.svg" width="40" alt=""> | **[plasma](https://github.com/trOOnies/plasma)**<br>*Series, movies, games and creators.* | Tracks what you're watching and playing, episode by episode, with ratings, franchises in release order, plans, platforms, and what's coming up next. It also has an Influencers tab with collages for the creators you follow. |
| <img src="https://raw.githubusercontent.com/trOOnies/persephone/main/src/persephone/static/favicon.svg" width="40" alt=""> | **[persephone](https://github.com/trOOnies/persephone)**<br>*Your book collection.* | Manages a library of books: who owns each copy and who it's lent to, reading status, half-star ratings, reviews and notes, a wishlist and budget carts, stats, and ISBN lookup with covers from Open Library. |
| 🏃 | **[pamela](https://github.com/trOOnies/pamela)**<br>*Activity and macros.* | A physical activity and macro tracker. Log meals from your own food catalog (with barcode lookup on Open Food Facts), log workouts with calories estimated from MET values, and check daily steps, sleep, weight and mood against your targets. |

## 🧩 What they have in common

- 🔒 **Local and private.** No accounts and no cloud. Everything runs on `127.0.0.1`, and
  your data stays in a local folder you can back up as a zip.
- 🪶 **Small stack.** Python 3.10+, FastAPI, SQLite or plain files, and server-rendered or
  framework-free HTML/CSS/JS. There's no build step and no npm.
- 🚀 **Same commands everywhere.** `make install`, `make seed` for demo data, `make serve`,
  and `make test`, which runs pytest with coverage.
- 🤝 **Duo, export and import.** Most of them can export your data to a small file and
  compare it with a friend's.
- 📖 **Help built in.** Each app has a Help page written for non-technical users.
- ⚖️ **Free software.** All are licensed under GPL-3.0.
