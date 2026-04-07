# UTL — Unified Turkic Latin

**Version 1.15 | Designed for compatibility with AI systems**

> **Changes in v1.1:** Added the letter **J j** for /j/ “Й”; **Ž ž** replaced J for /ʒ/; duplicate İ removed; examples and correspondence tables corrected.
> **Changes in v1.2:** added rule for loanwords — no markers, suffix determined by the last vowel of the word; added algorithm for determining loanwords for AI.
> **Changes in v1.3:** Introduced a two-level architecture UTL-O / UTL-P; corrected conversion rules — native words and loanwords have different rules for diphthongization.
> **Changes in v1.4:** **Ə ə** replaced with **Ä ä** — better tokenization in AI models, familiar from German/Finnish/Swedish corpora, more intuitive for humans.
> **Changes in v1.5:** **Y y** /ɯ/ replaced with **ı** (i without a dot) — Turkish standard, excellent tokenization, no conflict with Latin Y=/j/.
> **Changes in v1.6:** full transition to the hook — **Ç→Č**, **Ş→Š**, **Ğ→Ǧ**; a single diacritic for all modified consonants; **Ñ** replaced with **Ŋ** as the primary letter for /ŋ/; Rule 6 added — descending diphthongs AW/OW/EW are explicitly written with W.
> **Changes in v1.7 — five critical fixes:**
> 
> 1. **ı → ï** — resolved the collision between uppercase I and ı (Turkish-i problem); uppercase letters are now unambiguous: I=/i/, Ï=/ɯ/.
> 1. **C=/dʒ/ → Ĵ=/dʒ/**, **C=/ts/** — the voiced affricate now has a symmetrical counterpart to Č; C has been freed up for /ts/.
> 1. **Ǧ=/ɣ/ → Ğ=/ɣ/** — the velar fricative has been removed from the hook system; breve = weakened velar.
> 1. **C=/ts/ added** — the problem with Gagauz and Russian loanwords (center, price, police) has been resolved.
> 1. **Ŧ=/θ/, Đ=/ð/ added** — Bashkir dental fricatives.
>    **Changes in v1.8 — explicit diphthongs in UTL-O:**
> 1. Kazakh, Kyrgyz, Tatar, and Bashkir diphthongs are written **explicitly** using existing letters: **IY** /ɪj/, **UW** /ʊw/, **ÜW** /ʏw/.
> 1. The O→P conversion table for diphthongs has been **removed** — basic phonemics are fully handled in UTL-O.
> 1. UTL-P is retained only for allophonic details (velarization, assimilation, intonation).
> 1. Extended letters Ĭ/Ŭ **are not needed** — diphthongs resolve the І/И and Ұ/У issue without new symbols.
> 1. The text is self-contained — it does not require a language tag for correct reading.
>    **Changes in v1.9 — fixes:**
> 1. Added the entry **Ү (borrowed) → Ü** to the Kazakh vowel table.
> 1. Fixed errors in examples: *suwrgen* → **süwrgen** (Ү, not У), *güwn* (Kaz.) → **küwn** (К, not Г in Kazakh).
> 1. All examples of Kazakh text have been rechecked and corrected.
>    **Changes in v1.10 — review of all examples:**
> 1. Example I corrected: *il* “year” → *il* “province”.
> 1. Example N corrected: *ner* “thing” → *ne* “what” (Turkic).
> 1. Example P corrected: *paš* “head” → *pïčaq* “knife”.
> 1. Corrected example W: removed the “Kaz.” note from *watan*, added *waqït* “time”.
> 1. Corrected Tatar: *Tuğan* → **Tugan** (no /ɣ/ in this word).
> 1. Corrected Turkmen: *söjjärin* → **söjärin** (single J).
> 1. Kazakh corrected: *jaqsï* → **žaqsï** (Ж=/ʒ/=Ž).
> 1. Suffixation corrected: *institutter* → **instituttar** (U=back→-tar); *universitetler* → **universitetter** (after T→-ter, doubling); *cirkde/cirkler* → **cirkte/cirkter** (after K→-te/-ter).
> 1. Example for Ŋ clarified: *aŋ* “consciousness/understanding”.
>    **Changes in v1.11 — revision of language coverage:**
> 1. **Removed** Chuvash and Yakut — isolated branches with zero mutual intelligibility, not in OTS, incomplete phoneme coverage.
> 1. **Added** Karakalpak, Gagauz, Crimean Tatar — fully covered, high mutual intelligibility, use the Latin alphabet.
> 1. Extended letters Ź, Ĺ (Yakut) retained as reserve, Ħ (Uyghur) retained.
> 1. Justification for C=/ts/ changed: not a Chuvash phoneme, but preservation of information in loanwords.
> 1. Languages grouped by branches: Oghuz, Kipchak, Karluk.
>    **Changes in v1.12 — two-tier language coverage:**
> 1. **UTL** (basic, 16 languages) and **UTL-Extended** (extended, 8+ languages) have been introduced.
> 1. UTL: three branches of the Turkic languages — Oghuz (4), Kipchak (9), Karluk (2) + 1 mixed.
> 1. UTL-Extended: Siberian (Yakut, Tuvan, Khakas, Altai, Shor, Dolgan), Bulgar (Chuvash), archaic Oghuz (Salars).
> 1. **Nogai, Karachay-Balkar, and Kumyk** have been added to UTL.
> 1. Extended letters have been assigned: Ŧ/Đ (Bashkir) and Ħ (Uyghur) — UTL; Ź/Ĺ — UTL-Extended.
>    **Changes in v1.13 — comparative analysis and accumulated edits:**
> 1. Added section **“Comparison with other projects”** — CTA 2024, Kazakh 2021, Uzbek 1995/2023, Turkmen 1999, Zamanälif, ULY, etc.
> 1. **Karon** instead of “hook” in the description of diacritics + technical footnote about Ĵ (circumflex U+0134).
> 1. ASCII collision **Ng vs N+G** — documented in the description of ASCII mode.
> 1. Clarified: **Kumyk** uses V (not W) — Oghuz influence.
> 1. The notation **“(Kir.)”** has been removed from the Kazakh entry in the correspondence table.
>    **Changes in v1.14 — J/Y reassignment, diphthongoids, apostrophe:**
> 1. **Y=/j/, J=/dʒ/** — the marginal Ĵ has been removed; Y=/j/ matches CTA, Turkish, and all Turkic Latin alphabets; J=/dʒ/ matches the English association.
> 1. **Ĵ removed**, **Y added** → **35 base letters** (number unchanged: Ĵ→Y replacement).
> 1. Diphthongs: IJ→**IY**, ÏJ→**ÏY** (J replaced by Y as a semivowel).
> 1. ASCII: Ï → **I’** (apostrophe marks /ɯ/). Without apostrophe — I (context and vowel harmony resolve ~95% of cases).
> 1. **Note on diphthongoids** UW/ÜW — weak glide, not a full semivowel.
> 1. **Apostrophe for /ʔ/ removed** — a marginal phoneme in Arabic loanwords, not recorded in UTL.
> 1. **Definition of glides** — explanation of the nature of Y and W as semivowels (glide).
> 1. **Symmetry of Kazakh vowels** — І/Й/И ↔ Ұ/У̯/У, justification based on Baitursynov’s theory (5 base vowels + 4 allophones + 2 semivowels).
> 1. **Cyrillic→UTL conversion table** — rules for Kazakh: И→IY, У→UW, Ү→ÜW in native words; И→I, У→U, Ү→Ü in loanwords.
> 1. **Historical precedents** — the 1928 Baku alphabet (v=У/w/), the 1938 rule (ю=и+у), Batmanov 1939 (Kyrgyz long vowels), Yrk Bitig (a/ä, ı/i).
> 1. **Exact IPA values of diphthongoids** — IY /ɪj/ (was /ij/), UW /ʊw/ (was /uw/).
> 1. **Ġ removed** from the extended alphabet → 3 extended letters (Ŧ, Đ, Ħ). /ɢ/ — a dialectal variant, not a phoneme.
> 1. **ASCII: Ï → I’** (apostrophe). The only letter requiring a marker. The apostrophe in ASCII = a technical symbol (marker for Ï and digraph separator), not a UTL letter.
> 1. **Long vowels** — section expanded: Turkmen (9 long vowels, minimal pairs), Kyrgyz (6 long vowels, Batmanov 1939), Uyghur (long vowels in Arabisms). Doubling = phonemic length. Discrepancies with the Turkmen Latin alphabet are documented.
> 1. **Diphthongs expanded** — Tatar and Bashkir diphthongs added (AY, EY, ÖY, ÜY). Summary of diphthongs by language.
> 1. **Language profiles** — a section for each of the 16 languages: used/unused letters, diphthongs, long vowels, extended vowels. Summary table.
>    **Changes in v1.15 — language profiles, long vowels, loanwords:**
> 1. **Language profiles** — a section for each of the 16 languages: letters, W/V, diphthongs, long vowels, extended vowels. Summary table.
> 1. **Long vowels expanded** — Turkmen (9 pairs with minimal pairs), Kyrgyz (6 pairs), Uyghur (Arabic loanwords). Discrepancy with the Turkmen Latin alphabet.
> 1. **Extended diphthongs** — Tatar/Bashkir AY, EY, ÖY, ÜY. Summary by language.
> 1. **Uyghur long vowels** — *aalam*, *kaatip* (Arabic loanwords, doubled).
> 1. **Borrowed letters** — explanation of F, V, C, Ž as letters for loanwords. Degree of adaptation by language.
> 1. **Historical precedents** — Baku 1928, 1938 rule, Batmanov 1939, Yrk Bitig.
> 1. **ASCII: Ï → I’** — two-level ASCII (minimal/precise). Ħ→Hh added.
> 1. **Ġ removed** → 3 extended (Ŧ, Đ, Ħ).
> 1. **Removed** the section “Summary of all changes v1.6→v1.15” (duplicated the changelog).
> 1. **Corrections:** Ï ASCII Y→I’, Kypchak table, ÜW=front row, *qarra*→*anna*, *su* (Turk.).

-----

## Development Principles

UTL was created with five key requirements in mind:

1. **Phonetic Comprehensiveness** — two-tier coverage of Turkic languages:
- **UTL** (basic) — 16 languages from the three main branches:
  - *Oghuz:* Turkish, Azerbaijani, Turkmen, Gagauz
  - *Kipchak:* Kazakh, Kyrgyz, Karakalpak, Nogai, Karachay-Balkar, Kumyk, Tatar, Bashkir, Crimean Tatar
  - *Karluk:* Uzbek, Uyghur
- **UTL-Extended** — Siberian, Bulgar, and archaic Turkic languages (Yakut, Tuvan, Khakas, Altai, Chuvash, etc.)
1. **AI-optimization** — minimal diacritics, maximum tokenizability; every sound is a predictable symbol.
1. **Uniformity** — one sound = one letter in all languages without exception.
1. **ASCII compatibility** — each letter has a unique ASCII equivalent for use in LLM prompts and databases.
1. **Two-level architecture** — UTL-O for humans (phonemic notation), UTL-P for AI (allophonic details, generated automatically).

-----

## UTL Diacritics System v1.15

Four types of diacritics—four types of modifications. Each is predictable:

```
Caron (ˇ)    = sibilant fricative or affricate: Š Ž Č
Breve (˘)    = weakened velar:       Ğ
Diaeresis (¨) = modified vowel:   Ö Ü Ä Ï
Dash (-)    = dental fricative:         Ŧ Đ  (extended)
```

-----

## UTL Diphthong System v1.15

### Glides (semivowels)

**Glide** (glide, semivowel) — a sound that “glides” from the position of one vowel to another. Glides are an intermediate class between vowels and consonants: in terms of articulation, they are close to vowels, but in terms of function, they behave like consonants — they do not form a syllable on their own, but serve the adjacent vowel.

There are two glides in UTL:

```
Y /j/ — palatal glide: the tongue glides from/to the position of /i/
W /w/ — labial glide: the lips glide from/to the position of /u/
```

### Symmetry of Kazakh Vowels in UTL

Kazakh **I** and **U** are not simple vowels, but diphthongoids (vowel + glide). UTL makes this structure explicit:

```
І /ɪ/ → I  (pure vowel)     ↔  Ұ /ʊ/ → U  (pure vowel)
Й /j/ → Y  (glide)              ↔  У̯ /w/ → W  (glide)
И /ɪj/ → IY (vowel + glide)   ↔  У /ʊw/ → UW (vowel + glide)
```

Similarly for the front row: Ү /ʏw/ → **ÜW** (vowel Ü + glide W).

> **Theoretical Basis (A. Baitursynov):** The founder of Kazakh grammar, A. Baitursynov, identified 5 basic vowels in the Kazakh language (A, O, Ұ, Ы, Е), 4 allophones (Ə, Ө, Ү, І), and 2 semivowels (У, Й). In this classification, **І** and **У** are not vowels but **semivowels** (diphthongoids). Pure vowels are **І** and **Ұ**. Equivalences: ə = a + e, ö = o + e, ü = u + e, i = y + e. The UTL system accurately reproduces this structure: I = I + Y, U = U + W, while I and U are written with a single letter (I and U).

### Rule for converting Cyrillic to UTL (Kazakh)

In native Kazakh words, И, У, and Ү are **always** diphthong-like. In loanwords, they are monophthongs. There are no exceptions:

|Cyrillic|Native word|Loanword|
|-------- -|------------|-------------|
|І        |I (always)  |—            |
|И        |**IY**      |I            |
|Ы        |Ï (always)  |—            |
|Ұ        |U (always)  |—            |
|У        |**UW**      |U            |
|Ү        |**ÜW**      |Ü            |

Examples: *bit* “louse” → **biyt** (native, И=IY); *institute* → **institut** (loanword, И=I); *su* “water” → **suw** (native, U=UW); *autobus* → **avtobus** (loanword, U=U).

### Historical precedents

The UTL diphthong system is not an innovation—it has direct parallels in the history of the Turkic Latin alphabet:

**The 1928 Alphabet (Baku, Unified Turkic):** In the Kazakh variant of the Latin alphabet adopted at the 1928 Baku Conference, the letter **v** denoted the semivowel У /w/, **y** — Ы /ɯ/, **i** — І /ɪ/. Principle: У is not a vowel but a semivowel, written as a separate consonant letter.

**The 1938 Rule (Kazakh Latin script):** The Russian letter **ю** in loanwords was written as **и+у** (*iuвilei*, *soiuz*, *kaiuta*)—direct confirmation that И and У were treated as combinations, not monophthongs.

**Kyrgyz Grammar (Batmanov, 1939):** The Kyrgyz language has 14 vowel phonemes—8 short (a, e, o, ɵ, ɨ, i, u, y) and 6 long (aa, ee, oo, ɵɵ, uu, yy) . Long vowels are written by doubling—UTL supports this principle. Kyrgyz short vowels are 3–5 times shorter than Russian ones, which explains the diphthong-like pronunciation.

** Old Turkic (Yrk Bitig, ~10th century):** The runic script already distinguished back/front pairs: a/ä, ı/i, o/ö, u/ü—the foundation of the UTL vowel system. Garkavets’ transcription uses the symbols ŋ, ğ, š, ä, which correspond to UTL.

### Diphthongs

Two glides—**Y** and **W**—account for all diphthongs without the need for new letters:

```
Y marks a palatal glide:   IY /ɪj/ (front), ÏY /ɯj/ (back)
W marks labial glide:    UW /ʊw/ (back), ÜW /ʏw/ (front), AW /aw/ (back), OW /ow/ (back)
```

Diphthongs are written explicitly in UTL-O. The text is self-contained without a language tag.

### Rules for diphthongs in native words and loanwords

|Context                 |Sound|UTL-O |Example              |
|-------------------------|----|------|--------------------|
|Native word, diphthong    |/ɪj/|**IY**|*biyik* “tall”   |
|Native word, diphthong    |/ʊw/|**UW**|*suw* “water”        |
|Native word, diphthong    |/ʏw/|**ÜW** |*küwn* “day” (Kaz.)|
|Native word, diphthong    |/aw/|**AW**|*taw* “mountain”        |
|Borrowed word, monophthong |/i/ |**I** |*institut*          |
|Borrowed word, monophthong |/u/ |**U** |*universitet*       |
|Any context, monophthong|/ɪ/ |**I** |*bil* “know” (Kaz.) |
|Any context, monophthong|/ʊ/ |**U** |*bul* “this” (Kaz.)  |

-----

## Language Coverage: UTL and UTL-Extended

### UTL (basic) — 16 languages

Common Turkic languages of the three main branches. Mutual intelligibility is non-zero; phonemes are fully covered by the basic alphabet (35 letters) and the extended letters Ŧ/Đ/Ħ.

#### Oghuz (southwestern) — 4 languages

|Language           |Speakers|Script|OTS        |
|---------------|--------|------------|---------- -|
|Turkish       |~80 million |Latin    |✓          |
|Azerbaijani|~30 million |Latin    |✓          |
|Turkmen    |~7 million  |Latin    |observer|
|Gagauz     |~150,000|Latin    |—          |

#### Kipchak (Northwestern) — 9 languages

|Language                |Subgroup       |Speakers|Writing system   |OTS       |
|--------------------|--------------- -|--------|---------------|----------|
|Kazakh           |Nogai       |~13 million |transition to Latin|✓         |
|Karakalpak      |Nogai       |~700,000|Latin script       |via Uzbek|
|Nogai           |Nogai       |~90,000 |Cyrillic script      |—         |
|Kyrgyz          |Kipchak-Polovtsian|~5 million  |Cyrillic script      |✓         |
|Karachay-Balkar|Kipchak-Polovtsian|~300,000|Cyrillic      |—         |
|Kumyk           |Kipchak-Polovtsian|~500,000|Cyrillic      |—         |
|Tatar           |Volga      |~5 million  |Cyrillic      |—         |
|Bashkir          |Volga      |~1.2 million|Cyrillic      |—         |
|Crimean Tatar    |Kipchak-Oghuz  |~500,000|Latin       |—         |


> *Note:* Kumyk, despite belonging to the Kipchak branch, is strongly influenced by Oghuz and uses V /v/ (not W /w/) for labial consonants—like Turkish and Azerbaijani.

#### Karluk (Southeastern) — 2 languages

|Language     |Speakers|Script      |OTS|
|---------|--------|------------------|---|
|Uzbek|~30 million |Latin script          |✓  |
|Uyghur|~12 million |Arabic / Latin|—  |


> **Total UTL:** ~186 million speakers, coverage: 35 basic letters + 3 extended (Ŧ, Đ, Ħ).

-----

### UTL-Extended — 8+ languages

Isolated branches of Turkic languages with zero or minimal mutual intelligibility with UTL languages. Require additional letters and rules. Supported via reserve letters and language-specific extensions.

#### Siberian Turkic — 6 languages

|Language           |Speakers|Branch               |Unique requirements               |
|---------------|--------|------------------- -|-------------------------------------|
|Yakut (Sakha)|~450,000|Siberian           |/ðʲ/ → Ź, /lʲ/ → Ĺ, diphthongs uo/ie/üö|
|Tuvan      |~280,000|Siberian           |pharyngealization, long vowels       |
|Khakas      |~40,000 |Siberian           |palatal affricates                |
|Altaic      |~55,000 |Siberian           |/dʲ/, /tʲ/                           |
|Shor        |~2,500|Siberian           |same as Khakas                        |
|Dolgan     |~1,000  |Siberian (Yakut)|same as Yakut                         |

#### Bulgar branch — 1 language

|Language     |Speakers|Unique features                             |
|---------|--------|-------------------------------------------------- -|
|Chuvash|~1 million|/ts/ phoneme, Ă /ə̆/, Ĕ /ɘ̆/ — reduced vowels|

#### Archaic Oghuz — 1+ language

|Language     |Speakers|Unique needs                           |
|-------- -|--------|-------------------------------------------------|
|Salars|~70,000 |Archaic Oghuz, Tibetan/Chinese influence|


> **Total UTL-Extended:** ~1.9 million speakers. Reserve letters: Ź, Ĺ. Additional letters are determined during the development of a specific language profile.

-----

## The UTL Alphabet — Complete Chart

### Vowels (9 letters)

|UTL    |IPA|Row     |Occlusion|Examples                          |ASCII|
|-------|---|--------|----------- -|---------------------------------|-----|
|**A a**|/a/|back  |none         |*at* “horse”, *ana* “mother”      |A a  |
|**E e**|/e/|front|none         |*el* “hand”, *er* “man”      |E e  |
|**I i**|/i/|front|none         |*ip* “rope”, *il* “province” |I i  |
|**Ï ï**|/ɯ/|back  |no         |*qïz* “girl”, *yïl* “year”     |I’ i’|
|**O o**|/o/|back  |yes          |*on* “ten”, *ot* “grass”      |O o  |
|**U u**|/u/|back  |yes          |*un* “flour”, *bul* “this” (Kaz.)  |U u  |
|**Ö ö**|/ø/|front|yes          |*öz* “self”, *köz* “eye”         |Oe oe|
|**Ü ü**|/y/|front|yes          |*üč* “three”, *gün* “day”         |Ue ue|
|**Ä ä**|/æ/|front|no         |*äl* (Az.) “hand”, *äkin* “sowing”|Ae ae|


> **Note for AI — vowel harmony:**
> 
> - Back row: **A, Ï, O, U** → suffixes with back vowels
> - Front row: **E, I, Ö, Ü, Ä** → suffixes with front vowels
> 
> Example: *kitap* + locative → *kitapta* (A-row) / *ev* + locative → *evde* (E-row)

-----

### Four key distinctions: I / Y / Y / U

|Russian sound|IPA|UTL    |Type                  |Examples                          |
|------------|---|-------|---------------------|---------------------------------|
|**И**       |/i/|**I i**|vowel, front    |*ip* “rope”, *bil* “know”     |
|**Ы**       |/ɯ/|**Ï ï**|vowel, back      |*qïz* “girl”, *yïl* “year”     |
|**Y**       |/j/|**Y y**|semivowel|*yol* “road”, *ay* “moon”|
|**U**       |/u/|**U u**|back vowel|*bul* “this”, *un* “flour”         |


> **For AI:** Y is always /j/ as in the Turkic *yol* or the German *ja*. J is always /dʒ/ as in the English *judge*. Ž is /ʒ/ as in *measure*.

> **Uppercase letters are unambiguous:**
> 
> - **I** — always uppercase from **i** (/i/)
> - **Ï** — always uppercase from **ï** (/ɯ/)
> - The Turkish-i problem has been completely resolved.

-----


### Consonants (26 letters)

|UTL    |IPA  |Sound                           |Examples                                         |ASCII|
|-------|-----|-------------------------------|------------ ------------------------------------|-----|
|**B b**|/b/  |voiced labial-labial           |*bar* “to eat”, *bala* “child”                  |B b  |
|**C c**|/ts/ |voiceless dental affricate        |*centr* “center”, *policija* “police” (loanword)|C c  |
|**Č č**|/tʃ/ |voiceless sibilant affricate       |*čaj* “tea”, *čöl* “desert”                    |Ch ch|
|**D d**|/d/  |voiced dental                 |*dağ* “mountain”, *dil* “language”                      |D d  |
|**F f**|/f/  |voiceless labiodental            |*fikir* “idea”, *fal* “fortune-telling”                 |F f  |
|**G g**|/ɡ/  |voiced velar               |*gel* “come”, *göz* “eye”                     |G g  |
|**Ğ ğ**|/ɣ/  |voiced velar fricative   |*dağ* “mountain”, *ağa* “elder”                   |Gh gh|
|**H h**|/h/  |voiceless glottal               |*hava* “air”, *han* “khan”                    |H h  |
|**X x**|/x/  |voiceless velar fricative    |*xalq* “people”, *xan* “khan”                     |Kh kh|
|**Y y**|/j/  |palatal semivowel **“Y”**|*yol* ‘road’, *ay* “moon”                     |Y y  |
|**J j**|/dʒ/ |voiced sibilant affricate      |*jan* “soul”, *jahan* “world”                     |J j  |
|**Ž ž**|/ʒ/  |voiced sibilant fricative    |*žurnal* “magazine” (loanword)                    |Zh zh|
|**K k**|/k/  |voiceless velar                |*kel* “come”, *köl* “lake”                    |K k  |
|**Q q**|/q/  |voiceless uvular               |*qala* “fortress”, *qan* “blood”                |Q q  |
|**L l**|/l~ɫ/|lateral (soft/hard)     |*lale* “tulip”, *el* “hand”                   |L l  |
|**M m**|/m/  |nasal labial                 |*men* “I”, *mal* “property”                    |M m  |
|**N n**|/n/  |nasal alveolar                 |*nan* “bread”, *ne* “what”                        |N n  |
|**Ŋ ŋ**|/ŋ/  |velar nasal               |*köŋül* “soul”, *aŋ* “consciousness”                 |Ng ng|
|**P p**|/p/  |voiceless labial                  |*pul* “money”, *pïčaq* “knife”                   |P p  |
|**R r**|/r/  |trilled alveolar       |*yer* “place”, *yurt* “yurt”                    |R r  |
|**S s**|/s/  |voiceless dental fricative      |*su* “water” (Turk.), *söz* “word”               |S s  |
|**Š š**|/ʃ/  |voiceless sibilant                 |*šan* “glory”, *baš* “head”                   |Sh sh|
|**T t**|/t/  |voiceless alveolar                  |*taš* “stone”, *til* “tongue”                    |T t  |
|**V v**|/v/  |voiced labiodental           |*var* “to eat”, *vaqt* “time”                    |V v  |
|**W w**|/w/  |labio-velar semivowel      |*watan* “homeland” (Turkmen), *taw* “mountain” (Kazakh)  |W w  |
|**Z z**|/z/  |voiced dental fricative     |*yaz* “summer/write”, *söz* “word”                |Z z  |

-----

### Extended Characters

#### UTL — for languages in the base set

|UTL    |IPA|Language      |Sound                      |ASCII|
|-------|---|----------|---------------- ----------|-----|
|**Ŧ ŧ**|/θ/|Bashkir|voiceless dental fricative |Th th|
|**Đ đ**|/ð/|Bashkir|voiced dental fricative|Dh dh|
|**Ħ ħ**|/ħ/|Uyghur |pharyngeal fricative  |Hh hh|

#### UTL-Extended — for Siberian and isolated languages

|UTL    |IPA |Sound                     |ASCII|
|-------|----|---- ---------------------|-----|
|**Ź ź**|/ðʲ/|voiceless dental fricative|Dy dy|
|**Ĺ ĺ**|/lʲ/|palatalized L       |Ly ly|

-----

## Complete alphabetical order of UTL v1.15

**A B C Č D E Ä F G Ğ H I Ï J K L M N Ŋ O Ö P Q R S Š T U Ü V W X Y Z Ž**

*(35 basic + 3 extended UTL + 2 UTL-Extended)*

-----

## Kazakh Vowels in UTL-O — Complete Chart

|Kazakh|Context     |Sound|UTL-O |Type              |
|---------|-------------|----|------|---------------- -|
|**А**    |always       |/a/ |**A** |monophthong        |
|**Ә**    |always       |/æ/ |**Ä** |monophthong        |
|**Е**    |always       |/e/ |**E** |monophthong        |
|**І**    |always       |/ɪ/ |**I** |short monophthong|
|**И**    |native word |/ɪj/|**IY**|diphthong          |
|**И**    |loanword|/i/ |**I** |monophthong        |
|**Y**    |always       |/ɯ/ |**Ï** |monophthong        |
|**O**    |always       |/o/ |**O** |monophthong        |
|**Ö**    |always       |/ø/ |**Ö** |monophthong        |
|**Ұ**    |always       |/ʊ/ |**U** |short monophthong|
|**У**    |native word |/ʊw/|**UW**|diphthong          |
|**У**    |loanword|/u/ |**U** |monophthong        |
|**Ү**    |native word |/ʏw/|**ÜW**|diphthong          |
|**Ү**    |loanword|/y/ |**Ü** |monophthong        |

-----

## Correspondence Table with Existing Alphabets

|Sound     |IPA |UTL   |Turkish|Azerbaijani|Kazakh   |Uzbek   |Uyghur (Latin)|
|---------|----|------|------- -|---------------|------------|------------|----------------|
|I        |/i/ |**I** |i       |i              |І           |i           |i               |
|Y        |/ɯ/ |**Ï** |ı       |ı              |Y           |—           |—               |
|J        |/j/ |**Y** |y       |y              |J           |y           |y               |
|U        |/u/ |**U** |u       |u              |U           |u           |u               |
|Diphthong IY |/ɪj/|**IY**|—       |—              |I           |—           |—               |
|Diphthong UW |/ʊw/|**UW**|—       |—              |U           |—           |—               |
|Diphthong ÜW |/ʏw/|**ÜW**|—       | —              |U           |—           |—               |
|Diphthong AU |/aw/|**AW**|—       |—              |AU          |—           |—               |
|Yu        |/ju/|**Yu**|yu      |yu             |Yu           |yu          |yu              |
|Я        |/ja/|**Ya**|ya      |ya             |Я           |ya          |ya              |
|Э/Ä      |/æ/ |**Ä** |—       |ə              |Ә           |—           |é               |
|Ö        |/ø/ |**Ö** |ö       |ö              |Ө           |oʻ          |ö               |
|Ü        |/y/ |**Ü** |ü       |ü              |—           |—           |ü               |
|Ч        |/tʃ/|**Č** |ç       |ç              |Ч           |ch          |ch              |
|Дж       |/dʒ/|**J** |c       |c              |Дж          |j           |j               |
|Ц        |/ts/|**C** |—       |—              |Ц (borrowed)|—           |—               |
|Ш        |/ʃ/ |**Š** |ş       |ş              |Ш           |sh          |sh              |
|Ж        |/ʒ/ |**Ž** | —       |j              |Zh           |j (borrowed)|zh              |
|X (fric.)  |/x/ |**X** |—       |x              |X           |x           |x               |
|Ğ        |/ɣ/ |**Ğ** |ğ       |ğ              |Ğ           |gʻ          |gh              |
|Q        |/q/ |**Q** |—       |q              |Q           |q           |q               |
|Ō        |/ŋ/ |**Ō** |—       |—              |Ō           |ng          |ng              |
|H (guttural) |/h/ |**H** |h       |h              |H (weak)   |h           |h               |
|Ҫ (Bashkir)|/θ/ |**Ŧ** |—       |—              |—           |—           |—               |
|Ҙ (Bashkir)|/ð/ |**Đ** |—       |—              |—           |—           |—               |

-----

## Symmetry of the UTL v1.15 Phonological System

### Fricatives

```
              Dental        Sibilant       Velar
Voiceless:       S /s/         Š /ʃ/         X /x/
Voiced:      Z /z/         Ž /ʒ/         Ğ /ɣ/
```

### Affricates

```
              Dental        Sibilant
Voiceless:       C /ts/        Č /tʃ/
Voiced:      —             J /dʒ/
```

### Bashkir dental fricatives (extended)

```
              Interdental
Voiceless:       Ŧ /θ/
Voiced:      Đ /ð/
```

### Plosives and uvulars

```
              Velars      Uvulars
Voiceless:       K /k/         Q /q/
Voiced:      G /ɡ/
```

### Diphthongs (v1.15)

```
Palatal (Y-glide):  IY /ɪj/ (front),  ÏY /ɯj/ (back)
Labial (W-glide):   UW /ʊw/ (back),  ÜW /ʏw/ (front),  AW /aw/ (back),  OW /ow/ (back)
```

-----

## UTL Spelling Rules

### 1. Vowel Harmony

Suffixes agree with the root according to the vowel series:

```
Back series:    A  Ï  O  U   →  suffix -da / -lar / -dan / -lï
Front series:  E  I  Ö  Ü  Ä  →  suffix -de / -ler / -den / -li
```

In diphthongs, harmony is determined by the **vowel component**: AW, UW = back; ÜW = front; IY = front.

### 1a. Borrowings — The Final Vowel Rule

In UTL, **no borrowing markers are used**. The text is written in its pure form. AI and native speakers automatically determine a word’s status using a three-step algorithm:

**Step 1 — Checking Vowel Harmony**

```
bult      →  U                     →  only back vowels  →  native word
institut  →  I · U · I             →  mixed rows →  loanword
```

**Step 2 — Checking the root structure**

```
bult       →  CVCC   →  Turkic structure ✓
institut   →  -nst- cluster  →  loanword ✓
```

**Step 3 — Suffixation rule**
The suffix is always determined by the **final vowel**:

```
bult       →  final U (back)  →  bultta, bulttar
institut   →  final U (back)  →  institutta, instituttar
```

**Step 4 — The Diphthong Rule (v1.15)**
In native words, vowels that form diphthongs are written explicitly (IY, UW, ÜW). In loanwords, only monophthongs are written (I, U). This serves as an additional marker of a word’s status:

```
suw    →  contains UW  →  native word (Kazakh “water”)
summa  →  contains U   →  loanword
biyik  →  contains IY  →  native word (Kazakh “tall”)
bilet  →  contains I   →  loanword (Kazakh “ticket”)
```

|Feature         |Native word       |Borrowed word       |
|----------------|-------------------|------------------- -|
|Vowel harmony|preserved          |broken            |
|Root structure|CV/CVC/CVCC        |atypical clusters |
|Diphthongs        |IY, UW, ÜW         |only I, U, Ü      |
|Suffix         |based on root vowel|based on final vowel|

### 1a-suppl. Borrowings and “Borrowed” Letters

Several UTL letters exist **primarily for borrowings**—the corresponding sounds are absent or extremely rare in native Turkic words:

|Letter|Sound|Native words                          |History                                                                              |
| -----|----|--------------------------------------|-------------------------------------------------- -----------------------------------|
|**F**|/f/ |not in Kazakh, Kyrgyz           |Originally /p/: *pabrika* → *fabrika*. F became established via Russian                      |
|**V**|/v/ |not in Kazakh (there is /w/)            |Originally /b/ or /w/: *vagon* → Kazakh colloquial *bagon*. V is an Oghuz and borrowed sound|
|**C**|/ts/|not in all Turkic languages except Gagauz|Only in loanwords: *centr*, *policija*, *circus*                               |
|**Ž**|/ʒ/ |not in most Turkic languages            |Only in loanwords: *žurnal*, *režim*. In Kazakh, native Ž = /dʒ/ = J          |


> **UTL Principle:** The alphabet includes all letters necessary for **any** Turkic language in its modern state, including adapted loanwords. Each language uses its own subset (see “Language Profiles”).

> **The degree of adaptation varies by language:**
> 
> |Language       |Approach               |Example “institute”                    |
> |-----------|---------------------|------------------------------------ -|
> |Turkish   |strong adaptation    |*enstitü* (phonetics changed)        |
> |Kazakh   |moderate adaptation  |*institut* (form preserved)         |
> |Uzbek   |minimal adaptation|*institut*                           |
> |Turkmen|strong adaptation    |*institut* (but long vowels are not added)|
> 
> UTL records the **result** of adaptation in a specific language, not the source. The same borrowing can appear differently: Turk. *enstitü*, Kaz. *institut*, Az. *institut*.

### 1b. Assimilation of suffixes based on voicing (Kazakh)

In Kazakh (and Kyrgyz), suffixes have different forms depending on the final sound of the stem:

```
After voiced consonants (B, V, G, Ğ, D, Ž, Z, J, L, M, N, Ŋ, R, Y) and vowels:
  plural: -lar / -ler / -dar / -der
  locative: -da / -de

After voiceless consonants (K, Q, P, T, S, Š, C, Č, F, X):
  plural: -tar / -ter
  locative: -ta / -te
```

Examples:

```
institut  → final sound T (voiceless) → -tar (U=back) → instituttar
universitet → final sound T (voiceless) → -ter (E=front) → universitetter
telefon   → final sound N (voiced) → -dar (O=back) → telefondar
kompjuter → final sound R (voiced) → -ler (E=front) → kompjuterler
```

### 2. Combinations with Y “Й”

|Combination|Sound|Example  |Translation        |
|---------|----|--------|---------------|
|Ya / ya  |/ja/|*yana*  |“is burning”        |
|Ye / ye  |/je/|*yer*   |“place” (dial.)|
|Yi / yi  |/ji/|*yigit* |“hero”       |
|Yo / yo  |/jo/|*yol*   |“road”       |
|Yu / yu  |/ju/|*yurt*  |“yurt”         |
|Yö / yö  |/jø/|*yörgek*|“blanket”       |
|Yü / yü  |/jy/|*yüz*   |“face/hundred”     |
|Yï / yï  |/jɯ/|*yïlqï* |“herd of horses”|

### 2a. Diphthongs (v1.15)

|Diphthong|Sound|Example |Translation  |Language                 |
|-------|----|-------|---------|-------------------- -|
|IY     |/ɪj/|*biyik*|“tall”|Kazakh            |
|UW     |/ʊw/|*suw*  |“water”   |Kazakh            |
|ÜW     |/ʏw/|*küwn* |“day”   |Kazakh            |
|AW     |/aw/|*taw*  |“mountain”   |Kazakh            |
|OW     |/ow/|*tow*  |“gathering”   |Kazakh            |
|ÏY     |/ɯj/|*qïyïn*|“difficult”|Kazakh            |
|AY     |/aj/|*ay*   |“moon”   |Tatar, Bashkir|
|EY     |/ej/|*key*  |“put on”|Tatar            |
|ÖY     |/øj/|*köy*  |“village”|Tatar            |
|ÜY     |/yj/|*küy*  |“melody”|Kazakh, Tatar |


