<h1 align="center">Dansday</h1>

<p align="center">
  Open-source tools you can run yourself.<br>
  A Discord bot with a web panel, a terminal-style portfolio site, and the panels that drive them.
</p>

<p align="center">
  <a href="https://dansday.com"><img src="https://img.shields.io/badge/dansday.com-E60000?style=for-the-badge" alt="Website"></a>
  <a href="https://dansday.dev"><img src="https://img.shields.io/badge/Live%20demo-0D1117?style=for-the-badge" alt="Live demo"></a>
  <a href="https://discord.gg/7fEqEDSur3"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <img src="https://img.shields.io/badge/Self--hosted-0D1117?style=for-the-badge&logo=docker&logoColor=white" alt="Self-hosted">
</p>

---

Two projects, both open source and built to be self-hosted. No telemetry phoning home, no features held back behind a paid tier. Clone one, set your environment variables, run it.

Licenses differ per project — **dansday-main is MIT**, **dansday-discord-bot is AGPL-3.0**. Check the badge on each before you build on it.

---

### 🤖 [dansday-discord-bot](https://github.com/dansday-com/dansday-discord-bot)

<p>
  <img src="https://img.shields.io/github/languages/top/dansday-com/dansday-discord-bot?style=flat-square&labelColor=0D1117&color=3178C6" alt="Top language">
  <img src="https://img.shields.io/github/last-commit/dansday-com/dansday-discord-bot?style=flat-square&labelColor=0D1117&color=E60000" alt="Last commit">
  <img src="https://img.shields.io/github/license/dansday-com/dansday-discord-bot?style=flat-square&labelColor=0D1117&color=555555" alt="License">
</p>

**A Discord bot you configure in a browser — and an account for every member, not just admins.**

Most bots give the admin a dashboard. This one gives every member their own page: their XP, their bag, their streaks, their portfolio, their animated card.

- Leveling, moderation, welcomer, giveaways and an embed builder — every module a tab with live preview
- An XP economy with a shop, a live crypto-priced market and minigames. No real money
- 18 daily and 18 weekly tasks generated per member from their own last 7 days, with streaks and check-in
- **AI chat and Gemini Live voice** on any OpenAI-compatible endpoint, wake-word detection running on-device
- AI that reads your own server — live statistics, leaderboards, shop prices and XP formula
- Public server pages: statistics, leaderboards and member accounts, no login required
- Discord Quest notifications and Roblox catalog alerts

**SvelteKit · discord.js · TypeScript · MySQL · Redis · Docker**

[**Live demo →**](https://dansday.dev) · [**Docs →**](https://dansday.dev/docs) · [**Discord →**](https://discord.gg/7fEqEDSur3)

---

### 🖥️ [dansday-main](https://github.com/dansday-com/dansday-main)

<p>
  <img src="https://img.shields.io/github/languages/top/dansday-com/dansday-main?style=flat-square&labelColor=0D1117&color=777BB4" alt="Top language">
  <img src="https://img.shields.io/github/last-commit/dansday-com/dansday-main?style=flat-square&labelColor=0D1117&color=E60000" alt="Last commit">
  <img src="https://img.shields.io/github/license/dansday-com/dansday-main?style=flat-square&labelColor=0D1117&color=555555" alt="License">
</p>

**A personal site that looks like a terminal, plus the Laravel panel that runs it.**

- Articles, projects and an about page, each with categories and per-item visibility
- A terminal page that answers questions from your own content using hybrid retrieval — MySQL full-text fused with embedding similarity
- An **MCP server** so an AI assistant can write, edit and publish your content directly
- LinkedIn posting with images, document carousels, video and scheduling
- Live GitHub statistics with a contribution heatmap
- Admin panel translated into 18 locales

**SvelteKit · Laravel 12 · MySQL · Redis · Docker**

---

### Getting started

Both projects ship a `Dockerfile`, a `docker-compose.yaml` and a `Makefile`. The compose files build the application only — bring your own MySQL and Redis, point `.env` at them, then:

```bash
git clone https://github.com/dansday-com/<project>.git
cd <project>
cp .env.example .env   # database, session secret, mail
make up
```

Each repository has its own README covering configuration and a `CONTRIBUTING.md` if you want to send a patch.

Security issues go to the address in that repository's `SECURITY.md`, never a public issue — **security@dansday.com** for dansday-main, **security@dansday.dev** for the Discord bot.

---

<p align="center"><sub>Built and maintained by <a href="https://github.com/Dansday">Akbar Yudhanto</a> · Indonesia</sub></p>
