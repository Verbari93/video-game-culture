# 📋 Quality Standards & Citation Rules

The Cross-Media Pop Culture Archive maintains rigorous standards for academic integrity and factual accuracy. All contributors must follow these guidelines.

---

## 🏷️ Mandatory Metadata Tags

**Every game card MUST include the following tags in the frontmatter to ensure discoverability and consistency across the archive.**

### Required Tags

#### 1. **Genre**
Classify the primary game genre(s). Use standardized values:

```yaml
tags:
  - genre/action-rpg
  - genre/metroidvania
  - genre/puzzle
  - genre/strategy
  - genre/platformer
  - genre/adventure
  - genre/simulation
  - genre/sports
  - genre/rhythm
  - genre/visual-novel
```

**Note:** Include 1-3 primary genres. Use nested slash notation (`genre/subgenre`) for clarity.

#### 2. **Platform Availability**
Document all platforms where the game is available, including ports and remasters:

```yaml
tags:
  - platform/gba        # Original/primary platform
  - platform/ds         # Nintendo DS port
  - platform/steam      # PC port
  - platform/switch     # Nintendo Switch port
  - platform/playstation-5
  - platform/xbox-series-x
  - platform/mobile-ios
  - platform/mobile-android
  - platform/arcade
  - platform/wii
  - platform/ps2
```

**Include:** Every platform the game has been released on. This helps players find versions they can actually play.

#### 3. **Number of Players**
Specify the gameplay mode(s):

```yaml
tags:
  - players/single-player
  - players/multiplayer
  - players/co-op
  - players/local-multiplayer
  - players/online-multiplayer
  - players/competitive
  - players/asynchronous-multiplayer
```

#### 4. **Developer/Publisher Company**
Tag the company that created or published the game:

```yaml
tags:
  - company/konami
  - company/capcom
  - company/nintendo
  - company/square-enix
  - company/sony
  - company/microsoft
  - company/activision
  - company/ubisoft
  - company/bandai-namco
  - company/independent  # For indie games
```

**Note:** Use lowercase with hyphens for multi-word names.

#### 5. **Series/Saga**
Tag the franchise or series the game belongs to:

```yaml
tags:
  - saga/castlevania
  - saga/metroid
  - saga/zelda
  - saga/mega-man
  - saga/final-fantasy
  - saga/resident-evil
  - saga/pokemon
  - saga/mario
  - saga/sonic
  - saga/stand-alone  # For games without series
```

**Note:** Use the official series name. For spin-offs, include both the main series and indicate it's a spin-off in the card body.

### Optional Tags (Contextual)

Add these as relevant:

```yaml
tags:
  - era/8-bit
  - era/16-bit
  - era/32-bit
  - era/64-bit
  - era/3d-renaissance    # Early 3D era
  - era/modern            # Modern gaming era (2015+)
  
  - style/pixel-art
  - style/hand-drawn
  - style/3d-polygonal
  - style/photorealistic
  - style/voxel
  
  - theme/gothic
  - theme/cyberpunk
  - theme/fantasy
  - theme/sci-fi
  - theme/horror
  - theme/noir
  - theme/post-apocalyptic
  - theme/historical
  
  - rating/esrb-e      # E for Everyone
  - rating/esrb-t      # Teen
  - rating/esrb-m      # Mature
  - rating/pegi-3
  - rating/pegi-7
  - rating/pegi-12
  - rating/pegi-16
  - rating/pegi-18
  
  - region/japan        # Clarify region-specific releases
  - region/north-america
  - region/europe
```

### Complete Frontmatter Example

```yaml
---
title: "Castlevania: Aria of Sorrow"
description: >
  A masterpiece Metroidvania by Konami. Soma Cruz explores a gothic castle, 
  collecting souls to gain abilities, influenced by Gothic art and literature.
tags:
  # Genre
  - genre/action-rpg
  - genre/metroidvania
  
  # Platforms
  - platform/gba
  - platform/ds
  - platform/switch
  - platform/mobile-ios
  - platform/mobile-android
  
  # Players
  - players/single-player
  
  # Company
  - company/konami
  
  # Series
  - saga/castlevania
  
  # Optional Context
  - era/32-bit
  - style/hand-drawn
  - theme/gothic
  - theme/horror
  - rating/esrb-m
  - region/japan
  - region/north-america
  - region/europe
---
```

### How Tags Are Used

