# 🌾 HarvestIQ — Dividend Portfolio Intelligence

**Free, private, open-source dividend portfolio analyzer.**  
No account. No server. No data leaves your browser.

🔗 **Live app:** [harvestiq.daniellanzas.com](https://harvestiq.daniellanzas.com) *(or your GitHub Pages URL)*

---

## What it does

HarvestIQ analyzes your dividend portfolio across 7 views:

| View | What you get |
|------|-------------|
| ✦ **Opportunities** | Ranked buying list: yield × growth × quality |
| ⚖️ **Reinforce / Build** | Which positions to add to vs. which to start |
| ◈ **By Sector** | Sector concentration and diversification map |
| 📦 **ETFs** | Reference ETF universe (global + dividend) |
| 📅 **Monthly Dividends** | Projected monthly income calendar |
| 🔬 **Audit** | Yield traps, unsustainable payouts, quality alerts |
| 🏆 **DGI Score** | Dividend quality score: streak × growth × payout |

---

## How to use it

1. **Open the app** — explore the 4 example positions (MSFT, JNJ, KO, O)
2. **Upload your CSV** — exported from DivTracker or any platform with columns `Ticker · Quantity · Cost Per Share · Currency`
3. **Upload your Excel** — exported from Seeking Alpha or DivTracker (provides yield, growth, payout, streak)
4. **Get your analysis** — all 7 views update instantly with your data

> Your files are processed entirely in your browser. HarvestIQ has no backend.

---

## Privacy

- ✅ No server, no database, no telemetry
- ✅ Your files never leave your device
- ✅ Session-only by default — closing the tab clears everything
- ✅ Optional "Save in browser" toggle to persist across sessions

---

## Deploy your own instance

This is a single HTML file. To deploy on GitHub Pages:

```bash
# 1. Fork or clone this repo
git clone https://github.com/YOUR_USERNAME/HarvestIQ

# 2. The index.html is the entire app — no build step needed

# 3. Enable GitHub Pages
# Settings → Pages → Source: main → / (root)

# 4. Your app is live at:
# https://YOUR_USERNAME.github.io/HarvestIQ/
```

For a custom domain, add a `CNAME` file with your domain name and configure your DNS.

---

## Support the project

If you find HarvestIQ useful, consider [buying me a coffee ☕](https://ko-fi.com/daniel_lanzas)

Also check out [Axios-IQ](https://dlanzas-cyber.github.io/AxiosIQ_Stock-analyzer/) — individual stock analyzer from the same creator.

---

## License

MIT — free to use, modify and redistribute.
