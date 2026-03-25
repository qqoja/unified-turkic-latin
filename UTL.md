UTL — Unified Turkic Latin

Version 1.15 | Designed for compatibility with AI systems

Changes in v1.1: added the letter J j for /j/ "Y"; Ž ž replaced J for /ʒ/; removed duplicate İ; corrected examples and correspondence tables. Changes in v1.2: added a rule for borrowings — no ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.002.png)markers, the suffix is determined by the last vowel of the word; added an algorithm for determining borrowings for AI. Changes in v1.3: introduced a two-level architecture UTL-O / UTL-P; corrected conversion rules — native words and borrowings have different diphthongization rules.

Changes in v1.4: Ə ǝ replaced with Ä ä — better tokenization in AI models, familiar from German/Finnish/Swedish corpora, more intuitive for humans. Changes in v1.5: Y y /ɯ/ replaced with ı (i without a dot) — Turkish standard, excellent tokenization, no conflict with Latin Y=/j/. Changes in v1.C: complete transition to gache — Ç→Č, Ş→Š, Ğ→Ǧ; unified diacritics for all modified consonants; Ñ replaced with Ŋ as the basic letter for /ŋ/; Rule 6 added — descending diphthongs AW/OW/EW are written explicitly with W. Changes in v1.7 — five critical fixes:

1. ı → ï — the conflict between capital letters I/ı (Turkish-i problem) has been resolved; capital letters are unambiguous: I=/i/, Ï=/ɯ/.
1. C=/dʒ/ → Ĵ=/dʒ/, C=/ts/ — the voiced affricate has acquired a symmetrical pair ĸ Č; C is freed for /ts/.
1. Ǧ=/ɣ/ → Ğ=/ɣ/ — velar fricative removed from the gache system; breve = weakened velar.
1. C=/ts/ added — the problem of Gagauz and Russian borrowings (center, price, police) has been solved.
1. Ŧ=/θ/, Ð=/ð/ added — Bashkir dental fricatives. Changes in v1.8 — explicit diphthongs in UTL-O:
1. Kazakh, Kyrgyz, Tatar, and Bashkir diphthongs are explicitly written using existing letters: IY /ɪj/, UW /ʊw/, ÜW /ʏw/.
1. The O→P conversion table for diphthongs has been removed — the basic phonemic system is now entirely in UTL-O.
1. UTL-P is retained only for allophonic details (velarization, assimilation, intonation).

U. Extended letters Ĭ/Ŭ are not needed — diphthongs solve the problem of І/И and Ұ/У without new symbols.

10. The text is self-sufficient — it does not require a language tag for correct reading. Changes in v1.9 — corrections:
10. Added the letter Ү (borrowed) → Ü to the table of Kazakh vowels.
10. Corrected errors in examples: *suwrgen* → süwrgen (Ү not У), *güwn* (Kaz.) → küwn (K not G in Kazakh).
10. All examples of Kazakh text have been double-checked and corrected. Changes in v1.10 — checking of all examples:
10. Corrected example I: *il* "year" → *il* "province".
10. Corrected example N: *ner* "thing" → *ne* "what" (Turkic).
16. Corrected example P: *paš* "head" → *pïčaq* "knife".![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.003.png)
16. Corrected example W: removed the mark "ĸaz." from *watan*, added *waqït* "time".
16. Corrected Tatar: *Tuğan* → Tugan (there is no /ɣ/ in this word).

1U. Corrected Turkmen: *söjjärin* → söjärin (single J).

20. Corrected Kazakh: *jaqsï* → žaqsï (Ж=/ʒ/=Ž).
20. Corrected suffixation: *institutter* → instituttar (U=back→-tar); *universitetler* → universitetter (after T→-ter, doubling); *cirkde/cirkler* → cirkte/cirkter (after K→-te/-ter).
20. Clarified example Ŋ: *aŋ* "consciousness/understanding". Changes in v1.11 — revision of language coverage:
20. Chuvash and Yakut removed — isolated branches with zero mutual intelligibility, not in OTS, incomplete phoneme coverage.
20. Karakalpak, Gagauz, and Crimean Tatar have been added — fully covered, high mutual intelligibility, use the Latin alphabet.
20. Extended letters Ź, Ĺ (Yakut) retained as reserves, Ħ (Uyghur) retained.
20. Justification C=/ts/ changed: not a Chuvash phoneme, but preservation of information in borrowings.
20. Languages are grouped by branches: Oghuz, Kipchak, Karluk. Changes in v1.12 — two-level language coverage:
20. UTL (basic, 16 languages) and UTL-Extended (extended, 8+ languages) have been introduced. 2U. UTL: three branches of common Turkic languages — Oghuz (4), Kipchak (U), Karluk (2) + 1 mixed.
30. UTL-Extended: Siberian (Yakut, Tuvan, Khakas, Altai, Shor, Dolgan), Bulgarian (Chuvash), archaic Oghuz (Salar).
30. Nogai, Karachay-Balkar, and Kumyk have been added to UTL.
30. Extended letters are distributed: Ŧ/Ð (Bashkir) and Ħ (Uyghur) — UTL; Ź/Ĺ — UTL-Extended. Changes in v1.13 — comparative analysis and accumulated corrections:
30. Added section "Comparison with other projects" — CTA 2024, Kazakh 2021, Uzbek 1UU5/2023, Turkmen 1UUU, Zamanälif, ULY, etc.
30. Karon instead of "gachek" in the description of diacritics + technical note about Ĵ (circumflex U+0134).
30. ASCII collision Ng vs N+G — documented in the ASCII mode description.
30. Clarified: Kumyk uses V (not W) — Oghuz influence.
30. The note "(kir.)" has been removed from Kazakh in the correspondence table. Changes in v1.14 — J/Y redistribution, diphthongs, apostrophe:
30. Y=/j/, J=/dʒ/ — marginal Ĵ removed; Y=/j/ coincides with CTA, Turkish, and all Turkic Latin alphabets; J=/dʒ/ coincides with the English association.

3U. Ĵ removed, Y added → 35 basic letters (number unchanged: Ĵ→Y replacement).

40. Diphthongs: IJ→IY, ÏJ→ÏY (J replaced with Y as a semivowel).
40. ASCII: Ï → I’ (the apostrophe marks /ɯ/). Without the apostrophe — I (context and vowel harmony allow

    ~U5% of cases).![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.004.png)

42. Note on diphthongs UW/ÜW — weak glide, not a full semivowel.
42. The apostrophe for /ʔ/ is removed — a marginal phoneme in Arabic borrowings, not recorded in UTL.
42. Definition of glides — explanation of the nature of Y and W as semivowels (glide).
42. Symmetry of Kazakh vowels — І/Й/И ↔ Ұ/У̯/У, justification through Baitursynov's theory (5 supporting + 4 allophones + 2 semivowels).
42. Conversion table Cyrillic→UTL — rule for Kazakh: И→IY, У→UW, Ү→ÜW in native words; И→I, У→U, Ү→Ü in loanwords.
42. Historical precedents — Baku alphabet 1U28 (v=У/w/), rule 1U38 (ю=и+у), Batmanov 1U3U (Kyrgyz long vowels), Yrk Bitig (a/ä, ı/i).
42. Exact IPA values of diphthongs — IY /ɪj/ (was /ij/), UW /ʊw/ (was /uw/).

4U. Ġ removed from the extended alphabet → 3 extended (Ŧ, Ð, Ħ). /ɢ/ — dialectal variant, not a phoneme.

