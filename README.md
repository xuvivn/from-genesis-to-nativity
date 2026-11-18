# From Genesis to Nativity · Từ Sáng Thế Đến Giáng Sinh · 从创世到圣诞

**Multilingual 5-Level Storytelling Practice Corpus (Ages 9–10)**  
Inspired by the classic storytelling cycle of **Jakob Streit** (*And There Was Light*, *Journey to the Promised Land*, *We Will Build a Temple*, *Königskind und Hirtenkind*, *Sankt Nikolaus*), structured into **5 Books — 180 Chapters — 28 Hand-drawn Memory Illustrations — 25 Ancient Source Texts**.

---

## Language Editions · Các Bản Ngôn Ngữ · 多语言版本

| Language | Code | Title | Entry Guide | Machine-Readable Index |
| :--- | :--- | :--- | :--- | :--- |
| **Tiếng Việt** | `vi` | Từ Sáng Thế Đến Giáng Sinh | [locales/vi/README.md](locales/vi/README.md) | [locales/vi/story-index.json](locales/vi/story-index.json) |
| **English** | `en` | From Genesis to Nativity | [locales/en/README.md](locales/en/README.md) | [locales/en/story-index.json](locales/en/story-index.json) |
| **简体中文** | `zh` | 从创世到圣诞 | [locales/zh/README.md](locales/zh/README.md) | [locales/zh/story-index.json](locales/zh/story-index.json) |

- Root multi-language manifest: [languages.json](languages.json)
- Shared illustration assets (Level 4): [assets/images/](assets/images/)

---

## Unified Repository Architecture · Kiến Trúc Kho Dữ Liệu · 统一目录架构

Every language under `locales/{lang}/` mirrors the exact same 5-level file structure (`45 Markdown files + 1 story-index.json` per language):

```text
.
├── languages.json                     # Multi-language manifest (vi, en, zh)
├── README.md                          # Multilingual hub
├── assets/
│   └── images/                        # Shared 28 hand-drawn Level 4 illustrations
└── locales/
    ├── vi/                            # Tiếng Việt
    ├── en/                            # English
    └── zh/                            # 简体中文
        ├── README.md
        ├── story-index.json
        ├── level-0-context/           # Epic overview, 5 book guides, 25 ancient texts
        ├── level-1-full-text/         # Full read-aloud stories (180 chapters + voice notes)
        ├── level-2-detailed-outline/  # Detailed story outlines (180 chapters)
        ├── level-3-summary-outline/   # Core 180-chapter summary backbone
        └── level-4-visual-prompts/    # 28-scene visual gallery & art prompts
```

---

## 5-Level Storytelling Progression · Kiến Trúc 5 Cấp Độ · 五阶叙事练习体系

1. **Level 0 — Context & Epic Soul (`level-0-context/`):** Cultural atmosphere, storytelling rhythm for ages 9–10, pronunciation guides for ancient names, and 25 supplementary ancient texts (`ancient-texts/`).
2. **Level 1 — Full Read-Aloud Text (`level-1-full-text/`):** Complete narrative prose across all 5 Books (180 Chapters), each ending with practical oral storytelling notes (*Lưu ý giọng kể* / *Storytelling Notes* / *讲演提示*).
3. **Level 2 — Detailed Outline (`level-2-detailed-outline/`):** Characters, central symbols, plot beats, and storytelling highlights for all 180 Chapters so storytellers can practice without reading word-for-word.
4. **Level 3 — Summary Outline (`level-3-summary-outline/`):** Single condensed backbone file across all 180 Chapters for quick continuity checks.
5. **Level 4 — Pure Visual Prompts (`level-4-visual-prompts/`):** 28 hand-drawn traditional-media illustrations (`assets/images/`) mapped to chapter clusters for free-flowing oral retelling.