- **Archive Navigation:** Tags create filterable collections (e.g., "Show all games from Nintendo" or "Show all Metroidvanias")
- **Search Functionality:** Tags improve discoverability (e.g., users can search "platform/switch" to find portable versions)
- **Cross-References:** Related games can be linked via shared tags
- **Quality Control:** Consistent tagging ensures contributors follow a standardized system

### Verification Checklist for Tags

Before submitting a card:

- [ ] At least 1 Genre tag is included
- [ ] All Platform versions are listed (original + ports + remasters)
- [ ] Player mode(s) are specified (single/multi/co-op)
- [ ] Developer/Publisher company is tagged
- [ ] Series/Saga is tagged (or `saga/stand-alone` if applicable)
- [ ] All tags use lowercase with hyphens
- [ ] All tags follow the `category/value` format

---

## 🔗 Rule 1: Mandatory Citations

**Every factual claim must have a clickable reference immediately adjacent to it.**

### ✅ Correct Format

```markdown
The game's soundtrack features [jazz-fusion elements](https://example.com/article), 
which were influenced by [Herbie Hancock's work](https://en.wikipedia.org/wiki/Herbie_Hancock).
```

Or with footnotes:

```markdown
The game was released in 2003[^1], and won multiple awards[^2].

[^1]: Release date: May 5, 2003. Source: [Official Konami Page](https://example.com)
[^2]: Awards received: [GDC Awards Archive](https://example.com)
```

### ❌ Incorrect Format

```markdown
The game's soundtrack features jazz-fusion elements, which were influenced by 
Herbie Hancock's work. [See source](https://example.com)
```
❌ Link is too far from the claim. It's unclear which facts are sourced.

```markdown
The game's soundtrack features jazz-fusion elements influenced by Herbie Hancock.
```
❌ No source at all.

---

## 🤔 Rule 2: Distinguish Speculation from Fact

**All speculation, interpretation, or inference must be explicitly labeled.**

### Categories of Claims

#### A) Verifiable Fact (No label needed)
```markdown
The game was developed by Konami Computer Entertainment Tokyo and released in 2003[^1].

[^1]: [Castlevania: Aria of Sorrow - Wikipedia](https://en.wikipedia.org/wiki/Castlevania:_Aria_of_Sorrow)
```

#### B) Speculation/Interpretation (Requires label)

**Option 1: Direct statement**
```markdown
**Speculation:** The visual design may have been influenced by Giorgio de Chirico's 
painting style, though this connection is not explicitly confirmed by the developers.
```

**Option 2: Cautious language**
```markdown
The castle's architecture appears to echo [M.C. Escher's impossible geometries](https://example.com), 
suggesting possible influence, though no direct reference has been documented.
```

**Option 3: Comparative analysis**
```markdown
Like [Tim Burton's films](https://example.com), the game combines beauty with darkness—
a stylistic parallel that suggests shared aesthetic philosophy, though Burton did not 
directly influence this title.
```

**Option 4: Thematic connection**
```markdown
**Thematic link:** The protagonist's internal conflict mirrors the existential anguish 
depicted in [Egon Schiele's self-portraits](https://example.com). While no direct 
reference has been documented, both works explore psychological disturbance through 
visual distortion.
```

### ❌ Prohibited Patterns

```markdown
The developer was clearly inspired by Kafka.
```
❌ "Clearly" suggests certainty where none exists.

```markdown
The game obviously references Nietzsche's philosophy.
```
❌ "Obviously" is not a source. No citation provided.

```markdown
The artistic style definitely comes from Caravaggio.
```
❌ "Definitely" with no evidence or interview quote.

---

## 🎨 Rule 3: Evidence for Speculative Connections

When you speculate, you MUST provide supporting evidence. This can be:

### Type 1: Direct Quote from Developer/Creator
```markdown
**Confirmed influence:** In an interview, director Koji Igarashi stated: 
"I was deeply influenced by Gothic architecture and the works of M.C. Escher."[^1]

[^1]: [Koji Igarashi Interview - GDC 2003](https://example.com)
```

### Type 2: Artistic/Visual Comparison
```markdown
**Visual parallel:** The castle's non-Euclidean geometry mirrors 
[Escher's "Relative Neighborhood" (1953)](https://example.com/escher-print). 
Both feature stairs connecting impossible spaces.

**Evidence:**
- [Escher print image](https://example.com/image1)
- [In-game screenshot](https://example.com/game-image1)
- [Analysis comparing the two](https://example.com/article)
```

