# Claude Skills Backup

A public backup of my local **Claude Code skills** folder. This repo mirrors the skills I use in my Clawdbot/Claude Code workflow, including built‑in, custom, and experimental skill packs.

> **Note:** This is a **snapshot** of my local skills directory. It’s meant for backup, sharing, and reference.

---

## What’s Inside

This repository contains:

- **Skill packs** (each folder is a skill)
- **Skill metadata** (`SKILL.md`, rules, references, scripts, examples)
- **Templates & utilities** used by specific skills
- **Supporting assets** (docs, examples, diagrams, etc.)

Each skill is a self‑contained folder. The key file is usually:

```
<skill-name>/SKILL.md
```

---

## How to Use

If you’re using **Claude Code / Clawdbot**:

1. Clone the repo:
   ```bash
   git clone https://github.com/404kidwiz/claude-skills-backup.git
   ```
2. Copy skills into your local skills directory (or symlink):
   ```bash
   cp -R claude-skills-backup/* /path/to/your/skills/
   ```
3. Restart your agent (if required).

If you just want to browse, open any skill folder and read its `SKILL.md`.

---

## Folder Structure (Example)

```
skills/
├── api-design-principles/
│   ├── SKILL.md
│   ├── resources/
│   └── references/
├── git-pushing/
│   ├── SKILL.md
│   └── scripts/
├── ...
```

---

## Notes & Conventions

- **Each folder = one skill**
- `SKILL.md` is the entry point
- Some skills include scripts, templates, or example data
- A few skill packs include heavy assets or reference docs

---

## License

Unless a subfolder specifies otherwise, this repo is shared **as-is** for personal use and reference.

---

## Contact

If you’re using these skills or want to collaborate:
- GitHub: [@404kidwiz](https://github.com/404kidwiz)
