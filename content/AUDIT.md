# Content Audit — Draft v1 → v2

Status key: ✅ confirmed · ⚠️ needs change · ❌ error · 🔎 still to verify by hand

> **Verification note:** The Gurbani databases (BaniDB, SearchGurbani, SriGranth.org)
> could not be reached from the build environment. Ang/author checks below come
> from web search cross-referencing (SikhiWiki Ang pages) plus textual knowledge.
> **Before publishing, every Gurmukhi line must be checked character by character
> against BaniDB / SikhiToTheMax.** Track that in the checklist at the end.

## 1. Gurbani

| # | Line | v1 claim | Finding |
|---|------|----------|---------|
| G1 | ਅਠਸਠਿ ਤੀਰਥ ਸਗਲ ਪੁੰਨ ਜੀਅ ਦਇਆ ਪਰਵਾਨੁ ॥ | Guru Arjan Dev Ji, Ang 136 | ✅ Author/Ang (Barah Maha Majh, ਮਾਘ stanza, Angs 133–136). ⚠️ **Translation is wrong.** v1 makes it conditional ("...are accepted *when* one shows compassion"). In context the stanza says that the one blessed with Naam in the company of the holy has the merit of the 68 pilgrimages, all good deeds, **and** compassion to beings. Compassion is one of the merits listed. It isn't the condition for the others. Fixed in v2; moved out of the hero. |
| G2 | ਦਇਆ ਕਪਾਹ ਸੰਤੋਖੁ ਸੂਤੁ… | Guru Nanak Dev Ji, Ang 471 | ✅ Author/Ang (Asa Ki Vaar, Salok M1). ⚠️ Two translation errors: **ਜਤੁ** means self-restraint/continence, not "modesty". **ਹਈ ਤ ਪਾਡੇ ਘਤੁ** means "O Pandit, if you have such a thread, put it on [me]". It doesn't mean "if you have it, then wear it". Fixed in v2. |
| G3 | ਜਉ ਸਭ ਮਹਿ ਏਕੁ ਖੁਦਾਇ ਕਹਤ ਹਉ ਤਉ ਕਿਉ ਮੁਰਗੀ ਮਾਰੈ ॥੧॥ | Bhagat Kabir Ji, Ang 1375 | ❌ **Wrong Ang.** This line is in Raag Prabhati, Bhagat Kabir Ji, **Ang 1350** (the shabad opening ਬੇਦ ਕਤੇਬ ਕਹਹੁ ਮਤ ਝੂਠੇ…; rahao ਮੁਲਾਂ ਕਹਹੁ ਨਿਆਉ ਖੁਦਾਈ). Ang 1375 has Kabir's saloks (e.g. ਜੋਰੀ ਕੀਏ ਜੁਲਮੁ ਹੈ…), which is probably where the mix-up came from. ⚠️ Context: the shabad is addressed to a Mullah about ritual slaughter. That should be stated so readers aren't misled. |
| G4 | ਸਭਨਾ ਜੀਆ ਕਾ ਇਕੁ ਦਾਤਾ ਸੋ ਮੈ ਵਿਸਰਿ ਨ ਜਾਈ ॥ | Guru Nanak Dev Ji, Ang 2 | ✅ Japji Sahib (Pauris 5 & 6), Ang 2. Translation fine. |

### Framing issues (important for credibility with a Sikh audience)
- ⚠️ **"Ahimsa" is not a Sikh term.** It comes from Jain/Hindu/Buddhist ethics. Use **Daya**, **Sarbat da Bhala**, and **Nirvair** instead, or say clearly that the term is borrowed.
- ⚠️ **Gurbani does not prescribe a vegan diet, and diet is debated within the Panth.** The Sikh Rehat Maryada forbids *kuttha* meat, and traditions such as the AKJ, Namdhari and Damdami Taksal keep vegetarian discipline. Guru Nanak Dev Ji also criticises quarrelling over meat (ਮਾਸੁ ਮਾਸੁ ਕਰਿ ਮੂਰਖੁ ਝਗੜੇ…, Ang 1289 🔎). If the site ignores this, informed readers will dismiss it. v2 has a short, respectful "Our approach" note: the site applies Daya to *today's industrial conditions* and doesn't claim a scriptural mandate.
- ⚠️ **Dairy in Sikh practice.** Karah Prashad is made with ghee, and dairy is traditional in langar. A vegan site for Sikhs has to address this with care. The site must never suggest changing Maryada for Prashad. v2 adds an FAQ placeholder. **Decision needed from you.**

## 2. Dairy section
- ✅ Annual pregnancy is a fair simplification (calving interval is about 12–14 months).
- ✅ Calf separation within 24–48 h is typical in US/UK/EU commercial dairy. Some farms do it within hours.
- ⚠️ **Male calves → veal/beef is Western-specific.** Punjab and most Indian states ban cow slaughter. There, male calves and spent cows are more often abandoned (stray cattle), sold on informally, or trafficked across state lines. Since much of the audience is Punjabi/Indian, v2 covers both contexts.
- ✅ Cull at about 4–6 years against a natural lifespan of roughly 20 years is reasonable. v2 says "around 20 years".

