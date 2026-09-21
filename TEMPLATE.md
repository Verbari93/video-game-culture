---
title: "[Game Title]"
description: >
  [1-2 sentence description of the game and its cultural significance.
  This is displayed in search results and listings.]
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

<style>
.game-header {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 2rem;
  margin-bottom: 2rem;
  padding: 2rem;
  background: linear-gradient(135deg, rgba(40, 75, 99, 0.1) 0%, rgba(132, 165, 157, 0.1) 100%);
  border-radius: 12px;
  border-left: 4px solid var(--secondary);
}

.game-meta-card {
  display: flex;
  flex-direction: column;
  gap: 1rem;
  justify-content: space-between;
}

.game-meta-item {
  display: flex;
  flex-direction: column;
  gap: 0.25rem;
}

.meta-label {
  font-size: 0.85rem;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.5px;
  color: var(--secondary);
}

.meta-value {
  font-size: 1.1rem;
  font-weight: 500;
  color: var(--darkgray);
}

.game-info {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.game-title {
  font-size: 2rem;
  font-weight: 700;
  margin: 0;
  color: var(--dark);
  line-height: 1.2;
}

.game-year {
  font-size: 1.5rem;
  color: var(--secondary);
  font-weight: 600;
}

.game-rating {
  display: inline-block;
  padding: 0.5rem 1rem;
  background-color: var(--highlight);
  border-radius: 6px;
  font-weight: 600;
  color: var(--dark);
  width: fit-content;
}

.tag-section {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 1rem;
}

.tag {
  display: inline-block;
  padding: 0.4rem 0.8rem;
  background-color: var(--tertiary);
  color: white;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 500;
}

.tag.platform {
  background-color: var(--secondary);
}

.tag.genre {
  background-color: #7b97aa;
}

.tag.company {
  background-color: #84a59d;
}

.synopsis-box {
  background-color: var(--highlight);
  padding: 1.5rem;
  border-radius: 8px;
  margin: 1.5rem 0;
  border-left: 4px solid var(--secondary);
}

.synopsis-box p {
  margin: 0;
  line-height: 1.6;
  color: var(--darkgray);
}

@media (max-width: 768px) {
  .game-header {
    grid-template-columns: 1fr;
    gap: 1.5rem;
    padding: 1.5rem;
  }
  
  .game-title {
    font-size: 1.5rem;
  }
  
  .game-year {
    font-size: 1.2rem;
  }
}
</style>

<div class="game-header">
  <div class="game-meta-card">
    <div class="game-meta-item">
      <span class="meta-label">Developer</span>
      <span class="meta-value">[Developer Name]</span>
    </div>
    <div class="game-meta-item">
      <span class="meta-label">Director</span>
      <span class="meta-value">[Director Name]</span>
    </div>
    <div class="game-meta-item">
      <span class="meta-label">Original Platform</span>
      <span class="meta-value">[Platform]</span>
    </div>
    <div class="game-meta-item">
      <span class="meta-label">Rating</span>
      <div class="game-rating">[ESRB/PEGI Rating]</div>
    </div>
  </div>
  
  <div class="game-info">
    <div>
      <div class="game-year">[YEAR]</div>
      <h1 class="game-title">[Game Title]</h1>
    </div>
    <div class="tag-section">
      <span class="tag genre">[Genre 1]</span>
      <span class="tag genre">[Genre 2]</span>
      <span class="tag platform">[Platform 1]</span>
      <span class="tag platform">[Platform 2]</span>
      <span class="tag company">[Company]</span>
    </div>
  </div>
</div>

<div class="synopsis-box">

[Brief description of the game and its cultural significance, with relevant links]

</div>

---

## 📌 Synopsis

[Brief description of the game and its cultural significance]


## 📖 Books, Essays & Novels

<details open>
<summary><b>📚 Novels and Tie-In Media</b></summary>

* **Title:** Author
* **Description:** Notes on how the book relates to the game

</details>

<details open>
<summary><b>✍️ Critical & Analytical Essays</b></summary>

* **Title:** Author/Publisher
* **Focus:** Critical or analytical aspect covered
* **Link:** [if available]

</details>

---

## 📽️ Video Essays & Documentaries

<details open>
<summary><b>🎬 Analytical Videos</b></summary>

* **Title:** Creator/Channel
* **Platform:** YouTube, Vimeo, etc.
* **Duration:** [minutes]
* **Topic:** What the video covers

</details>

<details open>
<summary><b>🎞️ Documentaries & Making-Of</b></summary>

* **Title:** Studio/Creator
* **Type:** [Documentary, compiled interview, etc.]
* **Link:** [URL]

</details>

---

## 📰 Historical Interviews & Post-Mortems

<details open>
<summary><b>🎤 Key Interviews</b></summary>

* **Year/Date:** [e.g., 2001]
* **Interviewee:** Creator/Designer Name
* **Medium:** [Shmuplations, Interview Archive, etc.]
* **Key Topic:** Main theme of the interview
* **Link:** [URL]

</details>

<details open>
<summary><b>📊 Post-Mortems & Retrospectives</b></summary>

* **Source:** [e.g., GDC, Gamasutra]
* **Topic:** Development evolution or reception
* **Link:** [URL]

</details>

---

## 🎨 Artistic References & Cross-Media Inspirations

<details open>
<summary><b>🖼️ Visual Arts (Painting, Sculpture, Photography)</b></summary>

* **Artist/Work:** [e.g., Giorgio de Chirico, "Piazza d'Italia"]
* **Connection:** How the work influences the game's visual design
* **Notes:** Specific details

</details>

<details open>
<summary><b>🏛️ Architecture & Spatial Design</b></summary>

* **Architect/Style:** [e.g., M.C. Escher, Brutalist Architecture]
* **Influence:** How it reflects in level design
* **Link:** [visual references]

</details>

<details open>
<summary><b>📖 Literature & Philosophy</b></summary>

* **Author/Work:** [e.g., Dante Alighieri, "Divine Comedy"]
* **Theme:** How the literary theme is reinterpreted in the game

</details>

<details open>
<summary><b>🎵 Music & Sound</b></summary>

* **Genre/Composer:** [e.g., Baroque Music, Akira Yamaoka]
* **Influence:** Correlation between musical structure and game atmosphere

</details>

<details open>
<summary><b>🎬 Cinema & Visual Media</b></summary>

* **Title/Director:** [e.g., "Blade Runner", Ridley Scott]
* **Shared DNA:** Narrative or visual elements in common

</details>

---

## 🎮 Remakes, Remasters & Ports

<details open>
<summary><b>📦 Porting & Remaster Timeline</b></summary>

| Date | Platform | Version | Notes |
|------|----------|---------|-------|
| [YYYY] | [Platform] | [e.g., Original, Remaster, Remake] | [Technical details] |
| | | | |

</details>

---

## 🏆 Cultural Impact & Legacy

[Paragraph describing the game's influence on gaming culture, industry, or other media]

---

## 📚 Acknowledgments & Primary Sources

- **Source 1:** [Link or citation]
- **Source 2:** [Link or citation]
- **Source 3:** [Link or citation]

---

**Last Modified:** [Date] | **Curator:** [Name/Nickname] | **Status:** [Draft / In Review / Published]
