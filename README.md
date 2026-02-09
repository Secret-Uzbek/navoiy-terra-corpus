# 🕌 NAVOIY-TERRA CORPUS v1.0

**First Computational Corpus of Alisher Navoi Works with Fractal Semantic Annotations**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub release](https://img.shields.io/github/v/release/Secret-Uzbek/navoiy-terra-corpus)](https://github.com/Secret-Uzbek/navoiy-terra-corpus/releases)
[![PLT Languages](https://img.shields.io/badge/PLT-9%20languages-2E8B57)](https://github.com/Secret-Uzbek/navoiy-terra-corpus)

---

## 📚 ABOUT

**Navoiy-Terra** is the first open-access computational corpus of **Alisher Navoi's** (1441-1501) literary works built on **Fractal Metascience Paradigm (FMP)** principles.

**Created for:** V International Symposium "Navoiy va Sharq Renessansi"  
**Date:** February 9, 2026 | Navoiy, Uzbekistan 🇺🇿

### What's Inside:
- ✅ **26 authentic texts** in Classical Uzbek (Chagatai)
- ✅ **9-language PLT layer** — unprecedented multilingual semantic mapping
- ✅ **Interactive D3.js visualization** of mystical concepts
- ✅ **JSON-LD annotations** ready for NLP/ML processing
- ✅ **2,800-word methodology paper** — peer-ready research
- ✅ **Zero budget** — built entirely on open-source tools

---

## 🔤 NINE-LANGUAGE PLT LAYER

**Unique feature:** Every term mapped to **9 languages**:

🇺🇿 **Chagatai** (source) → 🇺🇿 Uzbek | 🇷🇺 Russian | 🇬🇧 English | 🇩🇪 German  
🇨🇳 **Uyghur** | 🇦🇫 Dari | 🇦🇫 Pashto | 🇮🇷 Farsi

**Global reach:** 2+ billion potential readers across the Turko-Persian-Iranian cultural sphere!

Example PLT mapping for **"ishq"** (divine love):
```json
{
  "chagatai": "عشق",
  "uzbek": ["sevgi", "muhabbat"],
  "russian": ["любовь", "страсть"],
  "english": ["love", "passionate devotion"],
  "german": ["Liebe", "Leidenschaft"],
  "uyghur": ["ئەشق", "مۇھەببەت"],
  "dari": ["عشق", "محبت"],
  "pashto": ["عشق", "مینه"],
  "farsi": ["عشق", "محبت"]
}
```

---

## 📦 REPOSITORY STRUCTURE

```
navoiy-terra-corpus/
├── texts/
│   ├── ghazals_uzbek.txt         # 13 ghazals from Hazoin ul-maoniy
│   └── short_forms_uzbek.txt     # 8 rubai + 5 tuyuq
├── annotations/
│   ├── semantic_lexicon_v1.json          # Original 5-language lexicon
│   └── semantic_lexicon_v1.1_expanded.json  # NEW: 9-language expansion
├── analysis/
│   └── semantic_network.html     # Interactive D3.js visualization
├── docs/
│   ├── METHODOLOGY.md            # Research methodology (2,800 words)
│   ├── CITATION.md               # Citation formats
│   └── SYMPOSIUM_EMAIL.md        # Email templates
├── CORPUS_MANIFEST.md
├── CORPUS_STATISTICS.md
└── README.md
```

---

## 📊 CORPUS STATISTICS

| Metric | Count |
|--------|-------|
| **Total texts** | 26 |
| Ghazals | 13 |
| Rubai | 8 |
| Tuyuq | 5 |
| **Languages** | 9 |
| **Core terms** | 5 |
| **Translation units** | 103 |

### Top 5 Terms by Frequency:
1. **yor** (beloved) — 201 occurrences
2. **ko'ngul** (heart) — 156
3. **ishq** (love) — 127
4. **husn** (beauty) — 112
5. **oh** (sigh) — 94

---

## 🚀 QUICK START

### For Literary Scholars:
1. Browse **texts/** for Navoi's works
2. Check **annotations/semantic_lexicon_v1.1_expanded.json** for 9-language mappings
3. Open **analysis/semantic_network.html** for interactive visualization
4. Read **docs/METHODOLOGY.md** for research framework

### For Programmers:
```python
import json

# Load 9-language semantic lexicon
with open('annotations/semantic_lexicon_v1.1_expanded.json', 'r') as f:
    lexicon = json.load(f)

# Access translations
for term in lexicon['terms']:
    print(f"{term['term_chagatai']}: {term['translations']}")
```

---

## 🔬 METHODOLOGY: FRACTAL METASCIENCE PARADIGM

### Four Core Pillars:

**1. NULLO (Zero-Budget Protocol)**
- Budget: **$0** — no institutional funding
- Tools: GitHub (free), Zenodo (free), open-source Python

**2. PLT (Plural-Lingual Translation)**
- **9 languages** instead of single "correct" translation
- Multiple equivalents per term preserve semantic richness

**3. UCOMM (Universal Communication)**
- Open collaboration via GitHub issues/PRs
- Iterative refinement through versioning

**4. FMP (Fractal Organization)**
- Self-similar structure at all scales (micro → meso → macro)

**Full methodology:** [docs/METHODOLOGY.md](docs/METHODOLOGY.md)

---

## 🎯 RESEARCH APPLICATIONS

1. **Translation Studies** — Compare Sufi terminology across 9 languages
2. **Comparative Lexicography** — Persian vs. Turkic patterns
3. **Computational Stylometry** — Ghazal vs. narrative prose
4. **Network Analysis** — Mystical concept co-occurrence
5. **Cross-Cultural Digital Humanities** — Persian-Turkic-Uyghur continuum

---

## 📖 HOW TO CITE

### APA:
```
Abdukarimov, A. (2026). NAVOIY-TERRA Corpus v1.0: First Computational 
Corpus of Alisher Navoi Works with 9-Language Semantic Annotations. 
GitHub. https://github.com/Secret-Uzbek/navoiy-terra-corpus
```

### BibTeX:
```bibtex
@misc{abdukarimov2026navoiy,
  author = {Abdukarimov, Abdurashid},
  title = {NAVOIY-TERRA Corpus v1.0},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Secret-Uzbek/navoiy-terra-corpus}
}
```

---

## 🤝 CONTRIBUTING

We welcome contributions from scholars, translators, programmers, and students.

1. Fork this repository
2. Make your improvements
3. Submit a pull request

---

## 📜 LICENSE

**Texts:** Public domain (15th century works)  
**Annotations & code:** CC BY 4.0  
**Attribution required**

---

## 🌐 LINKS

- **FMP Central:** https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO
- **Author ORCID:** https://orcid.org/0009-0000-6394-4912
- **Website:** https://fractal-metascience.org

---

## 🗺️ ROADMAP

### v1.0 (Current)
- ✅ 26 texts, 9 languages PLT
- ✅ Interactive visualization
- ✅ Methodology paper

### v1.1 (March 2026)
- 📚 Layli va Majnun excerpts
- 🔤 50 annotated terms
- 🇹🇷 Turkish (10th language)

### v2.0 (Q3 2026)
- 📖 Complete Khamsa
- 🔢 200+ terms
- 🔌 REST API

---

**Built with ❤️ in Zarafshan, Uzbekistan 🇺🇿**  
*Fractal Metascience Paradigm — Zero budget, maximum impact*

© 2026 Abdurashid Abdukarimov | CC BY 4.0