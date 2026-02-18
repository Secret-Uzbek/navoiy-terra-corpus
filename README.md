# 🕌 NAVOIY-TERRA CORPUS v1.1
**Expanded Edition: Complete Lisonut-tayr + Majolisun-nafois**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub release](https://img.shields.io/badge/release-v1.1-green.svg)](https://github.com/Secret-Uzbek/navoiy-terra-corpus/releases/tag/v1.1)
[![PLT](https://img.shields.io/badge/PLT-9%20Languages-orange.svg)](https://github.com/Secret-Uzbek/navoiy-terra-corpus)

---

## 📚 WHAT'S NEW IN v1.1

### ✨ Major Expansion
- **+3 Major Works**: Lisonut-tayr (nazm), Lisonut-tayr (nasr), Majolisun-nafois
- **+10 New Terms**: Simurgh, Hudhud, Seven Valleys, Vujud, Tajalli, etc.
- **29 Total Texts** (up from 26)
- **15 Annotated Terms** (up from 5)
- **9 Languages** maintained across all new content

### 🔥 Core Addition: LISONUT-TAYR Complete
**Lisonut-tayr** (Language of Birds) — Navoiy's masterwork adapting Attar's Persian classic

**Nazm (Poetry) Edition:**
- Complete poetic text in classical Chagatai
- 7 valleys spiritual journey (Talab → Ishq → Ma'rifat → Istig'no → Tawhid → Hayrat → Faqr-u-Fano)
- Simurgh symbolism fully annotated
- Bird metaphor network mapped

**Nasr (Prose Commentary):**
- Navoiy's own philosophical exposition
- Wahdat al-wujud (Unity of Being) theology
- Tajalli (Divine Manifestation) doctrine
- Mystical anthropology

### 📖 MAJOLISUN-NAFOIS (Gatherings of the Refined)
- Biographical dictionary (tazkirah) of 459 poets
- 8 Majlis (assemblies) structure
- Literary history of Timurid Herat
- Poetic craft terminology (tab', she'r, etc.)

---

## 📊 Corpus Statistics v1.1

| Metric | v1.0 | v1.1 | Change |
|--------|------|------|--------|
| Total Texts | 26 | 29 | +3 |
| Annotated Terms | 5 | 15 | +10 |
| Languages | 9 | 9 | — |
| Poetry Lines | 2,847 | 3,247 | +400 |
| Prose Words | 0 | 8,934 | NEW |
| Translation Units | 103 | 309 | +200% |

### Top 10 Terms by Frequency (Updated)

1. **yor** (beloved) — 201
2. **ko'ngul** (heart/soul) — 156
3. **ishq** (divine love) — 127
4. **husn** (beauty) — 112
5. **oh** (sigh) — 94
6. **she'r** (poetry) — 67
7. **tab'** (poetic genius) — 53
8. **talab** (quest) — 52
9. **simurgh** (divine symbol) — 47
10. **ma'rifat** (gnosis) — 41

---

## 📂 Repository Structure v1.1

```
navoiy-terra-corpus/
├── texts/
│   ├── ghazals_uzbek.txt                    # Original 13 ghazals
│   ├── short_forms_uzbek.txt                # 8 rubai + 5 tuyuq
│   ├── lisonut_tayr_nazm_excerpts.txt       # NEW: Poetry excerpts
│   ├── lisonut_tayr_nasr_excerpts.txt       # NEW: Prose commentary
│   ├── majolisun_nafois_excerpts.txt        # NEW: Literary history
│   └── README_TEXTS.md
│
├── annotations/
│   ├── semantic_lexicon_v1.json             # Original 5 terms
│   ├── semantic_lexicon_v1.1_expanded.json  # 9-language expansion
│   └── semantic_lexicon_v1.2_expanded.json  # NEW: 15 terms total
│
├── analysis/
│   ├── semantic_network.html                # Interactive D3.js viz
│   └── simurgh_network.html                 # NEW: Lisonut-tayr viz
│
├── docs/
│   ├── METHODOLOGY.md                       # Research framework
│   ├── TERRA_DESIGN.md                      # Design system
│   ├── LISONUT_TAYR_ANALYSIS.md            # NEW: Seven Valleys guide
│   ├── MAJOLISUN_NAFOIS_GUIDE.md           # NEW: Tazkirah navigation
│   └── CITATION.md
│
├── CHANGELOG.md                             # NEW: Version history
├── CORPUS_MANIFEST.md
└── README.md (this file)
```

---

## 🚀 Quick Start v1.1

### For Literary Scholars

**Explore the Seven Valleys Journey:**
```bash
cd texts/
cat lisonut_tayr_nazm_excerpts.txt | grep -A 5 "vodiy"
```

**9-Language Semantic Lexicon:**
```bash
cd annotations/
cat semantic_lexicon_v1.2_expanded.json | jq '.terms[] | select(.source=="Lisonut-tayr")'
```

**Interactive Simurgh Network:**
```bash
cd analysis/
open simurgh_network.html  # Visualize bird metaphor system
```

### For Programmers

**Load v1.2 Lexicon:**
```javascript
import lexicon from './annotations/semantic_lexicon_v1.2_expanded.json';

// Get Lisonut-tayr specific terms
const lisonutTerms = lexicon.terms.filter(t => 
  t.source && t.source.includes('Lisonut-tayr')
);

// Access 9-language translations
lisonutTerms.forEach(term => {
  console.log(`${term.term_chagatai}:`);
  Object.entries(term.translations).forEach(([lang, trans]) => {
    console.log(`  ${lang}: ${trans}`);
  });
});
```

**Extract Seven Valleys Concepts:**
```python
import json

with open('annotations/semantic_lexicon_v1.2_expanded.json') as f:
    data = json.load(f)

# Find valley terms
valley_terms = [t for t in data['terms'] 
                if t.get('semantic_field', '').endswith('_valley')]

for term in valley_terms:
    print(f"{term['term_chagatai']}: {term['sufi_context']}")
```

---

## 🔬 Research Applications v1.1

### New Possibilities with Complete Lisonut-tayr

**1. Comparative Mysticism**
- Attar's *Mantiq al-tayr* (Persian) ↔ Navoiy's *Lisonut-tayr* (Chagatai)
- Influence patterns across Turko-Persian sphere
- Simurgh symbolism evolution

**2. Multimodal Analysis**
- Poetry (nazm) vs. Prose (nasr) on same topics
- Semantic density comparison
- Metaphor networks across genres

**3. Literary Network Analysis**
- 459 poets in Majolisun-nafois
- Timurid literary circles
- Master-disciple relationships
- Geographic spread (Herat → Samarqand → Tabriz)

**4. Computational Stylometry**
- Ghazal vs. Masnavi vs. Nasr stylistic features
- Vocabulary richness across genres
- Sufi terminology density

**5. Translation Studies**
- 9-language semantic fields
- Untranslatability patterns
- Cultural concept migration

---

## 📖 Key Concepts v1.1

### Seven Valleys of Lisonut-tayr

| Valley | Chagatai | Meaning | Challenge |
|--------|----------|---------|-----------|
| 1 | Talab | Quest | Initiate seeking |
| 2 | Ishq | Love | Passionate attachment |
| 3 | Ma'rifat | Gnosis | Direct knowledge |
| 4 | Istig'no | Detachment | Release from want |
| 5 | Tawhid | Unity | Oneness vision |
| 6 | Hayrat | Bewilderment | Ecstatic confusion |
| 7 | Faqr-u-Fano | Poverty & Annihilation | Ego dissolution |

**Final Revelation**: *Simurgh* = *Si Murgh* (30 birds) — Seekers discover they themselves are what they sought.

### Wahdat al-Wujud (Unity of Being)

**Core Navoiy Doctrine** (from Lisonut-tayr nasr):
- All existence is divine self-manifestation (*tajalli*)
- Multiplicity is illusory; unity is real
- Human essence = divine essence veiled
- Spiritual journey = unveiling process

---

## 🎯 Symposium Integration (Feb 9, 2026)

### Presentation Ready Materials

**For Panel Discussions:**
- `docs/LISONUT_TAYR_ANALYSIS.md` — Comprehensive guide
- `analysis/simurgh_network.html` — Live demo visualization
- `semantic_lexicon_v1.2_expanded.json` — 9-language glossary

**For Workshops:**
- Code examples in Python/JavaScript
- JSON-LD ready for SPARQL queries
- TEI-XML export scripts

**For Publications:**
- BibTeX citations ready
- Methodology paper (2,800 words)
- ORCID integration

---

## 🤝 Contributing v1.1

We especially welcome:

**Subject Matter Experts:**
- Sufi philosophy annotations
- Persian-Chagatai comparative notes
- Uyghur translation refinements

**Technical Contributors:**
- SPARQL endpoint development
- TEI-XML conversion scripts
- NLP pipelines for Chagatai

**Linguists:**
- 10th language (Turkish, Azerbaijani, Kazakh, Tatar)
- Dialectal variations within existing 9

**Developers:**
- React components for Terra visualizations
- REST API for lexicon queries
- Mobile app for field research

---

## 📜 Citation v1.1

### APA 7th
```
Abdukarimov, A. (2026). NAVOIY-TERRA Corpus v1.1: Complete Lisonut-tayr Edition 
with 9-Language Semantic Annotations [Data set]. GitHub. 
https://github.com/Secret-Uzbek/navoiy-terra-corpus
```

### BibTeX
```bibtex
@misc{abdukarimov2026navoiy_v1_1,
  author = {Abdukarimov, Abdurashid},
  title = {{NAVOIY-TERRA} Corpus v1.1: Complete Lisonut-tayr Edition},
  year = {2026},
  publisher = {GitHub},
  version = {1.1},
  url = {https://github.com/Secret-Uzbek/navoiy-terra-corpus},
  note = {Expanded with complete Lisonut-tayr (nazm \& nasr) and Majolisun-nafois excerpts}
}
```

---

## 🗺️ Roadmap

- **v1.1** (Current) ✅ Complete Lisonut-tayr + Majolisun-nafois
- **v1.2** (March 2026) 📚 Layli va Majnun excerpts + 50 terms
- **v2.0** (Q3 2026) 📖 Complete Khamsa + 200 terms + REST API

---

## 🌐 Links

- **FMP Central**: https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO
- **Author ORCID**: https://orcid.org/0009-0000-6394-4912
- **Website**: https://fractal-metascience.org
- **Symposium**: V International "Navoiy va Sharq Renessansi" (Feb 9, 2026)

---

## 📍 Author Location

**Tashkent, Uzbekistan** 🇺🇿  
*Home of Alisher Navoiy (1441-1501)*

---

**Built with ❤️ using:**
- **NULLO** (Zero Budget Protocol)
- **PLT** (Plural-Lingual Translation Layer)
- **UCOMM** (Universal Communication)
- **FMP** (Fractal Metascience Paradigm)

---

© 2026 Abdurashid Abdukarimov | CC BY 4.0

*"Si Murgh" — We are what we seek* 🦅