### Type 3: Literary/Thematic Connection with Evidence
```markdown
**Thematic connection:** Soma's journey of self-discovery parallels Goethe's "Faust" (1829).

**Supporting evidence:**
1. Both protagonists gain forbidden knowledge/power
2. Both must choose between corruption and redemption
3. Both feature ambiguous endings leaving moral questions unresolved

**Sources:**
- [Goethe's Faust - Plot summary](https://example.com)
- [Castlevania AoS narrative analysis](https://example.com)
- [Comparative study](https://example.com)

**Note:** This connection has not been officially confirmed by the developers, 
but the structural and thematic parallels are striking.
```

### Type 4: Musical/Compositional Analysis
```markdown
**Musical influence:** The boss theme uses chord progressions typical of jazz-fusion.

**Evidence:**
- **Chord progression:** min7b5 → sus → maj7 (played at 0:45-1:10 in the track)
- **Reference:** [Herbie Hancock - "Maiden Voyage"](https://example.com) uses similar voicings
- **Analysis:** [Jazz harmony primer](https://example.com)

**Speculation:** These compositional choices suggest the composer was influenced by 
1970s jazz fusion, though direct influence has not been documented.
```

---

## 📝 Citation Formats

### Standard Link Format
```markdown
[Link text](URL)
```

### Footnote Format (for multiple references to same source)
```markdown
Some text[^1] and more text[^2].

[^1]: [Source Title](https://example.com)
[^2]: [Another Source](https://example.com)
```

### Long Quotes
```markdown
According to the developer: 

> "The castle was designed as a living organism, not a static structure. 
> Every room connects to another in ways that should feel impossible."[^1]

[^1]: Koji Igarashi, GDC Talk 2003, [Video link](https://example.com)
```

### External References
```markdown
See also: [Full analysis on Shmuplations](https://example.com)
```

---

## 🚫 Citation Red Flags

**Do NOT include citations for:**
- General knowledge (e.g., "The game was released in 2003")
- Well-documented historical facts
- Information available in multiple reliable sources

**DO include citations for:**
- Specific analysis or interpretation
- Claims about influence or inspiration
- Developer statements and interviews
- Academic or critical perspectives
- Specific dates, numbers, or statistics
- Unusual or contested facts

---

## ✅ Verification Checklist

Before submitting a card, verify:

- [ ] Every factual claim has a citation link next to it
- [ ] Every speculation is labeled as such (explicitly or through cautious language)
- [ ] If speculating, supporting evidence is provided (quote, visual comparison, analysis)
- [ ] All links are clickable and functional
- [ ] Developer quotes are attributed with date and source
- [ ] No claims marked as "obvious," "clearly," "definitely" without evidence
- [ ] Tone is academic and balanced
- [ ] Sources are reputable (avoid random blogs; prefer official sources, interviews, academic papers)

---

## 📚 Acceptable Sources

### Tier 1: Highly Reliable (Preferred)
- Official developer interviews (archived on stable sites like Shmuplations)
- Academic papers and journals
- Museum and gallery websites
- Official studios/publishers
- Dedicated game wikis (Fandom, GameFAQs)
- Spotify/Apple Music for soundtracks
- Wikipedia (for historical facts, cross-reference with other sources)

### Tier 2: Reliable (Acceptable)
- Established gaming journalism archives (IGN, GameSpot, Polygon - archival links)
- Art history books and museum catalogs
- Literary analysis from academic sources
- GitHub raw files or permanent repositories
- Archive.org snapshots of important pages
- Streaming platforms for music/soundtracks

### Tier 3: Supplementary (Use with caution)
- Video essays (YouTube, Vimeo) - BUT only for well-known creators with permanent channels
- Fan analyses and wikis (cite as "community observation" not fact)
- Blog posts and essays (acceptable if well-researched, corroborate with other sources)
- Reddit discussions (only if exceptional insight, cite with skepticism)

### Tier 4: Problematic (Avoid or note risk)
- ⚠️ YouTube links (high breakage rate, link often changes)
- ⚠️ Direct social media links (accounts deleted, tweets disappear)
- ⚠️ Personal blogs (may disappear)
- ⚠️ Broken or 404 links

### Tier 5: Not Acceptable
❌ Random blogs without author credentials
❌ Paywalled articles without confirmation
❌ Unverified fan theories presented as fact

---

## 🎯 Examples: Good vs. Bad

### Example 1: Music Analysis

❌ **Bad:**
```markdown
The soundtrack clearly draws from jazz fusion, obviously influenced by Herbie Hancock.
```