## 3. Environment
- ✅ **14.5%**: FAO, *Tackling Climate Change Through Livestock* (2013).
  ⚠️ FAO's **2023** report *Pathways towards lower emissions* revised this to **~12% (6.2 Gt CO₂e, 2015 base year)** with a new method (GLEAM 3). Cite the newer figure, or give both with years. v2 uses "12–14.5%, depending on FAO estimate".
- ✅ Poore & Nemecek (2018): livestock uses ~83% of farmland and supplies ~18% of calories (and ~37% of protein). Citation details are correct.
- ❌ **Water figures are attributed to the wrong source and mislabelled.** 628 L (dairy) / 28 L (soy) / 48 L (oat) per litre are **freshwater withdrawals** from **Poore & Nemecek (2018)** as charted by Our World in Data. They do not come from the Water Footprint Network. Mekonnen & Hoekstra measure total footprint (green + blue + grey), which is about 1,000 L per litre of milk, a different metric. 🔎 Confirm the exact OWID values (I could not open the chart). Also add almond (~371 L), because the alternatives table mentions almond milk.

## 4. Health & nutrition
- ❌ **Critical omission: Vitamin B12.** Every credible vegan nutrition source (including the AND position paper already cited) says vegans need a reliable B12 source (supplement or fortified foods). This must be on the site. Also mention vitamin D, iodine, and omega-3 (ALA/algal DHA).
- ⚠️ "All 20 amino acids originate in plants" overstates it. More accurate: plants (and microbes) make all the amino acids. Humans must get 9 of them from food, and a varied plant diet supplies all 9.
- ⚠️ "Proven by athletes" for **bone health** is a non sequitur, because an athlete's medal says nothing about bone density. v2 moves athletes to a separate "Plant-powered athletes" panel (inspiration rather than evidence) and supports the nutrition claims with the AND position paper.
- ⚠️ Vitamin K2's role in bone health has mixed evidence. Softened in v2.

### Athletes
| Athlete | Finding |
|---|---|
| **Dotsie** Bausch (v1 spelled "Dotsey") | ✅ Team pursuit silver, London 2012, aged 39; plant-based. Fix spelling. 🔎 year she went plant-based |
| Scott Jurek | ✅ 7 consecutive Western States 100 wins (1999–2005); vegan. |
| Patrik Baboumian | ✅ Strongman with world records (e.g. yoke walk). "Powerlifter" is secondary, so describe him mainly as a strongman. |
| Nimai Delgado | ✅ IFBB Pro, raised vegetarian, never ate meat. 🔎 "vegan since 2015": confirm the year from his own bio. |
| Kendrick Farris | ✅ Vegan since 2014. Set the American record total of 377 kg (168 snatch / 209 C&J) at 94 kg at the 2016 US Olympic Trials, and competed at Rio 2016 (3rd Olympics). v1 said "broke records" (plural) and was vague. v2 is specific. |

## 5. Alternatives table
- ❌ **Agave and maple "rich in antioxidants"**: agave is mostly fructose with negligible antioxidants. All three are added sugars, so v2 removes the health claim.
- ⚠️ Coconut yoghurt is low in protein and high in saturated fat. Recommend soy yoghurt first. "Active probiotics" applies only to cultured products ("live cultures" on the label).
- ⚠️ Ghee → oils is fine. Add **mustard oil** for Punjabi cooking (🔎 erucic-acid guidance differs by country: FDA does not allow it as a cooking oil in the US, but it is standard in India).
- ✅ Soy milk 7–8 g protein per cup, tofu replacing paneer, calcium-set tofu: all fine.

## 6. References
- ✅ Poore & Nemecek 2018, *Science* 360(6392):987–992.
- ✅ Melina, Craig & Levin, AND Position Paper, *J Acad Nutr Diet* 2016;116(12):1970–1980. Add author names.
- ⚠️ FAO: add the 2023 *Pathways towards lower emissions*.
- ⚠️ Water: cite Poore & Nemecek / OWID for the per-litre milk figures. Keep Mekonnen & Hoekstra only if total footprint is quoted.
- ➕ Add: Sikh Rehat Maryada (SGPC), and a Gurbani source (BaniDB / SikhiToTheMax) for each verse.

## Pre-publish checklist
- [ ] Each Gurmukhi line copy-pasted from BaniDB, not retyped
- [ ] Each translation checked against Prof. Sahib Singh (Darpan) and/or Sant Singh Khalsa, with the translation source named on the page
- [ ] Ang 1289 line confirmed (if used)
- [ ] OWID milk water values confirmed
- [ ] Delgado and Bausch dates confirmed
- [ ] Decision on Karah Prashad / Maryada FAQ wording
- [ ] Optional: review by a Gianni / Sikh scholar and a registered dietitian
