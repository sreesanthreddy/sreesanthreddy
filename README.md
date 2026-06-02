# Sreesanth Reddy Samala — Portfolio

Editorial AI-architect portfolio. Warm-paper theme, oxblood accents, scrolling logos, robotic mascot, AI-duality section.

## ⚠ Step 1 — drop your photos in `assets/`

The site references seven local images. **Save each photo you sent in chat to `assets/` with the exact filename below.** The site will pick them up automatically; until then, each slot shows a "// drop X.jpg into /assets" placeholder.

| Filename                | What it should be                                              | Where it appears                              |
|-------------------------|----------------------------------------------------------------|-----------------------------------------------|
| `assets/me-portrait.jpg`| Close-up headshot (you in black blazer, smiling at camera)     | **Hero polaroid** + About small photo         |
| `assets/me-office.jpg`  | Standing in office, hands in pockets, full body                | **About** — main portrait card                |
| `assets/me-desk.jpg`    | At desk with laptop, hands folded                              | About small photo                             |
| `assets/ai-chibi.jpg`   | Cute white chibi-style robot                                   | **Nav** — AI agent indicator badge            |
| `assets/ai-panther.jpg` | Black robotic panther / cheetah                                | **"Real-time platforms"** illustration        |
| `assets/ai-handshake.jpg`| You touching fingers with the white humanoid robot            | **"AI & GenAI"** illustration                 |
| `assets/ai-duality.jpg` | Side-by-side composite of you + AI robot                       | **AI Duality** full-bleed background section  |

> Recommended: JPG, ≤ 1600px wide, ≤ 400 KB each. The CSS already crops/positions them.

## Step 2 — open it

Just open `index.html` in Chrome/Edge/Safari/Firefox. Audio starts after first click (browser autoplay policy).

## Step 3 — deploy to GitHub

**🚨 Security:** revoke the leaked PAT at https://github.com/settings/tokens first. Then create a fresh fine-grained token with:
- **Repository access:** All repositories (or pick one)
- **Permissions → Administration:** Read & Write (only if creating a new repo)
- **Permissions → Contents:** Read & Write
- **Permissions → Pages:** Read & Write

### Option A — push from your machine (recommended)

```bash
cd "C:\Users\srees\Favorites\Portfolio"
git init
git add .
git commit -m "feat: portfolio v6 — editorial + AI duality"
git branch -M main
git remote add origin https://github.com/sreesanthreddy/portfolio.git
git push -u origin main
# (use your fresh PAT when git prompts for password)
```

Then enable Pages: `github.com/sreesanthreddy/portfolio` → Settings → Pages → Source: `main / (root)` → Save. Live at `https://sreesanthreddy.github.io/portfolio/` in about a minute.

### Option B — drag-and-drop on Netlify

1. https://app.netlify.com/drop
2. Drag the entire `Portfolio` folder.
3. Rename the auto-generated subdomain.

### Option C — Vercel CLI

```bash
npm i -g vercel
cd "C:\Users\srees\Favorites\Portfolio"
vercel
```

## What's on the site

- **Hero** — kinetic typography (Bricolage Grotesque + Fraunces italic), tilted polaroid photo, three-column footer note
- **About** — bio + portrait card + photo grid + facts
- **AI Duality** — full-bleed cinematic section with your composite photo + manifesto
- **Approach** — six principles (governed by default, AI where it earns its keep, cloud AI native, …)
- **What I do** — four paragraph rows (AI & GenAI · Real-time platforms · Cost & token budgeting · MCP servers & RAG), each with a *// current example* callout
- **Tools** — two infinite-scrolling marquees of inline-SVG brand marks (Anthropic, Claude, Snowflake, AWS, OpenAI, LangChain, Databricks, Pulumi, Python, GitHub, Kafka, Azure, GCP, MCP, RAG, Cursor, SOC2/CJIS, Flink, K8s, Docker, PySpark, MySQL/Oracle, Next.js, Vercel)
- **Projects** — six real client engagements with image thumbs
- **Contact** — letterpress-style links

Plus: synthesized-audio interactions (Web Audio API), custom cursor, scroll reveals, running robotic mascot at the bottom with typed spe