50. ASCII: Ï → I’ (apostrophe). The only letter requiring a marker. Apostrophe in ASCII = technical character (marker Ï and digraph separator), not a UTL letter.
50. Long vowels — expanded section: Turkmen (U long, minimal pairs), Kyrgyz (6 long, Batmanov 1U3U), Uyghur (long in Arabisms). Doubling = phonemic length. Discrepancies with Turkmen Latin script are documented.
50. Diphthongs are expanded — Tatar and Bashkir diphthongs (AY, EY, ÖY, ÜY) are added. Summary of diphthongs by language.
50. Language profiles — a section for each of the 16 languages: used/unused letters, diphthongs, long vowels, extended vowels. Summary table. Changes in v1.15 — language profiles, long vowels, borrowings:
50. Language profiles — a section for each of the 16 languages: letters, W/V, diphthongs, long vowels, extended vowels. Summary table.
50. Long vowels are extended — Turkmen (U pairs with minimal pairs), Kyrgyz (6 pairs), Uyghur (Arabicisms). Discrepancy with Turkmen Latin script.
50. Diphthongs are extended — Tatar/Bashkir AY, EY, ÖY, ÜY. Summary by language.
50. Uyghur long vowels — *aalam*, *kaatip* (Arabicisms, doubling).
50. Borrowed letters — explanation of F, V, C, Ž as letters for borrowings. Degree of adaptation by language. 5U. Historical precedents — Baku 1U28, rule 1U38, Batmanov 1U3U, Yrk Bitig.
60. ASCII: Ï → I’ — two-level ASCII (minimum/exact). Ħ→Hh added.
60. Ġ removed → 3 extended (Ŧ, Ð, Ħ).
60. Removed section "Summary of all changes v1.6→v1.15" (duplicated changelog).
60. Corrections: Ï ASCII Y→I’, ĸыпчаĸсĸих table, ÜW=front row, *qarra→anna*, *su* (Turkish).

Development principles![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.005.png)

UTL was created with five key requirements in mind:

1. Phonetic completeness — two-level coverage of Turkic languages:
- UTL (basic) — 16 languages of the three main branches:
  - *Oghuz:* Turkish, Azerbaijani, Turkmen, Gagauz
  - *Kipchak:* Kazakh, Kyrgyz, Karakalpak, Nogai, Karachay-Balkar, Kumyk, Tatar, Bashkir, Crimean Tatar
  - *Karlukskie:* Uzbek, Uyghur
  - UTL-Extended — Siberian, Bulgarian, and archaic Turkic languages (Yakut, Tuvan, Khakas, Altai, Chuvash, etc.)
2. AI-optimality — minimum diacriticism, maximum tokenizability; each sound — a predictable symbol.
2. Uniformity — one sound = one letter in all languages without exception.
2. ASCII compatibility — each letter has a unique ASCII equivalent for use in LLM prompts and databases.
2. Two-level architecture — UTL-O for humans (phonemic transcription), UTL-P for AI (allophonic details, generated automatically).![ref1]

UTL v1.15 diacritics system

Four types of diacritics — four types of modification. Each is predictable:

Caron (ˇ) = sibilant fricative or affricate: Š Ž Č Breve (˘) = weakened velar: Ğ

Diaeresis (¨) = modified vowel: Ö Ü Ä Ï

Dash (-) = dental fricative: Ŧ Đ (extended)![ref2]

UTL v1.15 diphthong system

Glides (semi-vowels)

Glide (glide, semivowel) — a sound that "slides" from the position of one vowel to another. Glides are an intermediate class between vowels and consonants: they are similar to vowels in terms of articulation, but function like consonants — they do not form a syllable on their own, but serve the neighboring vowel.

There are two glides in UTL:

Y /j/ — palatal glide: the tongue slides from/to the position /i/ W /w/ — labial glide: the lips slide from/to the position /u/

Symmetry of Kazakh vowels in UTL

Kazakh I and U are not simple vowels, but diphthongs (vowel + glide). UTL makes this structure explicit:

І /ɪ/ → I (pure vowel) ↔ Ұ /ʊ/ → U (pure vowel)

Й /j/ → Y (glide) ↔ У /w/ → W (glide)

И /ɪj/ → IY (vowel + glide) ↔ U /ʊw/ → UW (vowel + glide)

Similarly for the front row: Ү /ʏw/ → ÜW (vowel Ü + glide W).

Theoretical basis (A. Baitursynov): The founder of Kazakh grammar, A. Baitursynov, identified five basic ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.008.png)vowels (A, O, Ұ, Ы, E), four allophones (Ə, Ө, Ү, І), and two semivowels (У, Й). In this classification, І and У are not vowels, but semivowels (diphthongs). The pure vowels are І and Ұ. Identities: ǝ = a + e, ө = o + e, ү 

- ұ + e, і = ы + e. The UTL system accurately reproduces this structure: І = I + Y, У = U + W, while І and Ұ are written with a single letter (I and U).

Conversion rule Cyrillic → UTL (Kazakh)

In native Kazakh words, И, У, Ү are always diphthongs. In loanwords, they are monophthongs. Without exceptions:



|Cyrillic|Native word|Borrowed word|
| - | - | - |
|І|I (always)|—|
|I|IY|I|
|Y|Ï (always)|—|
|Ұ|U (always)|—|
|U|UW|U|
|Ү|ÜW|Ü|

Examples: *bit* "louse" → biyt (native, И=IY); *institute* → institut (borrowing, И=I); *su* "water" → suw (native, UW=UW); *bus* → avtobus (borrowing, U=U).

Historical precedents

The UTL diphthongoid system is not an innovation — it has direct parallels in the history of the Turkic Latin alphabet:

The 1928 alphabet (Baku, unified Turkic): In the Kazakh variant of the Latin alphabet adopted at the Baku Conference in 1928, the letter v denoted the semivowel У /w/, y denoted Ы /ɯ/, and i denoted І /ɪ/. Principle: У is not a vowel, but a semivowel written with a separate consonant letter.

Rule of 1938 (Kazakh Latin alphabet): The Russian letter ю in borrowings was written as ĸaĸ and+у (*iuвilei*, *soiuz*, *kaiuta*) — direct confirmation that И and У were treated as combinations, not monophthongs.

Kyrgyz grammar (Batmanov, 1939): The Kyrgyz language has 14 vowel phonemes — 8 short (a, e, o, ɵ, ɨ, i, u, y) and 6 long (aa, ee, oo, ɵɵ, uu, yy). Long vowels are written with double letters — UTL supports this principle. Short vowels in Kyrgyz are 3–5 times shorter than in Russian, which explains the diphthongal pronunciation.

Ancient Turkic (Yrq Bitig, ~X century): Runic writing already distinguished between back/front pairs: a/ä, ı/i, o/ö, u/ü — the foundation of the UTL vowel system. Garkavets' transcription uses the symbols ŋ, ğ, š, ä, which coincide with UTL.

Diphthongs

Two glides — Y and W — serve all diphthongs without new letters:

Y marks palatal glide: IY /ɪj/ (front), ÏY /ɯj/ (back)

W marks labial glide: UW /ʊw/ (back), ÜW /ʏw/ (front), AW /aw/ (back), oW /ow/ Diphthongs are written explicitly in UTL-O. The text is self-sufficient without a language tag.

Rule for diphthongs in native words and borrowings![ref3]



|Context|Sound|UTL-O|Example|
| - | - | - | - |
|Native word, diphthong|/ɪj/|IY|*biyik* "tall"|
|Native word, diphthong|/ʊw/|UW|*suw* "water"|
|Native word, diphthong|/ʏw/|ÜW|*küwn* "day" (Kaz.)|
|Native word, diphthong|/aw/|AW|*taw* "mountain"|
|Borrowing, monophthong|/i/|I|*institut*|
|Borrowing, monophthong|/u/|U|*universitet*|
|Any context, monophthong|/ɪ/|I|*bil* "know" (Kaz.)|
|Any context, monophthong|/ʊ/|U|*bul* "this" (Kaz.)|

Language coverage: UTL and UTL-Extended

UTL (basic) — 1C languages

Common Turkic languages of the three main branches. Mutual intelligibility is non-zero, phonemes are fully covered by the basic alphabet (35 letters) and extended letters Ŧ/Ð/Ħ.

