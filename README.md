# Tech Trend Dataset 📈

> Weekly updated dataset of trending tech topics, tools, and signals.

Free, open data for researchers, developers, and analysts.

---

## 📦 Available Data

| File | Description | Updated |
|------|-------------|---------|
| [trending_topics.json](./data/trending_topics.json) | Top 50 trending topics this week | Weekly |
| [hot_products.json](./data/hot_products.json) | Trending products from GitHub & Product Hunt | Weekly |
| [sector_signals.json](./data/sector_signals.json) | Signal counts by sector | Weekly |

---

## 🔥 This Week's Top Trends

<!-- AUTO-UPDATED -->
| Rank | Topic | Signals | Change |
|------|-------|---------|--------|
| 1 | AI | 2,450 | 📈 +12% |
| 2 | SaaS | 1,890 | 📈 +8% |
| 3 | DevTools | 1,245 | 📈 +15% |
| 4 | Cloud | 1,102 | ➡️ 0% |
| 5 | Security | 987 | 📈 +5% |

*See full data in [trending_topics.json](./data/trending_topics.json)*

---

## 📊 Data Schema

### trending_topics.json
```json
{
  "updated": "2026-01-09",
  "topics": [
    {
      "name": "AI",
      "count": 2450,
      "change_pct": 12,
      "sources": ["hn", "github", "reddit", "producthunt"]
    }
  ]
}
```

### hot_products.json
```json
{
  "updated": "2026-01-09",
  "products": [
    {
      "name": "Product Name",
      "url": "https://...",
      "source": "github_trending",
      "score": 85
    }
  ]
}
```

---

## 🔄 Update Schedule

Data is refreshed **every Sunday at 00:00 UTC**.

---

## 📡 Data Source

All data collected by [ASOF](https://asof.app) from:

- **Hacker News** - Top stories & discussions
- **GitHub** - Trending repositories
- **Reddit** - r/startups, r/SaaS, r/sideproject, r/Entrepreneur
- **Product Hunt** - New launches

[Explore Real-Time Data →](https://asof.app/live)

---

## 🛠️ Use Cases

- **Researchers** - Track tech trend evolution
- **Founders** - Validate market timing
- **Content Creators** - Find trending topics
- **Investors** - Early signal detection

---

## 📜 License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/) - Public Domain. Use freely.

---

## 🔗 Related

- [ASOF Live Dashboard](https://asof.app/live) - Real-time trends
- [ASOF Intelligence](https://asof.app/intel) - AI analysis
- [HN Best Posting Times](https://github.com/relikonapp/hn-best-posting-times) - Launch timing data
- [Awesome Tech Trend Resources](https://github.com/relikonapp/awesome-tech-trend-resources) - Curated tools

---

<p align="center">
  <sub>Data by <a href="https://asof.app">ASOF</a> - Real-time tech trend intelligence</sub>
</p>
