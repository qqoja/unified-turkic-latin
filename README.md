# UTL — Unified Turkic Latin

**Version 1.15** | Designed for optimal compatibility with AI systems (LLMs).

---

## Changelog

* **v1.1 – v1.3**: Added letter `Jj` for /j/ and `Žž` for /ʒ/. Introduced two-tier architecture: UTL-O (Orthographic level) and UTL-P (Phonetic level).
* **v1.4 – v1.6**: Replaced `Әә` with `Ää` to improve tokenization efficiency. Transitioned to unified diacritics (caron/hacek) for sibilants: `Č`, `Š`, `Ž`.
* **v1.7**: Resolved the "Turkish-i problem": `I` always represents the front-row /i/, while `Ї` represents the back-row /ɯ/ (similar to 'ы').
* **v1.8 – v1.10**: Introduced explicit diphthongs `IY`, `UW`, `ÜW` in UTL-O to distinguish native Turkic vocabulary.
* **v1.11 – v1.15**: Grouped 16 languages, introduced the **UTL-Extended** module, and finalized the automated loanword detection algorithm.

---

## Core Development Principles

* **Phonetic Completeness**: Comprehensive coverage of Oghuz, Kipchak, and Karluk branches.
* **AI-Optimality**: Utilization of characters with high "weight" in existing neural network training sets to reduce token fragmentation.
* **Uniformity**: Strict "one sound — one letter" correspondence across all 16 supported languages.
* **ASCII Compatibility**: Defined transliteration rules for legacy systems and environments without Unicode support.
* **Two-Tier Architecture**: Separation between the writing standard (UTL-O) and the analytical phonetic layer for AI processing (UTL-P).

---

## UTL Alphabet (Basic Set)

### Vowels (9 Phonemes)

* **Aa** — Back row, unrounded. Example: *at* (horse). ASCII: `Aa`.
* **Ee** — Front row, unrounded. Example: *el* (hand). ASCII: `Ee`.
* **Ii** — Front row, unrounded. Example: *ip* (rope). ASCII: `Ii`.
* **Її** — Back row, unrounded. Phonetically corresponds to 'ы'. Example: *qiz* (girl). ASCII: `I'i'`.
* **Oo** — Back row, rounded. Example: *on* (ten). ASCII: `Oo`.
* **Uu** — Back row, rounded. Example: *un* (flour). ASCII: `Uu`.
* **Öö** — Front row, rounded. Example: *öz* (self). ASCII: `Oe`.
* **Üü** — Front row, rounded. Example: *gün* (day). ASCII: `Ue`.
* **Ää** — Front row, open unrounded. Example: *äl* (hand/arm). ASCII: `Ae`.

### Key Consonants and Semivowels

* **Yy** — Palatal semivowel /j/.
* **Ww** — Labial semivowel /w/. Used in diphthongs and word-initial positions.
* **Jj** — Voiced affricate /dʒ/ (as in "judge").
* **Čč** — Voiceless affricate /tʃ/ (as in "church").
* **Šš** — Voiceless fricative /ʃ/ (as in "she").
* **Žž** — Voiced fricative /ʒ/ (as in "measure").
* **Ğğ** — Voiced velar fricative.
* **Ŋŋ** — Velar nasal consonant (as in "sing").
* **Cc** — Voiceless alveolar affricate /ts/ (used for loanwords).

---

## AI Optimization Rules

### Native Vocabulary Marking (Diphthongs)
To improve the accuracy of Turkic lexical recognition, explicit digraphs are used instead of single letters in specific positions:
* **IY** (instead of I): *biyik* (high/tall).
* **UW** (instead of U): *suw* (water).
* **ÜW** (instead of Ü): *küwn* (day).
* **AW / OW**: *taw* (mountain).

### Automated Loanword Processing
The UTL algorithm allows neural networks to identify word origins without additional markers:
1. If a word violates vowel harmony (mixed rows), it is flagged as a loanword.
2. Declension and suffixation always align with the **last vowel** of the stem (e.g., *institut* -> *instituttar*).

---

## Language Coverage

* **Oghuz Group**: Turkish, Azerbaijani, Turkmen, Gagauz.
* **Kipchak Group**: Kazakh, Kyrgyz, Tatar, Bashkir, Karakalpak, Nogai, Kumyk, Karachay-Balkar, Crimean Tatar.
* **Karluk Group**: Uzbek, Uyghur.
* **UTL-Extended**: Sakha (Yakut), Tuvan, Khakas, Altai, Chuvash.

---

## License

This project is distributed under the **Apache License 2.0**. This license was chosen to ensure maximum legal safety for the standard's integration into both commercial and open-source AI models.