Oghuz (southwestern) — 4 languages



|Language|Speakers|Writing|OTS|
| - | - | - | - |
|Turkish|~80 million|Latin|✓|
|Azerbaijani|~30 million|Latin|✓|
|Turkmen|~7 million|Latin|observer|
|Gagauz|~150,000|Latin|—|

Kypchak (northwestern) — 9 languages



|Language|Subgroup|Speakers|Writing|OTS|
| - | - | - | - | - |
|Kazakh|Nogai|~13 million|transition to Latin|✓|
|Karakalpak|Nogai|~700 thousand|Latin|via Uzbek|
|Nogai|Nogaiskaya|~U0 thousand|Cyrillic|—|
|Kyrgyz|Kypchak-Polovtsian|~5 million|Cyrillic|✓|
|Karachay-Balkar|Kipchak-Polovtsian|~300 thousand|Cyrillic|—|
|Kumyk|Kipchak-Polovtsian|~500 thousand|Cyrillic|—|
|Tatar|Volga|~5 million|Cyrillic|—|
|Bashkir|Povolzhskaya|~1.2 million|Cyrillic|—|
|Crimean Tatar|Kypchak-Oguz|~500 thousand|Latin|—|

*Note:* Despite belonging to the Kipchak branch, Kumyk is strongly influenced by Oghuz and uses V /v/ (not W ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.010.png)/w/) for labials, like Turkish and Azerbaijani.

Karluk (southeastern) — 2 languages



|Language|Speakers|Writing|OTS|
| - | - | - | - |
|Uzbek|~30 million|Latin|✓|
|Uyghur|~12 million|Arabic / Latin|—|

![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.011.png) Total UTL: ~186 million speakers, coverage: 35 basic letters + 3 extended letters (Ŧ, Ð, Ħ).![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.012.png)

UTL-Extended — 8+ languages

Isolated branches of Turkic languages with zero or minimal mutual intelligibility with UTL languages. Require additional letters and rules. Supported through reserve letters and language-specific extensions.

Siberian Turkic languages — C languages



|Language|Speakers|Branch|Unique needs|
| - | - | - | - |
|Yakut (Sakha)|~450,000|Siberian|/ðʲ/ → Ź, /lʲ/ → Ĺ, diphthongs uo/ie/үө|
|Tuvan|~280,000|Siberian|pharyngealization, long vowels|
|Khakass|~40 thousand|Siberian|palatal affricates|
|Altai|~55 thousand|Siberian|/dʲ/, /tʲ/|
|Shor|~2,500|Siberian|Khakass|

Dolgan ~1 thousand Siberian (Yakut) Yakut ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.013.png)Bulgarian branch — 1 language



|Language|Speakers|Unique needs|
| - | - | - |
|Chuvash|~1 million|/ts/ phoneme, Ă /ǝ̆/, Ĕ /ɘ̆/ — reduced vowels|

Archaic Oghuz languages — 1+ languages



|Language|Speakers|Unique needs|
| - | - | - |
|Salarski|~70,000|Archaic Oghuz, influence of Tibetan/Chinese|

Total UTL-Extended: ~1.U million speakers. Reserve letters: Ź, Ĺ. Additional letters are determined when developing a specific language profile.![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.014.png)![ref4]

UTL alphabet — complete table

Vowels (9 letters)



|UTL|IPA|Row|Labialization|Examples|ASCII|
| - | - | - | - | - | - |
|A a|/a/|back|none|*at* "horse", *ana* "mother"|A a|
|E e|/e/|front|none|*el* "hand", *er* "man"|E e|
|I i|/i/|front|none|*ip* "rope," *il "*province"|I i|
|Ï ï|/ɯ/|back|none|*qïz* "girl", *yïl* "year"|I’ i’|
|O o|/o/|back|yes|*on* "ten", *ot* "grass"|O o|
|U u|/u/|back|yes|*un* "muka", *bul* "this" (Kaz.)|U u|
|Ö ö|/ø/|front|yes|*öz* "self," *köz* "eye"|Oe oe|
|Ü ü|/y/|front|yes|*üč* "three", *gün "*day"|Ue ue|
|Ä ä|/æ/|front|none|*äl* (Azerbaijani) "hand", *äkin* "sowing"|Ae ae|

Note for AI — vowel harmony:![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.016.png)

- Back row: A, Ï, O, U → suffixes with back vowels
- Front row: E, I, Ö, Ü, Ä → suffixes with front vowels Example: *kitap* + 

locative → *kitapta* (A-row) / *ev* + locative → *evde* (E-row)![ref5]

Four key differences: И / Й / Ы / У



|Russian sound|IPA|UTL|Type|Examples|
| - | - | - | - | - |
|I|/i/|I i|vowel, front|*ip* "rope", *bil* "know"|
|Ы|/ɯ/|Ï ï|vowel, back|*qïz* "girl", *yïl* "year"|
|Y|/j/|Y y|consonant semivowel|*yol* "road," *ay* "moon"|
|U|/u/|U u|vowel, back|*bul* "this", *un* "muka"|

For AI: Y always = /j/ as in Turkish *yol*, German *ja*. J always = /dʒ/ as in English *judge*. Ž = /ʒ/ as in ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.018.png)*measure*.

Capital letters are unambiguous:![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.019.png)

- I — always capitalized from i (/i/)
- Ï — always capitalized from ï (/ɯ/)
- The Turkish-i problem has been completely eliminated.![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.020.png)

Consonants (2C letters)



|UTL|IPA|Sound|Examples|ASCII|
| - | - | - | - | - |
|B b|/b/|voiced labial|*bar* "to eat", *bala "*child"|B b|
|C c|/ts/|voiceless dental affricate|*centr* "center", *policija* "police" (borrowed)|C c|
|Č č|/tʃ/|voiceless sibilant affricate|*čaj* "tea", *čöl* "desert"|Ch ch|
|D d|/d/|voiced dental|*dağ* "mountain", *dil* "tongue"|D d|
|F f|/f/|voiceless labiodental|*fikir* "idea," *fal* "fortune telling"|F f|
|G g|/ɡ/|voiced velar|*gel* "come," *göz* "eye"|G g|
|Ğ ğ|/ɣ/|voiced velar fricative|*dağ* "mountain", *ağa* "elder"|Gh gh|
|H h|/h/|voiceless glottal|*hava* "air", *han* "khan"|H h|
|X x|/x/|voiceless velar fricative|*xalq* "people", *xan* "khan"|Kh kh|
|Y y|/j/|palatal semivowel "Y"|*yol* "road", *ay "*moon"|Y y|
|J j|/dʒ/|voiced sibilant affricate|*jan* "soul", *jahan* "world"|J j|
|Ž ž|/ʒ/|voiced sibilant fricative|*žurnal* "magazine" (borrowed)|Zh zh|
|K k|/k/|voiceless velar|*kel* "come," *köl* "lake"|K k|
|Q q|/q/|voiceless uvular|*qala* "fortress", *qan* "blood"|Q q|
||||||


|L l|/l~ɫ/|lateral (soft/hard)|*lale* "tulip", *el* "hand"|L l|
| - | - | - | - | - |
|M m|/m/|nasal labial|*men* "I", *mal* "property"|M m|
|N n|/n/|nasal dental|*nan* "bread", *ne* "what"|N n|
|Ŋ ŋ|/ŋ/|velar nasal|*köŋül* "soul", *aŋ* "consciousness"|Ng ng|
|P p|/p/|voiceless labial|*pul* "money", *pïčaq* "knife"|P p|
|R r|/r/|vibrating alveolar|*yer* "place", *yurt* "yurt"|R r|
|S s|/s/|voiceless dental fricative|*su* "water" (Turkish), *söz* "word"|S s|
|Š š|/ʃ/|voiceless sibilant|*šan* "glory", *baš* "head"|Sh sh|
|T t|/t/|voiceless dental|*taš* "stone", *til* "tongue"|T t|
|V v|/v/|voiced labiodental|*var* "is," *vaqt "*time"|V v|
|W w|/w/|labiovelar semivowel|*watan* "homeland" (Turkmen), *taw* "mountain" (Kazakh)|W w|
|Z z|/z/|voiced dental fricative|*yaz* "summer/write", *söz* "word"|Z z|

