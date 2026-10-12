# Verification Checklist

## Editorial rules
1. Every factual claim has an **inline citation** right in the sentence, e.g. "(Poore & Nemecek, *Science*, 2018)", linked to the source, plus a full entry in the Sources list. Where it reads naturally, name the source in the sentence itself ("Health Canada recommends…").
2. No mention of any existing religious or community practice.
3. Informational tone only: describe, don't prescribe or judge.
4. Gurmukhi is **copy-pasted** from BaniDB / SikhiToTheMax, never retyped.
5. Health content carries the "not medical advice" note.
6. If a claim can't be traced to a credible source, it is removed, not softened.

## How v4 was verified (Oct 2026)
Every claim in `content/website-content.md` was checked with web searches that
returned the source, or quoted text from it. The build environment couldn't open
web pages directly, so a person should click each link once before launch to make
sure it loads and says what we say. Work through the list below.

### Corrections made in v4
- **Male calves:** the "Frontiers in Animal Science 2022" paper studied **US** farms (Ohio and Indiana), not Canada. It was replaced by Canadian sources: NFAHW Council 2019, Renaud et al. 2017, and Lactanet.
- **Ang 663:** "ਸਭ ਮਹਿ ਜੋਤਿ ਜੋਤਿ ਹੈ ਸੋਇ" is now cited as Ang 663 (Raag Dhanasari Aarti), confirmed via Darpan 663. Ang 13 couldn't be confirmed.
- **Japji, Ang 2:** "ਸਭਨਾ ਜੀਆ ਕਾ ਇਕੁ ਦਾਤਾ…" is now labelled Japji **Pauri 5**.
- **Ang 469:** "ਬਲਿਹਾਰੀ ਕੁਦਰਤਿ ਵਸਿਆ" was removed because no source confirmed its Ang.
- **Ardas:** the reference to Ardas was removed because it couldn't be confirmed against the SGPC text.
- **Removed as unconfirmed:**
  - "no need to combine proteins at every meal"
  - "the Code of Practice permits separation"
  - "31% of Holsteins reach 4th calving" (the document is undated)
  - "about half of calves are male" (replaced by the Lactanet beef-semen figures)
  - "Canadian winters make sunlight unreliable"
  - "the world's largest organization of nutrition professionals"
  - the per-cup and per-tbsp nutrition numbers
  - the coconut yoghurt and cashew cream claims
  - the bok choy, broccoli, tahini, almond, chia and fig calcium list
  - the dry peas claim
  - the almond and rice columns and the water row in the milk table (sources disagreed)
- **Reworded to match the source:**
  - Tong 2019 now says "coronary heart disease"; the 20% stroke figure is total stroke.
  - Vitamin D advice applies at age 51+.
  - Lactanet calving age and interval are now given as medians.

## v5 changes (from reviewer feedback, Oct 2026)
- BC SPCA dairy page (reported as "page not found") replaced by Montreal SPCA, Alberta Milk, Canadian Food Focus and a Government of BC farm-practices guide.
- Journal articles now link to their DOI or PubMed record: Beaver 2019, Meagher 2019, Renaud 2017, Feskanich 2014 and De Vries & Marcondes 2020.
- The Lactanet benchmark PDF and Van Doormaal 2003 (no link) were removed. The calving cycle now cites the BC government, and artificial insemination cites The Canadian Encyclopedia.
- "Herds remove about 30% of cows a year" was removed because the cited DFC PDF didn't support it. The figure is now AAFC's official 27.9% (2024).
- The US-only longevity figure was replaced by a peer-reviewed review (De Vries & Marcondes 2020: 3–4 years of productive life in high-producing dairy countries). No Canada-specific average lifespan figure was found. AAFC's annual culling rate is the Canadian data point.
- PDFs that remain in Page 3 are from official bodies: the NFAHW Council, Dairy Farmers of Canada and the Government of BC.

## Sources that are secondary (worth replacing with the primary source if possible)
| Claim | Current source | Primary source to check |
|---|---|---|
| Agriculture = 7.9% of Canada's emissions (2023) | The Advocate (news) | ECCC National Inventory Report 2025 |
| Milk table values | Ethical Consumer, quoting OWID | ourworldindata.org/environmental-impact-milks |
| Ghee ≈ 60% saturated fat | Mirror of USDA FDC 171314 | fdc.nal.usda.gov, FDC 171314 |
| Tofu 17.3 g protein / 1.3 g sat fat / 683 mg Ca | Mirror of USDA FDC 172475 | fdc.nal.usda.gov, FDC 172475 |
| Canola ≈ 7% saturated fat | Canola Council 2016 release (industry body) | Canadian Nutrient File |
| Nimai Delgado details | Rich Roll podcast page | his own interview or site |
| Scott Jurek wins | Wikipedia | Western States results page |
| Native bees > 800 species | Nature Conservancy of Canada story map | a Government of Canada species list |
| Natural lifespan up to ~20 years | INRAE paper citing De Vries & Marcondes | full text of De Vries & Marcondes (2020) |
| Most producers use AI | The Canadian Encyclopedia (may be dated) | AAFC CDIC current AI report |

## Gurbani (copy from BaniDB, confirm Ang and author)
| Line | Ang | Status |
|---|---|---|
| ਧੌਲੁ ਧਰਮੁ ਦਇਆ ਕਾ ਪੂਤੁ ॥ | 3 (Japji, Pauri 16) | confirmed via web ☐ BaniDB copy |
| ਦਇਆ ਕਪਾਹ ਸੰਤੋਖੁ ਸੂਤੁ… | 471 (Asa Ki Vaar) | confirmed via web ☐ BaniDB copy |
| ਸਭ ਮਹਿ ਜੋਤਿ ਜੋਤਿ ਹੈ ਸੋਇ ॥ | 663 (Dhanasari Aarti) | confirmed via web ☐ BaniDB copy |
| ਸਭਨਾ ਜੀਆ ਕਾ ਇਕੁ ਦਾਤਾ… | 2 (Japji, Pauri 5) | confirmed via web ☐ BaniDB copy |
| ਜਉ ਸਭ ਮਹਿ ਏਕੁ ਖੁਦਾਇ… | 1350 (Prabhati, Bhagat Kabir Ji) | confirmed via web ☐ BaniDB copy |
| ਭੈ ਕਾਹੂ ਕਉ ਦੇਤ ਨਹਿ… | 1427 (Salok M9) | partly confirmed (section spans 1426–1429) ☐ BaniDB check |
| ਪਵਣੁ ਗੁਰੂ ਪਾਣੀ ਪਿਤਾ… | 8 (Japji, Salok) | confirmed via web ☐ BaniDB copy |
| Translation source chosen and credited | — | ☐ |

## Before launch
- [ ] Click every link in the Sources list and confirm it loads and supports the sentence
- [ ] Replace the secondary sources above where possible
- [ ] Gurmukhi copied from BaniDB; translation source credited
- [ ] Review by a Giani / Sikh scholar (Gurbani)
- [ ] Review by a registered dietitian (health pages)
