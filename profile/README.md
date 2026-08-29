<h1 align="center">Dansday</h1>

<p align="center">
  Open-source tools you can run yourself.<br>
  A portfolio site, a Discord bot, and the panels that drive them.
</p>

<p align="center">
  <a href="https://dansday.com"><img src="https://img.shields.io/badge/dansday.com-E60000?style=for-the-badge" alt="Website"></a>
  <img src="https://img.shields.io/badge/License-MIT-555555?style=for-the-badge" alt="MIT">
  <img src="https://img.shields.io/badge/Self--hosted-0D1117?style=for-the-badge&logo=docker&logoColor=white" alt="Self-hosted">
</p>

---

Everything here is MIT licensed and built to be self-hosted. No accounts, no hosted tier, no telemetry phoning home. Clone it, set your environment variables, run `make up`.

---

### 🖥️ [dansday-main](https://github.com/dansday-com/dansday-main)

<p>
  <img src="https://img.shields.io/github/languages/top/dansday-com/dansday-main?style=flat-square&labelColor=0D1117&color=777BB4" alt="Top language">
  <img src="https://img.shields.io/github/last-commit/dansday-com/dansday-main?style=flat-square&labelColor=0D1117&color=E60000" alt="Last commit">
  <img src="https://img.shields.io/github/license/dansday-com/dansday-main?style=flat-square&labelColor=0D1117&color=555555" alt="License">
</p>

A personal site that looks like a terminal, plus the Laravel panel that runs it.

- Articles, projects and an about page, each with categories and per-item visibility
- A terminal page that answers questions from your own content using hybrid retrieval — MySQL full-text fused with embedding similarity
- An **MCP server** so an AI assistant can write, edit and publish your content directly
- LinkedIn posting with images, document carousels, video and scheduling
- Live GitHub statistics with a contribution heatmap
- Admin panel translated into 18 locales

**SvelteKit · Laravel 12 · MySQL · Redis · Docker**

---

### 🤖 [dansday-discord-bot](https://github.com/dansday-com/dansday-discord-bot)

<p>
  <img src="https://img.shields.io/github/languages/top/dansday-com/dansday-discord-bot?style=flat-square&labelColor=0D1117&color=3178C6" alt="Top language">
  <img src="https://img.shields.io/github/last-commit/dansday-com/dansday-discord-bot?style=flat-square&labelColor=0D1117&color=E60000" alt="Last commit">
  <img src="https://img.shields.io/github/license/dansday-com/dansday-discord-bot?style=flat-square&labelColor=0D1117&color=555555" alt="License">
</p>

A Discord bot managed from a web panel instead of slash commands.

- Leveling, moderation, welcomer, giveaways and an embed builder
- An XP economy with a shop, a live crypto market and minigames
- Daily and weekly tasks that generate per member, with streaks and check-in
- **AI chat and voice** on any OpenAI-compatible endpoint, with wake-word detection running on-device
- Public server pages — statistics, leaderboards and member accounts, no login required
- Discord Quest notifications and Roblox catalog alerts

**SvelteKit · discord.js · MySQL · Redis · Docker**

---

### Getting started

Both projects ship with Docker Compose and a `Makefile`:

```bash
git clone https://github.com/dansday-com/<project>.git
cd <project>
cp .env.example .env
make up
```

Each repository has its own README covering configuration, and a `CONTRIBUTING.md` if you want to send a patch. Security issues go to **security@dansday.com**, never a public issue.

---

<p align="center"><sub>Built and maintained by <a href="https://github.com/Dansday">Akbar Yudhanto</a></sub></p>