Extended letters![ref6]

UTL — for languages of basic coverage



|UTL|MFA|Language|Sound|ASCII|
| - | - | - | - | - |
|Ŧ ŧ|/θ/|Bashkir|voiceless dental fricative|Th th|
|Ð đ|/ð/|Bashkir|voiced dental fricative|Dh dh|
|Ħ ħ|/ħ/|Uyghur|pharyngeal fricative|Hh hh|

UTL-Extended — for Siberian and isolated languages![ref4]



|UTL|IPA|Sound|ASCII|
| - | - | - | - |
|Ź ź|/ðʲ/|soft dental fricative|Dy dy|
|Ĺ ĺ|/lʲ/|palatalized L|Ly ly|

Complete alphabetical order UTL v1.15

A B C Č D E Ä F G Ğ H I Ï J K L M N Ŋ O Ö P Q R S Š T U Ü V W X Y Z Ž *(35 basic + 3 extended UTL + 2 extended UTL-Extended)![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.022.png)*

Kazakh vowels in UTL-O — complete table![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.023.png)



|Kazakh|Context|Sound|UTL-O|Type|
| - | - | - | - | - |
|A|always|/a/|A|monophthong|
|Ә|always|/æ/|Ä|monophthong|
|E|always|/e/|E|monophthong|
|І|always|/ɪ/|I|ĸratĸi monophthong|
|I|cognate|/ɪj/|IY|diphthong|
|I|borrowing|/i/|I|monophthong|
|Ы|always|/ɯ/|Ï|monophthong|
|O|always|/o/|O|monophthong|
|Ө|always|/ø/|Ö|monophthong|
|Ұ|always|/ʊ/|U|ĸratĸiy monophthong|
|U|cognate|/ʊw/|UW|diphthong|
|U|borrowing|/u/|U|monophthong|
|Ү|native word|/ʏw/|ÜW|diphthong|
|Ү|borrowing|/y/|Ü|monophthong|

Table of correspondences with existing alphabets



|Sound|IPA|UTL|Turkish|Azerbaijani|Kazakh|Uzbek|Uyghur (Latin)|
| - | - | - | - | - | - | - | :- |
|I|/i/|I|i|i|І|i|i|
|Ы|/ɯ/|Ï|ı|ı|Ы|—|—|
|Y|/j/|Y|y|y|Y|y|y|
|U|/u/|U|u|u|Ұ|u|u|
|Dift. IJ|/ɪj/|IY|—|—|I|—|—|
|Diphth ong. UV|/ʊw/|UW|—|—|U|—|—|
|Dift. ҮВ|/ʏw/|ÜW|—|—|Ү|—|—|
|||||||||


|Dift. AU|/aw/|AW|—|—|AU|—|—|
| - | - | - | - | - | - | - | - |
|Ю|/ju/|Yu|yu|yu|Yu|yu|yu|
|I|/ja/|Ya|ya|ya|I|ya|ya|
|E/Ä|/æ/|Ä|—|ǝ|Ә|—|é|
|Ö|/ø/|Ö|ö|ö|Ө|oʻ|ö|
|Ü|/y/|Ü|ü|ü|—|—|ü|
|Ч|/tʃ/|Č|ç|ç|Ч|ch|ch|
|J|/dʒ/|J|c|c|J|j|j|
|C|/ts/|C|—|—|Ц (borrowed)|—|—|
|Ш|/ʃ/|Š|ş|ş|Ш|sh|sh|
|Ж|/ʒ/|Ž|—|j|Ж|j (borrowed)|zh|
|X friĸ.|/x/|X|—|x|X|x|x|
|Ғ|/ɣ/|Ğ|ğ|ğ|Ғ|gʻ|gh|
|Қ|/q/|Q|—|q|Қ|q|q|
|Ң|/ŋ/|Ŋ|—|—|Ң|ng|ng|
|Х g|/h/|H|h|h|X (weak)|h|h|
|Ҫ (Bashkir)|/θ/|Ŧ|—|—|—|—|—|
|Ҙ (Bashkir)|/ð/|Ð|—|—|—|—|—|

Symmetry of the phonological system UTL v1.15![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.024.png)

Fricatives

Dental Sibilants Velars Voiceless: S /s/ Š /ʃ/ X /x/ Voiced: Z /z/ Ž /ʒ/ Ğ /ɣ/

Affricates

Dental Sibilants Voiceless: C /ts/ Č /tʃ/

Voiced: — J /dʒ/

Bashkir dental fricatives (extended)

Interdental Voiceless: Ŧ /θ/ Loud: Đ /ð/

Explosive and uvular

Velars Uvular Voiceless: K /k/ Q /q/ Voiced: G /ɡ/

Diphthongs (v1.15)

Palatal (Y-glide): IY /ɪj/ (front), ÏY /ɯj/ (back)

Labial (W-glide): UW /ʊw/ (back), ÜW /ʏw/ (front), AW /aw/ (back), oW /ow/ (back)![ref3]

UTL spelling rules

1. Vowel harmony

Suffixes agree with the root in a series of vowels:

Back row: A Ï o U → suffix -da / -lar / -dan / -lï Front row: E I Ö Ü Ä → suffix -de / -ler / -den / -li

In diphthongs, harmony is determined by the vowel part: AW, UW = back; ÜW = front; IY = front.

1a. Borrowings — last vowel rule

No borrowing markers are used in UTL. The text is written cleanly. AI and native speakers determine the status of a word automatically using a three-step algorithm:

Step 1 — Checking vowel harmony

bult → U → only back vowels → native word institut → I · U · I → mixed rows → borrowing

Step 2 — Checking the root structure

bult → CVCC → Turkic structure ✓ institut → cluster -nst- → borrowing ✓

Step 3 — Suffixation rule The suffix is always determined by the last vowel:

bult → last U (back) → bultta, bulttar

institut → last U (back) → institutta, instituttar

Step 4 — Diphthong rule (v1.15) In native words, diphthongized vowels are written explicitly (IY, UW, ÜW). In loanwords, only monophthongs (I, U) are used. This is an additional marker of word status:

suw → contains UW → native word (Kazakh "water") summa → contains U → borrowing

biyik → contains IY → native word (Kazakh "high") bilet → contains I → borrowing (Kazakh "bilet")



|Recognition|Native word|Borrowing|
| - | - | - |
|Vowel harmony|observed|violated|
|Root structure|CV/CVC/CVCC|Atypical clusters|
|Diphthongs|IY, UW, ÜW|only I, U, Ü|
|Suffix|by root vowel|by last vowel|

1a-add. Borrowings and "borrowed" letters

Several UTL letters exist primarily for borrowings — in native Turkic words, the corresponding sounds are absent or extremely rare:



|Letter|Sound|Native words|History|
| - | - | - | - |
|F|/f/|Not found in Kazakh or Kyrgyz|Originally /p/: *pabrika* → *fabrika*. F became established through Russian|
|V|/v/|not in Kazakh (there is /w/)|Originally /b/ or /w/: *wagon* → Kazakh colloquial *bagon*. V — Oghuz and borrowed sound|
|C|/ts/|Not found in any Turkic languages except Gagauz|Only in borrowings: *centr*, *policija*, *circus*|
|Ž|/ʒ/|Not present in most Turkic languages|Only in loanwords: *žurnal*, *režim*. In Kazakh, native Ж = /dʒ/ = J|

