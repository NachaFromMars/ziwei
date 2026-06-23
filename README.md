# Ziwei — Tử Vi Đẩu Số Full-Stack App

> Chinese Astrology (紫微斗數) web app with AI interpretation, chart matching, and 100-year destiny K-line visualization.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)
[![Tech Stack](https://img.shields.io/badge/Stack-React%2018%20%2B%20TypeScript%20%2B%20Vite-blue)](/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## Overview

**Ziwei** is a full-stack Tử Vi Đẩu Số (Purple Star Astrology) application that combines the `iztro` calculation engine with AI-powered destiny interpretation. Input a birth date and get a complete 12-palace chart, detailed star system analysis, and a century-spanning fortune K-line.

## Features

| Feature | Description |
|---|---|
| 🌟 Chart Generation | Full 12-palace chart from birth date (date, time, gender) |
| 🤖 AI Interpretation | Multi-model analysis: Kimi, Gemini, Claude, DeepSeek |
| ⚖️ Chart Matching | Compare two charts — tứ hóa phi tinh compatibility |
| 📈 K-Line (100 Years) | Visual fortune curve across a lifetime |
| 📤 Share / Export | Export chart as shareable image card |

## Tech Stack

- **Frontend:** React 18, TypeScript, Vite, Tailwind CSS, Recharts
- **Astrology Engine:** [iztro](https://github.com/SylarLong/iztro) — Purple Star calculation core
- **AI:** Multi-provider (configurable via env)

## Quick Start

```bash
# Dev server
cd app
npm install
npm run dev

# Production build
npm run build
```

## Documentation

Deep-dive docs in `docs/`:

| Folder | Content |
|---|---|
| `01-排盘算法` | Chart calculation algorithm |
| `02-星曜体系` | Star system |
| `03-宫位系统` | Palace system (12 palaces) |
| `04-四化飞星` | Tứ hóa phi tinh (Four Transformations) |
| `05-格局判断` | Pattern / configuration judgment |
| `06-运限系统` | Luck period / fortune cycle system |

## Trigger Keywords (OpenClaw)

`ziwei app`, `tử vi app`, `chạy ziwei`, `giao diện tử vi`, `hợp bàn`, `so bàn tử vi`, `k-line vận mệnh`, `命盘`, `合盘`, `人生K线`

## Related Skills

- [iztro](https://github.com/NachaFromMars/iztro) — Core calculation engine (standalone)
- [destiny-engine](https://github.com/NachaFromMars/destiny-engine) — Bát Tự / Bazi engine

---

Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
