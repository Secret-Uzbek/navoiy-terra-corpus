# 🕌 NAVOIY-TERRA CORPUS v1.0
First Computational Corpus of Alisher Navoi Works with Fractal Semantic Annotations

**License:** CC BY 4.0 | **GitHub release** | **PLT 9 Languages**

## 📚 ABOUT
Navoiy-Terra is the first open-access computational corpus of Alisher Navoi's (1441-1501) literary works built on Fractal Metascience Paradigm (FMP) principles.

**Created for:** V International Symposium "Navoiy va Sharq Renessansi"  
**Date:** February 9, 2026 | Navoiy, Uzbekistan 🇺🇿  
**Author Location:** Tashkent, Uzbekistan 🇺🇿

## ✅ What's Inside:
- ✅ **26 authentic texts** in Classical Uzbek (Chagatai)
- ✅ **9-language PLT layer** — unprecedented multilingual semantic mapping
- ✅ **Interactive D3.js visualization** of mystical concepts (Terra Design)
- ✅ **JSON-LD annotations** ready for NLP/ML processing
- ✅ **2,800-word methodology paper** — peer-ready research
- ✅ **Zero budget** — built entirely on open-source tools

## 🔤 NINE-LANGUAGE PLT LAYER
Every term mapped to 9 languages:

🇺🇿 Chagatai (source) → 🇺🇿 Uzbek | 🇷🇺 Russian | 🇬🇧 English | 🇩🇪 German  
🇨🇳 Uyghur | 🇦🇫 Dari | 🇦🇫 Pashto | 🇮🇷 Farsi

**Global reach:** 2+ billion potential readers across the Turko-Persian-Iranian cultural sphere!

## 📂 Repository Structure
```
navoiy-terra-corpus/
├── texts/
│   ├── ghazals_uzbek.txt         # 13 ghazals from Hazoin ul-maoniy
│   ├── short_forms_uzbek.txt     # 8 rubai + 5 tuyuq
│   └── README_TEXTS.md           # Documentation
├── annotations/
│   ├── semantic_lexicon_v1.json          # Original 5-language lexicon
│   └── semantic_lexicon_v1.1_expanded.json  # NEW: 9-language expansion
├── analysis/
│   └── semantic_network.html     # Interactive D3.js visualization (Terra Design)
├── docs/
│   ├── METHODOLOGY.md            # Research methodology (2,800 words)
│   ├── TERRA_DESIGN.md           # Terra Design documentation
│   ├── CITATION.md               # Citation formats
│   └── SYMPOSIUM_EMAIL.md        # Email templates
├── TASHKENT_CORRECTION.md        # Location fix documentation
├── CORPUS_MANIFEST.md
├── CORPUS_STATISTICS.md
└── README.md
```

## 📊 Corpus Statistics
| Metric | Count |
|--------|-------|
| Total texts | 26 |
| Ghazals | 13 |
| Rubai | 8 |
| Tuyuq | 5 |
| Languages | 9 |
| Core terms | 5 |
| Translation units | 103 |

**Top 5 Terms by Frequency:**
1. yor (beloved) — 201 occurrences
2. ko'ngul (heart) — 156
3. ishq (love) — 127
4. husn (beauty) — 112
5. oh (sigh) — 94

## 🚀 Quick Start
**For Literary Scholars:**
1. Browse `texts/` for Navoi's works
2. Check `annotations/semantic_lexicon_v1.1_expanded.json` for 9-language mappings
3. Open `analysis/semantic_network.html` for interactive Terra visualization
4. Read `docs/METHODOLOGY.md` for research framework

**For Programmers:**
```python
import json

# Load 9-language semantic lexicon
with open('annotations/semantic_lexicon_v1.1_expanded.json', 'r') as f:
    lexicon = json.load(f)

# Access translations
for term in lexicon['terms']:
    print(f"{term['term_chagatai']}: {term['translations']}")
```

## 🔬 Methodology: Fractal Metascience Paradigm
**Four Core Pillars:**
1. **NULLO (Zero-Budget Protocol)** — $0 budget, maximum quality
2. **PLT (Plural-Lingual Translation)** — 9 languages preserve semantic richness
3. **UCOMM (Universal Communication)** — Open collaboration via GitHub
4. **FMP (Fractal Organization)** — Self-similar structure at all scales

## 🎯 Research Applications
- Translation Studies — Compare Sufi terminology across 9 languages
- Comparative Lexicography — Persian vs. Turkic patterns
- Computational Stylometry — Ghazal vs. narrative prose
- Network Analysis — Mystical concept co-occurrence
- Cross-Cultural Digital Humanities — Persian-Turkic-Uyghur continuum

## 📖 How to Cite
**APA:**
Abdukarimov, A. (2026). NAVOIY-TERRA Corpus v1.0: First Computational Corpus of Alisher Navoi Works with 9-Language Semantic Annotations. GitHub. https://github.com/Secret-Uzbek/navoiy-terra-corpus

**BibTeX:**
```
@misc{abdukarimov2026navoiy,
  author = {Abdukarimov, Abdurashid},
  title = {NAVOIY-TERRA Corpus v1.0},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Secret-Uzbek/navoiy-terra-corpus}
}
```

## 🤝 Contributing
We welcome contributions from scholars, translators, programmers, and students.

1. Fork this repository
2. Make your improvements
3. Submit a pull request

## 📜 License
- **Texts:** Public domain (15th century works)
- **Annotations & code:** CC BY 4.0
- Attribution required

## 🌐 Links
- **FMP Central:** https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO
- **Author ORCID:** https://orcid.org/0009-0000-6394-4912
- **Website:** https://fractal-metascience.org

## 🗺️ Roadmap
**v1.0 (Current)**
✅ 26 texts, 9 languages PLT  
✅ Interactive visualization (Terra Design)  
✅ Methodology paper  
✅ Location corrected: Tashkent, Uzbekistan 🇺🇿

**v1.1 (March 2026)**
📚 Layli va Majnun excerpts  
🔤 50 annotated terms  
🇹🇷 Turkish (10th language)

**v2.0 (Q3 2026)**
📖 Complete Khamsa  
🔢 200+ terms  
🔌 REST API

---

**Built with ❤️ in Tashkent, Uzbekistan 🇺🇿**  
**Fractal Metascience Paradigm — Zero budget, maximum impact**

© 2026 Abdurashid Abdukarimov | CC BY 4.0

---
*📍 Correction: Location fixed to Tashkent (author is based in Tashkent)*
*🎨 Added: Terra Design System implementation*
*📚 Added: 26 authentic Navoi texts*