UTL principle: the alphabet includes all letters necessary for any Turkic language in its modern state, ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.025.png)including adapted borrowings. Each language uses its own subset (see "Language profiles").

The degree of adaptation varies depending on the language:



|Language|Approach|Example "institute"|
| - | - | - |
|Turkish|Strong adaptation|*enstitü* (changed phonetics)|
|Kazakh|moderate adaptation|*institut* (form retained)|
|Uzbek|minimal adaptation|*institut*|
|Turkmen|strong adaptation|*institut* (but long vowels are not added)|

UTL records the result of adaptation in a specific language, not the source. The same borrowing can look different: Turk. ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.026.png)![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.027.png)*enstitü*, Kaz. *institut*, Az. *institut*.

1b. Assimilation of suffixes according to voicing (Kazakh)

In Kazakh (and Kyrgyz), suffixes have variants depending on the last sound of the base:

After voiced consonants (B, V, G, Ğ, D, Ž, Z, J, L, M, N, Ŋ, R, Y) 

and vowels: plural: -lar / -ler / -dar / -der

locative: -da / -de

After unvoiced consonants (K, Q, P, T, S, Š, C, Č, F, X):

plural: -tar / -ter

locative: -ta / -te

Examples:

institut → last sound T (voiceless) → -tar (U=back) → instituttar universitet → last sound T (voiceless) → -ter (E=front) → universitetter telefon → last sound N (voiced) → -dar (o=back) → telefondar kompjuter → last sound R (voiced) → -ler (E=front) → kompjuterler

2. Combinations with Y "Й"



|Combination|Sound|Example|Translation|
| - | - | - | - |
|Ya / ya|/ja/|*yana*|"burns"|
|Ye / ye|/je/|*yer*|"place" (dialect)|
|Yi / yi|/ji/|*yigit*|"dzhigit"|
|Yo / yo|/jo/|*yol*|"road"|
|Yu / yu|/ju/|*yurt*|"yurt"|
|Yö / yö|/jø/|*yörgek*|"blanket"|
|Yü / yü|/jy/|*yüz*|"face/hundred"|
|Yï / yï|/jɯ/|*yïlqï*|"herd of horses"|

2a. Diphthongs (v1.15)



|Diphthong|Sound|Example|Translation|Language|
| - | - | - | - | - |
|IY|/ɪj/|*biyik*|"tall"|Kazakh|
|UW|/ʊw/|*suw*|"water"|Kazakh|
|ÜW|/ʏw/|*küwn*|"day"|Kazakh|
|AW|/aw/|*taw*|"mountain"|Kazakh|



|OW|/ow/|*tow*|"gathering"|Kazakh|
| - | - | - | - | - |
|ÏY|/ɯj/|*qïyïn*|"difficult"|Kazakh|
|AY|/aj/|*ay*|"moon"|Tatar, Bashkir|
|EY|/ej/|*key*|"put on"|Tatar|
|ÖY|/øj/|*köy*|"village"|Tatar|
|ÜY|/yj/|*küy*|"melody"|Kazakh, Tatar|

Diphthongs by language:![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.028.png)

- Kazakh, Kyrgyz, Karakalpak: full set — IY, UW, ÜW, AW, OW, ÏY, AY, ÜY
- Tatar, Bashkir: descending diphthongs with Y — AY, EY, ÖY, ÜY, ÏY; with W — AW, ÄW
- Oghuz (Turkish, Azerbaijani, Turkmen): no diphthongs (monophthongs)
- Uzbek: no diphthongs in the literary language

For AI — diphthong rule:![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.029.png)

- Y after a vowel = descending diphthong (palatal glide)
- W after a vowel = descending diphthong (labial glide)
- Y and W at the beginning of a word before a vowel = consonants /j/ and /w/
3. Gemination

Long consonants — doubling: *katta* "big" (Uzbek), *anna* "mother" (Kazakh colloquial)

4. Glottal stop

The glottal stop /ʔ/ (Arabic ﻉ) is a marginal phoneme found only in Arabic loanwords (Uzbek, Uyghur). It is not recorded in UTL: *malum* "famous", *talim* "education". In colloquial speech, /ʔ/ is usually not pronounced. If phonetic accuracy is required, the UTL-P level is used.

5. Long vowels

Vowel length is phonemic (distinguishes words) in Turkmen and Kyrgyz. UTL records length by doubling the vowel letter:

Turkmen — 9 long vowels

In Turkmen, each short vowel has a long counterpart. Length distinguishes between words:



|Short|Long|Minimal pair|
| - | - | - |
|a /a/|aa /aː/|*at* "horse" ↔ *aat* "name"|
|e /e/|ee /eː/|*el* "hand" ↔ *eel* "edge"|
|i /i/|ii /iː/|*bil* "know" ↔ *biil* "waist"|



|o /o/|oo /oː/|*gol* "hand" ↔ *gool* "lake"|
| - | - | - |
|u /u/|uu /uː/|*gul* "slave" ↔ *guul* "flower"|
|ö /ø/|öö /øː/|*öl* "wet" ↔ *ööl* "die"|
|ü /y/|üü /yː/|*gün* "day" ↔ *güün* "sun"|
|ä /æ/|ää /æː/|*är* "man" ↔ *äär* "morning"|
|ï /ɯ/|ïï /ɯː/|— (redĸo)|

Difference from Turkmen Latin script: In the official Turkmen Latin script (1UUU), length is encoded in separate ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.030.png)letters: *a* = /aː/ (long), *ä* = /æ/ and simultaneously short /a/. In UTL, length is explicitly written by doubling: *a* = /a/ (short), *aa* = /aː/ (long). The UTL principle: letter = quality phoneme, doubling = length. This is more unambiguous and universal.

Kyrgyz — C long vowels

Kyrgyz has 14 vowel phonemes: 8 short and 6 long (Batmanov, 1U3U). Long vowels are written with a double letter:

aa /aː/ ee /eː/ oo /oː/ öö /øː/ uu /uː/ üü /yː/

Examples: *at* "horse" ↔ *aat* "name"; *tuu* "to give birth" ↔ *tu* "banner".

Note: Short vowels in Kyrgyz are 3–5 times shorter than in Russian (Batmanov, 1U3U), which makes the contrast between short and long vowels particularly noticeable.![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.031.png)

Kazakh — no long vowels

In the Kazakh literary language, vowel length is not phonemic. Doubling is not used.

Uyghur — long in Arabicisms

In Uyghur, long vowels are found in borrowings from Arabic and Persian. Length distinguishes words:

aalam /aːlam/ "world" ↔ alam /alam/ "pain" kaatip /kaːtip/ "scribe" ↔ katip /katip/ (none) taariix /taːriːx/ "history"

UTL records this with a doubling: *aalam*, *kaatip*, *taariix*. The same principle applies to Turkmen and Kyrgyz. Other languages

In Turkish, Azerbaijani, Uzbek, Tatar, and Bashkir, vowel length is not phonemic and is not recorded in UTL.

C. The letter W — three positional functions



|Position|W =|Example|Translation|
| - | - | - | - |
|Beginning of a word (before a vowel)|/w/ consonant|*watan* "homeland" (Turkmen), *waqït* "time" (Kazakh)|Turkmen, Kazakh|



|After vowels A, O|/aw/, /ow/ diphthong|*taw* "mountain", *žaw* "enemy"|Kazakh|
| - | - | - | - |
|After the vowels U, Ü|/ʊw/, /ʏw/ diphthong|*suw* "water", *küwn* "day"|Kazakh|

7\. Letter Y — two positional functions



|Position|Y =|Example|Translation|
| - | - | - | - |
|Beginning of word / before vowel|/j/ consonant|*yol* "road", *yurt* "yurt"|all languages|
|After vowel I, Ï|/ɪj/, /ɯj/ diphthong|*biyik* "tall", *qïyïn* "difficult"|Kazakh|