✅ **Good:**
```markdown
The soundtrack incorporates jazz-fusion elements, particularly in boss themes. 
The chord progressions and synth-bass arrangements are reminiscent of 
[1970s fusion pioneers like Herbie Hancock](https://example.com/fusion-history), 
suggesting possible influence, though the composer has not explicitly confirmed this.[^1]

[^1]: Composer credits: Masanori Adachi, Michiru Yamane. 
[Original soundtrack liner notes](https://example.com)
```

### Example 2: Artistic Influence

❌ **Bad:**
```markdown
The game's visual style is definitely inspired by Caravaggio's use of light and shadow.
```

✅ **Good:**
```markdown
**Visual parallel:** Like [Caravaggio's paintings](https://example.com/caravaggio-gallery), 
the game employs dramatic chiaroscuro (light/shadow contrast) to create atmosphere. 
The castle's interiors feature strong light sources creating deep shadows.

**Evidence:**
- [Caravaggio: "Judith Beheading Holofernes" (1598)](https://example.com/painting)
- [Game screenshot showing similar lighting](https://example.com/screenshot)

**Note:** While no developer has cited Caravaggio as direct inspiration, 
the visual language is remarkably similar.[^1]

[^1]: [Visual analysis comparing the aesthetics](https://example.com)
```

### Example 3: Narrative Connection

❌ **Bad:**
```markdown
The game is basically about a young man discovering evil power, just like Faust.
```

✅ **Good:**
```markdown
**Thematic connection:** Soma's arc shares structural similarities with 
[Goethe's "Faust" (1829)](https://example.com/faust-summary):

| Element | Faust | Soma |
|---------|-------|------|
| Knowledge of forbidden power | Yes | Yes |
| Temptation/corruption | Yes | Yes |
| Ambiguous moral ending | Yes | Yes |

**Sources:**
- [Faust plot analysis](https://example.com)
- [Castlevania AoS narrative study](https://example.com)

**Speculation:** While this thematic parallel is striking, there is no official 
confirmation that the developers drew from Faust. This observation is based on 
narrative structure comparison.[^1]

[^1]: Community analysis. No official statement from developers has confirmed this influence.
```

---

## 🔄 Revision Process

If a citation is challenged:

1. **Provide the source** with the exact quote or reference
2. **If source is broken**, find an alternative or remove the claim
3. **If claim is unverifiable**, rephrase as speculation with evidence
4. **If no evidence exists**, remove the claim entirely

---

## 📖 For Card Writers

### Before Publishing

1. **Read through your card**
2. **For each factual claim, ask:** "Could someone verify this?"
3. **For each interpretation, ask:** "Did I label this as speculation?"
4. **For each speculation, ask:** "Did I provide supporting evidence?"
5. **Check every link** — click it to verify it works
6. **Ask a peer** to review before submitting

### When in Doubt

Use this template:
```markdown
**[Speculation/Analysis/Theory]:** [Claim here]. 

**Evidence:**
- [Source 1](link)
- [Source 2](link)

**Note:** This has [not been officially confirmed / is based on community observation / 
is my interpretation of the available evidence].
```

---

## 🏆 Quality Tiers for Cards

### Tier 1: Exemplary (Publication-Ready)
- Every claim is cited with working links
- All speculation is labeled and evidenced
- Sources are Tier 1 (official, academic)
- No broken links
- Balanced, academic tone

### Tier 2: Good (Acceptable)
- Most claims are cited
- Speculation is clearly labeled
- Sources are mostly Tier 1-2
- Minimal broken links
- Professional tone

### Tier 3: Acceptable (Needs Work)
- Basic claims are cited
- Some speculation is labeled
- Mix of source tiers
- Some broken links
- Mostly professional tone

### Tier 4: Not Acceptable
- Many uncited claims
- Speculation presented as fact
- Broken or unreliable sources
- Tone is promotional or opinionated
- **Action:** Request revisions before publishing

---

## 📢 Community Standards

All contributors agree to:
- ✅ Cite every factual claim
- ✅ Label all speculation
- ✅ Provide evidence for interpretations
- ✅ Verify all links work
- ✅ Use reputable sources
- ✅ Accept feedback gracefully
- ✅ Correct errors when identified

Violations of these standards will result in:
1. Request for revision
2. If not addressed: Request changes on PR
3. If still unresolved: PR rejection with explanation

---

## 🤝 Questions?

If you're unsure whether something needs a citation, open an Issue and ask the community!

---

**Last updated:** 21/09/2026  
**Status:** Active guideline for all CPCA contributions
