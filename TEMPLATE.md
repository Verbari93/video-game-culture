---
title: "[Game Title]"
description: >
  [1-2 sentence description of the game and its cultural significance.
  This is displayed in search results and listings.]
cover: /video-game-culture/static/covers/[game-slug].jpg
releaseDate: [YYYY-MM-DD]
tags:
  # Genre (Required: at least 1)
  - genre/[primary-genre]
  - genre/[secondary-genre]

  # Platform Availability (Required: all platforms)
  - platform/[original-platform]
  - platform/[port-platform]
  # Common values: gba, ds, ps2, ps5, xbox-series-x, switch, steam, arcade, mobile-ios, mobile-android

  # Number of Players (Required)
  - players/single-player
  # OR: players/multiplayer, players/co-op, players/local-multiplayer, players/online-multiplayer

  # Company (Required: developer or publisher)
  - company/[studio-name]
  # Common values: konami, capcom, nintendo, sony, square-enix, independent

  # Series/Saga (Required)
  - saga/[series-name]
  # OR: saga/stand-alone if no series

  # Optional Tags (Use as relevant)
  - era/[8-bit|16-bit|32-bit|64-bit|3d-renaissance|modern]
  - style/[pixel-art|hand-drawn|3d-polygonal|photorealistic]
  - theme/[gothic|cyberpunk|fantasy|sci-fi|horror|noir|post-apocalyptic]
  - rating/[esrb-e|esrb-t|esrb-m|pegi-3|pegi-7|pegi-12|pegi-16|pegi-18]
  - region/[japan|north-america|europe|worldwide]
---

# [Game Title] ([YEAR])

> **Developer:** [Studio Name]  
> **Director:** [Director Name]  
> **Original Platform:** [Platform]  
> **Genre:** [Genre] | [Secondary Genre]  
> **Rating:** [ESRB/PEGI Rating]

> [!note] 📌 Synopsis
> [1-3 sentence summary of the game and its cultural significance. This should be a compelling overview.]

---

## 📌 Synopsis

[Expanded description of the game. Context about the series, gameplay mechanics, narrative themes, and why it matters culturally.]

## 📖 Books, Essays & Novels

<details open>
<summary><b>📚 Novels and Tie-In Media</b></summary>

* **Title:** Author
  * Description of how the book relates to the game

</details>

<details open>
<summary><b>✍️ Critical & Analytical Essays</b></summary>

* **"Title":** Author/Publisher
  * **Focus:** Critical or analytical aspect covered
  * **Link:** [URL]

</details>

---

## 📽️ Video Essays & Documentaries

<details open>
<summary><b>🎬 Analytical Videos</b></summary>

* **"Title"** - Creator/Channel
  * Platform: YouTube/Vimeo/etc
  * Duration: ~[XX] minutes
  * Topic: What the video covers

</details>

---

## 📰 Historical Interviews & Post-Mortems

<details open>
<summary><b>🎤 Key Interviews</b></summary>

* **"Title"** (Year)
  * Interviewee: Creator/Designer
  * Medium: Interview archive/publication
  * Topic: Main theme or quotes

</details>

---

## 🎨 Artistic References & Cross-Media Inspirations

<details open>
<summary><b>🖼️ Visual Arts</b></summary>

* **Artist - "Work Title"**
  * **Connection:** How the work influences the game's design
  * **Notes:** Specific visual or thematic parallels

</details>

<details open>
<summary><b>🏛️ Architecture & Spatial Design</b></summary>

* **Architect/Style:** [e.g., Frank Lloyd Wright, Brutalism]
  * **Influence:** How it reflects in level design and spatial complexity

</details>

<details open>
<summary><b>📖 Literature & Philosophy</b></summary>

* **Author - "Work Title"**
  * **Theme:** How the literary theme is reinterpreted in the game

</details>

<details open>
<summary><b>🎵 Music & Sound</b></summary>

* **Genre/Composer:** [e.g., Jazz Fusion, Akira Yamaoka]
  * **Influence:** Correlation between musical structure and game atmosphere

</details>

<details open>
<summary><b>🎬 Cinema & Visual Media</b></summary>

* **"Title"** - Director
  * **Shared DNA:** Narrative or visual elements in common

</details>

---

## 🎮 Remakes, Remasters & Ports

<details open>
<summary><b>📦 Porting & Remaster Timeline</b></summary>

| Date | Platform | Version | Notes |
|------|----------|---------|-------|
| [YYYY-MM-DD] | [Platform] | [Original/Remaster/Remake] | [Details] |

</details>

---

## 🏆 Cultural Impact & Legacy

[Paragraph describing the game's influence on gaming culture, industry, or other media]

---

## 📚 Acknowledgments & Primary Sources

- **Source 1:** [Link or full citation]
- **Source 2:** [Link or full citation]
- **Source 3:** [Link or full citation]

---

**Last Modified:** [Date] | **Curator:** [Name] | **Status:** [Draft / In Review / Published]

## 📸 ADDING COVER ART

1. **Source the box art image:**
   - Use official publisher box art when available (fair use for editorial/archival purposes)
   - Sources: Wikipedia, MobyGames, IGDB, Fandom wikis
   - Preferred format: JPG, 300x400px (portrait orientation)

2. **Add to repository:**
   - Save as: `quartz-setup/static/covers/[game-slug].jpg`
   - Example: `castlevania-aria-of-sorrow.jpg`

3. **Update frontmatter:**
   ```yaml
   cover: /video-game-culture/static/covers/[game-slug].jpg
   releaseDate: YYYY-MM-DD
   ```

4. **The homepage will automatically include the image in the featured games grid**