Note on diphthongs: W in the diphthongs UW/ÜW is realized as a weak glide (diphthong), rather than a full ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.032.png)semivowel /w/ as at the beginning of the word (*waqït*). Kazakh *suw* sounds closer to [sʊ] with a slight labialization at the end. Y in the diphthongs IY sounds more distinct. UTL phonological notation: the distinctive function (native/borrowed) is more important than accurate phonetics.![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.033.png)

Language profiles UTL v1.15

UTL is a single alphabet of 35 letters. Each language uses a subset of this alphabet plus its own features (diphthongs, long vowels, extended letters).

Oghuz languages

Turkish



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü|
|Not used|Ä (no /æ/), W (no /w/, V is used instead), C (no /ts/), Q (no /q/), X (no /x/), Ŋ (no /ŋ/)|
|Diphthongs|none|
|Long vowels|none|
|Extended letters|No|
|Note|The most "compact" profile — 2U letters out of 35|

Azerbaijani



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü, Ä|
|Not used|W (V is used), C (no /ts/)|



|Diphthongs|none|
| - | - |
|Long vowels|None|
|Extended letters|No|
|Note|Ä=/æ/ (corresponds to Azerbaijani Ə), Q and X are active|

Turkmen



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü, Ä|
|All 35 letters|are active (W=/w/ in *watan*)|
|Diphthongs|none|
|Long vowels|yes — U pairs: aa, ee, ii, ïï, oo, öö, uu, üü, ää|
|Extended letters|No|
|Note|The only Oghuz language with W and long vowels|

Gagauz



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü, Ä|
|Not used|W (V is used), Q (no /q/), X (no /x/)|
|Diphthongs|none|
|Long vowels|none|
|Extended letters|No|
|Note|C=/ts/ active (Gagauz phoneme)|

Kypchak languages

Kazakh



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü, Ä|
|Not used|V (W is used), F (only in loanwords), C (only in loanwords)|
|Diphthongs|IY, UW, ÜW, AW, OW, ÏY, AY, ÜY|
|Long vowels|none|
|||


|Extended letters|none|
| - | - |
|Note|Full set of diphthongs. W instead of V. Q, Ğ, Ŋ, X are active|

Kyrgyz



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü|
|Not used|Ä (not /æ/), V (used as W), F (only in loanwords)|
|Diphthongs|Kak Kazakh|
|Long vowels|yes — 6 pairs: aa, ee, oo, öö, uu, üü|
|Extended letters|none|
|Note|Diphthongs + long vowels simultaneously|

Karakalpak



|Parameter|Value|
| - | - |
|Profile|close to Kazakh|
|Diphthongs|yes (Kazakh)|
|Long vowels|none|
|Note|W instead of V|

Tatar



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, Ï, O, Ö, U, Ü, Ä|
|Not used|Q (no /q/), W (V is used)|
|Diphthongs|AY, EY, ÖY, ÜY, ÏY, AW, ÄW|
|Long vowels|none|
|Extended letters|No|
|Note|Diphthongs with Y; V instead of W; Ğ active|

Bashkir

Parameter Value![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.034.png)

Profile Tatar + extended



|Diphthongs|yes (Tatar)|
| - | - |
|Long vowels|none|
|Extended letters|Ŧ /θ/, Ð /ð/|
|Note|The only UTL language with interdental sounds|

Crimean Tatar



|Parameter|Value|
| - | - |
|Profile|Oguz-Kipchak, close to Turkish|
|Diphthongs|none (Oghuz type)|
|Long vowels|none|
|Extended letters|none|
|Note|Q, X, Ŋ are active (Kipchak substrate)|

Nogai, Karachay-Balkar, Kumyk



|Parameter|Nogai|Karachay-Balkar|Kumyk|
| - | - | - | - |
|Profile|Kazakh type|Kazakh type|Oguz influence|
|Diphthongs|yes|yes|no|
|W/V|W|W|V (Oguz influence)|
|Q, Ŋ|active|active|active|

Karluksk languages

Uzbek



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, O, U, Ö|
|Not used|Ï (no /ɯ/), Ü (no /y/), Ä (no /æ/), W (V is used)|
|Diphthongs|none|
|Long vowels|none|
|Extended letters|No|
|Note|The "poorest" vowel system among UTL languages — 6 vowels|

Uyghur



|Parameter|Value|
| - | - |
|Vowels used|A, E, I, O, Ö, U, Ü, Ä|
|Not used|Ï (no /ɯ/), W (V is used)|
|Diphthongs|none|
|Long vowels|Yes — in Arabicisms: aa, ii, etc.|
|Extended letters|Ħ /ħ/|
|Note|The only UTL language with a pharyngeal|

Summary table of features![ref3]



|Language|Letter|W/V|Diphthongs|Long|Exp.|
| - | - | - | - | - | - |
|Turkish|2U|V|—|—|—|
|Azerbaijani|31|V|—|—|—|
|Turkmen|35|W|—|9 pairs|—|
|Gagauz|30|V|—|—|—|
|Kazakh|32|W|full|—|—|
|Kyrgyz|31|W|full|C steam|—|
|Karakalpak|32|W|full|—|—|
|Tatar|32|V|AY/EY/ÖY|—|—|
|Bashkir|32|V|AY/EY/ÖY|—|Ŧ Ð|
|Crimean Tatar|31|V|—|—|—|
|Nogaiskiy|32|W|yes|—|—|
|K.-Balkarsky|32|W|yes|—|—|
|Kumyski|31|V|—|—|—|
|Uzbek|28|V|—|—|—|
|Uyghur|31|V|—|Arabic|Ħ|

Two-level architecture UTL-O / UTL-P (v1.15)

UTL-O — Orthographic level (for humans)

Phonemic transcription. Diphthongs are explicit. The text is self-sufficient:

Turkish: su gün bir vatan enstitü Kazakh: suw küwn bir otan institut Kyrgyz: suw küwn bir meken institut Uzbek: su gün bir vatan institut

Differences between languages are real phonological differences, not artifacts of notation. Kazakh *suw* and Turkish *su* are different phonological structures (diphthongoid vs. monophthong), even if the acoustic difference in isolation is minimal.

UTL-P — Phonetic level (for AI)

Generated automatically from UTL-O + language tag. Contains only allophonic details not covered by UTL-O:

- Velarization of L in back syllables
- Assimilation of voicing at the junction of morphemes
- Aspiration of plosives
- Intonation markup for TTS
- Dialect variation

Basic phonemic system — completely in UTL-O. UTL-P is no longer needed for diphthongs.

Analogues in other systems

Pinyin: tones are written in the main text (ā á ǎ à)

- not hidden in a separate layer

Serbian Latin: all phonemes are explicit (dž, lj, 

nj)

- does not require a language tag

UTL v1.15: all phonemes are explicit (IY, UW, ÜW)

- does not require a language tag![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.035.png)

ASCII mode UTL v1.15



|UTL|ASCII|UTL|ASCII|
| - | - | - | - |
|Č č|Ch ch|Ö ö|Oe oe|
|Š š|Sh sh|Ü ü|Ue ue|
|Ğ ğ|Gh gh|Ä ä|Ae ae|
|X x|Kh kh|Ï ï|I’ i’|
|Ž ž|Zh zh|Ŋ ŋ|Ng ng|
|J j|J j|Y y|Y y|
|||||


|C c|C c|Q q|Q q|
| - | - | - | - |
|Ŧ ŧ|Th th|Ð đ|Dh dh|
|Ħ ħ|Hh hh|||
Example: *Biyik tawlar* → ASCII: Biyik tawlar (no changes — pure ASCII) Example: *Türkçe söz* → ASCII: Tuerkche soez Example: *Jahan* → ASCII: Jahan Example: *qïz* → ASCII: qi’z (apostrophe marks Ï)

