# Ziwei App — Tử Vi Full-Stack Skill

## Mô tả
App React full-stack Tử Vi Đẩu Số với AI giải mệnh, hợp bàn, K-line vận mệnh 100 năm. Dùng iztro engine bên trong.

## Trigger Keywords
`ziwei app`, `tử vi app`, `chạy ziwei`, `giao diện tử vi`, `hợp bàn`, `so bàn tử vi`, `k-line vận mệnh`, `命盘`, `合盘`, `人生K线`

## Cách dùng

### Dev server
```bash
cd /root/.openclaw/workspace/skills/ziwei/app
npm run dev
```

### Build production
```bash
cd /root/.openclaw/workspace/skills/ziwei/app
npm run build
```

## Tính năng
- **Lập lá số** — Input ngày sinh → 12 cung đầy đủ
- **AI Giải mệnh** — Multi-model (Kimi/Gemini/Claude/DeepSeek)
- **Hợp bàn** — So sánh 2 lá số, tứ hóa phi tinh, tương hợp
- **K-line 100 năm** — Biểu đồ vận mệnh trực quan
- **Chia sẻ** — Export card hình ảnh

## Docs
Tài liệu chuyên sâu trong `docs/`:
- `01-排盘算法` — Thuật toán lập bàn
- `02-星曜体系` — Hệ thống sao
- `03-宫位系统` — Hệ thống cung
- `04-四化飞星` — Tứ hóa phi tinh
- `05-格局判断` — Phán đoán cách cục
- `06-运限系统` — Hệ thống vận hạn

## Tech Stack
React 18 + TypeScript + Vite + Tailwind CSS + Recharts + iztro

## Source
- GitHub: https://github.com/ruijayfeng/ziwei
