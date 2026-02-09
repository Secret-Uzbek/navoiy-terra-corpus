# ð NAVOIY-TERRA CORPUS v1.0

**First Computational Corpus of Alisher Navoi Works with Fractal Semantic Annotations**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub release](https://img.shields.io/github/v/release/Secret-Uzbek/navoiy-terra-corpus)](https://github.com/Secret-Uzbek/navoiy-terra-corpus/releases)
[![PLT Languages](https://img.shields.io/badge/PLT-9%20languages-2E8B57)](https://github.com/Secret-Uzbek/navoiy-terra-corpus)

---

## ð ABOUT

**Navoiy-Terra** is the first open-access computational corpus of **Alisher Navoi's** (1441-1501) literary works built on **Fractal Metascience Paradigm (FMP)** principles.

**Created for:** V International Symposium "Navoiy va Sharq Renessansi"  
**Date:** February 9, 2026 | Navoiy, Uzbekistan ðºð¿

### What's Inside:
- â **26 authentic texts** in Classical Uzbek (Chagatai)
- â **9-language PLT layer** â unprecedented multilingual semantic mapping
- â **Interactive D3.js visualization** of mystical concepts
- â **JSON-LD annotations** ready for NLP/ML processing
- â **2,800-word methodology paper** â peer-ready research
- â **Zero budget** â built entirely on open-source tools

---

## ð¤ NINE-LANGUAGE PLT LAYER

**Unique feature:** Every term mapped to **9 languages**:

ðºð¿ **Chagatai** (source) â ðºð¿ Uzbek | ð·ðº Russian | ð¬ð§ English | ð©ðª German  
ð¨ð³ **Uyghur** | ð¦ð« Dari | ð¦ð« Pashto | ð®ð· Farsi

**Global reach:** 2+ billion potential readers across the Turko-Persian-Iranian cultural sphere!

Example PLT mapping for **"ishq"** (divine love):
```json
{
  "chagatai": "Ø¹Ø´Ù",
  "uzbek": ["sevgi", "muhabbat"],
  "russian": ["Ð»ÑÐ±Ð¾Ð²Ñ", "ÑÑÑÐ°ÑÑÑ"],
  "english": ["love", "passionate devotion"],
  "german": ["Liebe", "Leidenschaft"],
  "uyghur": ["Ø¦ÛØ´Ù", "ÙÛÚ¾ÛØ¨Ø¨ÛØª"],
  "dari": ["Ø¹Ø´Ù", "ÙØ­Ø¨Øª"],
  "pashto": ["Ø¹Ø´Ù", "ÙÛÙÙ"],
  "farsi": ["Ø¹Ø´Ù", "ÙØ­Ø¨Øª"]
}
```

---

## ð¦ REPOSITORY STRUCTURE

```
navoiy-terra-corpus/
âââ texts/
â   âââ ghazals_uzbek.txt         # 13 ghazals from Hazoin ul-maoniy
â   âââ short_forms_uzbek.txt     # 8 rubai + 5 tuyuq
âââ annotations/
â   âââ semantic_lexicon_v1.json          # Original 5-language lexicon
â   âââ semantic_lexicon_v1.1_expanded.json  # NEW: 9-language expansion
âââ analysis/
â   âââ semantic_network.html     # Interactive D3.js visualization
âââ docs/
â   âââ METHODOLOGY.md            # Research methodology (2,800 words)
â   âââ CITATION.md               # Citation formats
â   âââ SYMPOSIUM_EMAIL.md        # Email templates
âââ CORPUS_MANIFEST.md
âââ CORPUS_STATISTICS.md
âââ README.md
```

---

## ð CORPUS STATISTICS

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
1. **yor** (beloved) â 201 occurrences
2. **ko'ngul** (heart) â 156
3. **ishq** (love) â 127
4. **husn** (beauty) â 112
5. **oh** (sigh) â 94

---

## ð QUICK START

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

## ð¬ METHODOLOGY: FRACTAL METASCIENCE PARADIGM

### Four Core Pillars:

**1. NULLO (Zero-Budget Protocol)**
- Budget: **$0** â no institutional funding
- Tools: GitHub (free), Zenodo (free), open-source Python

**2. PLT (Plural-Lingual Translation)**
- **9 languages** instead of single "correct" translation
- Multiple equivalents per term preserve semantic richness

**3. UCOMM (Universal Communication)**
- Open collaboration via GitHub issues/PRs
- Iterative refinement through versioning

**4. FMP (Fractal Organization)**
- Self-similar structure at all scales (micro â meso â macro)

**Full methodology:** [docs/METHODOLOGY.md](docs/METHODOLOGY.md)

---

## ð¯ RESEARCH APPLICATIONS

1. **Translation Studies** â Compare Sufi terminology across 9 languages
2. **Comparative Lexicography** â Persian vs. Turkic patterns
3. **Computational Stylometry** â Ghazal vs. narrative prose
4. **Network Analysis** â Mystical concept co-occurrence
5. **Cross-Cultural Digital Humanities** â Persian-Turkic-Uyghur continuum

---

## ð HOW TO CITE

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

## ð¤ CONTRIBUTING

We welcome contributions from scholars, translators, programmers, and students.

1. Fork this repository
2. Make your improvements
3. Submit a pull request

---

## ð LICENSE

**Texts:** Public domain (15th century works)  
**Annotations & code:** CC BY 4.0  
**Attribution required**

---

## ð LINKS

- **FMP Central:** https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO
- **Author ORCID:** https://orcid.org/0009-0000-6394-4912
- **Website:** https://fractal-metascience.org

---

## ðºï¸ ROADMAP

### v1.0 (Current)
- â 26 texts, 9 languages PLT
- â Interactive visualization
- â Methodology paper

### v1.1 (March 2026)
- ð Layli va Majnun excerpts
- ð¤ 50 annotated terms
- ð¹ð· Turkish (10th language)

### v2.0 (Q3 2026)
- ð Complete Khamsa
- ð¢ 200+ terms
- ð REST API

---

**Built with â¤ï¸ in Tashkent, Uzbekistan ðºð¿**  
*Fractal Metascience Paradigm â Zero budget, maximum impact*

Â© 2026 Abdurashid Abdukarimov | CC BY 4.0

📍 **Исправлено:** Локация изменена на Ташкент (автор находится в Ташкенте)