Note about Ï in ASCII: Ï=/ɯ/ is written as ĸаĸ I’ (I + apostrophe). ASCII mode has two levels:![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.036.png)

- Minimum ASCII: Ï → I (without apostrophe). Context (Q/K) and vowel harmony allow ~U5% cases. Suitable for fast typing and SMS.
- Exact ASCII: Ï → I’ (with an apostrophe). 100% uniqueness. Suitable for databases and AI processing.

All other diacritical letters are resolved through digraphs (Š→Sh, Č→Ch) or combinations (Ö→Oe, Ü→Ue, Ä→Ae) at both levels.

Note on collisions: the digraph Ng (for Ŋ=/ŋ/) can theoretically coincide with the sequence N+G (/n/+/ɡ/) in borrowings (e.g., ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.037.png)*ingredient*). In practice, the combination /n/+/ɡ/ is extremely rare in Turkic texts — in native words, /ŋ/ precedes /ɡ/, not /n/. If necessary, use a separator: *in’gredient* (apostrophe). A similar collision Kh (for X=/x/) is practically non-existent — /k/+/h/ is not characteristic of Turkic languages.

The role of the apostrophe in ASCII mode: the apostrophe is not a UTL character and is not used in UTL-O (Unicode). In ASCII mode, it performs two technical functions: (1) marker Ï = I'; (2) separator of digraphs in rare collisions. The apostrophe does not cause any problems for AI processing—it is a standard character in all corpora.![ref1]

Special features for AI systems

Tokenization

Diacritics are limited to the letters: Č, Š, Ğ, Ö, Ü, Ä, Ï, Ž, Ŋ. All are known to BPE tokenizers. The diphthongs IY, UW, ÜW, AW are combinations of basic ASCII letters, ideal for tokenization.

Principles of uniqueness



|Principle|Status|
| - | - |
|One sound = one letter|✓ 100|
|One letter = one sound|✓ U8% (W and Y are position-dependent)|
|No silent letters|✓|
|No digraphs in the base|✓ (IY/UW are not digraphs, but two sounds)|
|Uniform consonant diacritics|✓ ĸарон=sibilants, breve=velar, stroke=dental|
|Unambiguous capital letters|✓ 100% (Turkish-i problem fixed)|
|Text is self-sufficient|✓ (does not require a language tag for reading)|

![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.038.png)

Morphological transparency

Q-a-z-a-q-s-t-a-n - d-a - ğ-ï - l-a-r - d-a-n [toponym] -[loc] -[adj]-[pl]-[ex]

- "of those who are in Kazakhstan"

Phoneme index (for embedding space)![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.039.png)



|No|Phoneme|UTL|No|Phoneme|UTL|
| - | - | - | - | - | - |
|01|/a/|A|1U|/l/|L|
|02|/e/|E|20|/m/|M|
|03|/i/|I|21|/n/|N|
|04|/ɯ/|Ï|22|/ŋ/|Ŋ|
|05|/o/|O|23|/p/|P|
|06|/u/|U|24|/q/|Q|
|07|/ø/|Ö|25|/r/|R|
|08|/y/|Ü|26|/s/|S|
|0U|/æ/|Ä|27|/ʃ/|Š|
|10|/b/|B|28|/t/|T|
|11|/ts/|C|2U|/v/|V|
|12|/tʃ/|Č|30|/w/|W|
|13|/d/|D|31|/x/|X|
|14|/dʒ/|J|32|/j/|Y|
|15|/f/|F|33|/z/|Z|
|16|/ɡ/|G|34|/ʒ/|Ž|
|17|/ɣ/|Ğ|35|/k/|K|
|18|/h/|H||||
Examples of texts in UTL v1.15

Kazakh — "Kazakhstan is my homeland"

Cyrillic: Kazakhstan — my homeland. This is where my

my ancestors lived. The nature of our country is beautiful. The high mountains and vast plains fill my heart with joy.

I love my country.

UTL-o: Kazakhstan is my homeland. My ancestors 

lived here. Our country

tabiyğatï öte ädemi. Biyik tawlar, keŋ dalanïŋ körki — bäri de žüwregimdi toltïradï.

I see my own hands.

ASCII: Kazakhstan is my homeland. My ancestors 

lived here. Our country's

is beautiful. The high mountains, the vast plains — everything is beautiful.

I love my homeland.

Note: In the ASCII example, the exact level (I' for Ï) is used. In minimal ASCII, it is permissible to write without an apostrophe: ![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.040.png)*Otanim*, *tabiyghati* — ĸontekst (back Q, Gh) and vowel harmony allow

~U5% of cases.

Keyword analysis (v1.15)



|Cyrillic|UTL-O|Why taĸ|
| - | - | - |
|B|bul|Ұ=/ʊ/ → U (monophthong)|
|sürgen|süwrgen|Ү=/ʏw/ → ÜW (diphthong)|
|Biik|biyik|I=/ɪj/ → IY, І=/ɪ/ → I|
|taular|tawlar|AU=/aw/ → AW (diphthong)|
|zhuregimdi|žüwregimdi|Ү=/ʏw/ → ÜW (diphthong)|
|meniң|meniŋ|І=/ɪ/ → I, Ң=/ŋ/ → Ŋ|
|жақсы|žaqsï|Ж=/ʒ/ → Ž, Қ=/q/ → Q, Ы=/ɯ/ → Ï|
|kөremin|köremin|І=/ɪ/ → I|
|елімді|elimdi|І=/ɪ/ → I|
|University|Universitet|U (borrowed) = /u/ → U (monophthong)|

"I love my homeland" — all languages



|Language|UTL-O|
| - | - |
|Turkish|*Vatanïmï seviyorum*|
|Azerbaijani|*Vätänimi seviräm*|
|Kazakh|*Otanïmdï žaqsï köremin*|
|||


|Uzbek|*I love my homeland*|
| - | - |
|Tatar|*My native land*|
|Kyrgyz|*Mekenimi jakšï köröm*|
|Turkmen|*Watanïmï söyärin*|
|Bashkir|*Vatanïmdï yaratam*|

Borrowings — examples of suffixation



|Word|UTL-O|Last vowel|Locative|Plural|
| - | - | - | - | - |
|облаĸо|*bult*|U (back)|*bultta*|*bulttar*|
|institute|*institut*|U (rear)|*institutta*|*instituttar*|
|university|*universitet*|E (front)|*university*|*universitetter*|
|telephone|*telefon*|O (back)|*telefonda*|*telefondar*|
|ĸompyuter|*kompjuter*|E (front)|*computer*|*computers*|
|center|*center*|E (front)|*center*|*centrler*|
|police|*policija*|A (rear)|*police*|*policijalar*|

Bashkir — extended letters

ŧal "gray- (cf. sal "raft" — minimal pair)

haired"

đur "big" (cf. zur in Tatar)

Agglutination with analysis

Turkish - Czech - Les - Tir - E - Me - Dik - Ler - Imiz - Den

│ │ │ │ │ │ │ │ │ └─ nominative 

case

│ │ │ │ │ │ │ │ └──────── 1st person 

plural present indicative

│ │ │ │ │ │ │ └────────────── past participle │ │ │ │ │ │ └───────────────────── -dik suffix

│ │ │ │ │ └────────────────────────── denial

│ │ │ │ └────────────────────────────── potential

│ │ │ └────────────────────────────────── causative

│ │ └──────────────────────────────────────── denominative

│ └───────────────────────────────────────── language/style └─────────────────────────────────────────────────── "Turk"

- "from what we could not Turkify"![ref2]

Comparison with other Turkic Latin alphabets

Overview of existing projects



|Project|Status|Letters|Year|Features|
| - | - | - | - | - |
|CTA 2024|Official OTS|34|2024|İ/I, Y=/j/, C=/dʒ/, Ñ=/ŋ/, Ç/Ş (sedil)|
|Kazakh 2021|offic.|31|2021|Y=/ɯ/, Ñ=/ŋ/, Ş (sedil), Ū=/ʊ/ (macron)|
|Uzbek 1995|offic.|2U|1UU5|pure ASCII, digraphs sh/ch/ng/oʻ/gʻ|
|Uzbek 2023|project|2U|2023|C=/tʃ/, Ş, Ğ, Õ — movement ĸ diacritics|
|Turkmen 1999|offic.|30|1UUU|Ž=/ʒ/ (karon!), Ň=/ŋ/, J=/dʒ/, Ä=/æ/|
|Azerbaijani|offic.|32|1UU1|Ə=/æ/, İ/I, C=/dʒ/, J=/ʒ/, X=/x/|
|Zamanälif-2 (Tat.)|unofficial|34|2012|İ/I, Ñ=/ŋ/, Ç/Ş (cedilla), W=/w/|
|Crimean Tatar|semi-official|31|1UU7|close to Turkish/CTA|
|Gagauz|officer.|31|1UU6|Ţ=/ts/ (T-sedil), İ/I|
|ULY (Uyghur)|auxiliary.|32|2001|pure ASCII, digraphs ch/gh/ng/sh/zh|
|Yañalif (hist.)|hist.|33|1U28|Ƣ=/ɣ/, special characters, first Turkic Latin|
|UTL v1.15|project|35+3|2025|Y=/j/, J=/dʒ/, Ï=/ɯ/, Ŋ, ĸaron, explicit diphthongs|

Key discrepancies and solutions UTL

1. Turkish-i problem (İ/I vs I/Ï)



|Approach|Used|Problem|
| - | - | - |
|İ=/i/, I=/ɯ/|CTA, Turkish, Azerbaijani, Zamanälif|toLowerCase("İ") = a bug in thousands of programs|
|I=/i/, Ï=/ɯ/|UTL|no problem — standard Unicode|
|Y=/ɯ/, I=/i/|Kazakh 2021|Y is associated with /j/ in the global corpus|

UTL solution: Ï with a diaeresis — the only option without the Turkish-i problem and without incorrect associations.

2. Letter C — "battlefield"



|Project|C=|/dʒ/=|/tʃ/=|/ts/=|
| - | - | - | - | - |
|CTA 2024|/dʒ/|C|Ç|—|
|Uzbek 2023|/tʃ/|—|C|—|
|Turkish|/dʒ/|C|Ç|—|
|Turkmen|—|J|Ç|—|
|UTL|/ts/|J|Č|C|

UTL solution: Each sound is a unique letter. No conflicts. C=/ts/ — the least controversial meaning

(only needed for borrowings).

3. Velar nasal /ŋ/



|Approach|Used|
| - | - |
|Ñ (tilde)|CTA, Kazakh 2021, Crimean Tatar, Zamanälif|
|Ň (ĸaron on N)|Turkmen|
|Ŋ (IPA)|UTL|
|ng (digraph)|Uzbek, Karakalpak, ULY|

UTL decision: Ŋ — IPA symbol, unambiguous, easily transliterated (Afrikaans languages).

4. Sibilants: sedil vs ĸaron



|Approach|/ʃ/|/tʃ/|/ʒ/|Used|
| - | - | - | - | - |
|Sedil (¸)|Ş|Ç|—|CTA, Turkish, Azerbaijani, Kazakh|
|Karon (ˇ)|Š|Č|Ž|UTL, Turkmen (Ž)|
|Digraphs|sh|ch|zh|Uzbek 1UU5, ULY|

UTL solution: ĸaron — a single system for all sibilants. Turkmen already uses Ž with ĸaron, which confirms the viability of this approach.

5. Kazakh diphthongs: UTL vs CTA 2024



|Problem|CTA 2024|Kazakh 2021|UTL|
| - | - | - | - |
|/ʊ/ vs /ʊw/|Ū (macron)|Ū|U vs UW|
|/ɪ/ vs /ɪj/|—|—|I vs IY|
|/ʏw/|—|—|ÜW|

UTL solution: explicit diphthongs IY/UW/ÜW instead of new letters — the text is self-sufficient without a language tag. CTA only resolves /ʊ/ through Ū, but does not distinguish between monophthongs and diphthongs.

C. Semivowel /j/



|Approach|/j/=|Used|
| - | - | - |
|Y|CTA, Turkish, Azerbaijani, Uzbek, Turkmen, UTL|all|

UTL v1.15 solution: Y=/j/ — matches all Turkish Latin characters. J=/dʒ/ — matches the English association. Ĵ has been removed as a marginal character.

Final comparison



|Criterion|CTA 2024|Kazakh 2021|Uzbek|UTL v1.15|
| - | - | - | - | - |
|Turkish-i problem|yes|no (Y=/ɯ/)|no (no / ɯ/)|no|
|Unified diacritics|<p>no</p><p>(cedilla + breve)</p>|<p>no</p><p>(cedilla + macron + breve)</p>|no (digraphs)|yes (ĸaron+breve+dieresis+stroke)|
|Clear diphthongs|none|no|no|yes|
|Self-sufficient text|No (tag required)|No|yes (own alphabet)|Yes|
|ASCII compatibility|partial|partial|full|full|
|AI optimization|average|average|high|High|
|Compatibility Y=/j/|✓|✗ (Y=/ɯ/)|✓|✓|
|Language coverage|6 (OTS)|1 (Kazakh)|1 (Uzbek)|1C|

Compatibility with CTA 2024![ref5]



|CTA 2024|UTL v1.15|Note|
| - | - | - |
|A|A|matches|
|B|B|matches|
|C|J|CTA: C=/dʒ/, UTL: J=/dʒ/|
|Ç|Č|sedil → ĸaron|
|D|D|coincides|
|E|E|matches|
|Ə|Ä|sva → diaeresis|
|F|F|coincides|
|G|G|matches|
|Ğ|Ğ|matches|
|H|H|matches|
|I|Ï|CTA: I=/ɯ/, UTL: Ï=/ɯ/|
|İ|I|CTA: İ=/i/, UTL: I=/i/|
||||


|J|Ž|CTA: J=/ʒ/, UTL: Ž=/ʒ/|
| - | - | - |
|K|K|coincides|
|L|L|matches|
|M|M|matches|
|N|N|matches|
|Ñ|Ŋ|tilde → IPA symbol|
|O|O|coincides|
|Ö|Ö|matches|
|P|P|matches|
|Q|Q|matches|
|R|R|matches|
|S|S|matches|
|Ş|Š|sedil → ĸaron|
|T|T|coincides|
|U|U|coincides|
|Ū|—|UTL does not use; /ʊ/ through U, diphthong through UW|
|Ü|Ü|coincides|
|V|V|matches|
|X|X|matches|
|Y|Y|match: Y=/j/|
|Z|Z|matches|
|—|W|UTL adds|
|—|C /ts/|UTL adds|

Recommendations for implementation![](Aspose.Words.0e35ee6c-3383-424d-a96a-b3de1f5ce922.041.png)

For AI developers: UTF-8 with a full set of UTL; ASCII mode for legacy systems; diphthongs IY/UW/ÜW — a reliable marker of native Turkish words during classification. UTL covers 16 languages (~186 million speakers) of three branches: Oghuz, Kipchak, and Karluk. UTL-Extended adds Siberian and isolated branches.

For linguists: UTL is an interlingual scientific notation and the basis for panlingual NLP models. UTL-Extended extends coverage to isolated branches (Bulgarian, Siberian) through additional letters and

language profiles.

For education: ASCII mode — for the initial level; full UTL — for academic writing and digital communication.

CTA 2024 ↔ UTL v1.15 conversion: fully automatic, unambiguous in both directions (see the compatibility table).![ref6]

*UTL v1.15 is an open standard for discussion by the Turkic community and AI researchers.*
