# 🤝 Contributing to CPCA

Thank you for your interest in the **Cross-Media Pop Culture Archive**! This guide explains how to contribute new game cards and resources.

---

## 🎯 Three Ways to Contribute

### Option 1: Fork & Pull Request (Recommended for Developers)

Perfect if you're comfortable with Git and GitHub.

#### Step 1: Fork the Repository
1. Click the **Fork** button (top right of the repository)
2. This creates your own copy of the project

#### Step 2: Clone Your Fork
```bash
git clone https://github.com/YOUR_USERNAME/video-game-culture.git
cd video-game-culture
```

#### Step 3: Create a Feature Branch
```bash
git checkout -b add/game-name
# Example: git checkout -b add/silent-hill-2
```

#### Step 4: Add Your Game Card
1. Copy the template: `TEMPLATE.md`
2. Create your card in `content/games/game-slug.md`
3. Follow the template structure
4. Fill in all available sections

**Example filename:** `content/games/silent-hill-2.md`

#### Step 5: Commit Your Changes
```bash
git add content/games/your-game.md
git commit -m "Add [Game Title] card with cross-media references"
# Example: git commit -m "Add Silent Hill 2 card with cultural analysis"
```

#### Step 6: Push to Your Fork
```bash
git push origin add/game-name
# Example: git push origin add/silent-hill-2
```

#### Step 7: Create a Pull Request
1. Go to the original repository
2. Click **Pull Requests** → **New Pull Request**
3. Select your fork and branch
4. Fill in a description:
   - Game title and year
   - Number of sources included
   - Any notes about your research
5. Click **Create Pull Request**

#### Step 8: Wait for Review
The maintainers will review your contribution and either:
- ✅ Merge it (your card goes live!)
- 💬 Request changes (we'll tell you what to fix)
- ❌ Decline (rare, but we explain why)

---

### Option 2: Edit Directly on GitHub (Easy)

No Git knowledge required! Perfect for small updates.

#### Step 1: Navigate to Content Folder
1. Go to the repository on GitHub
2. Navigate to `content/games/`

#### Step 2: Create a New File
1. Click **Add file** → **Create new file**
2. Name it: `your-game-slug.md`
3. **Example:** `outer-wilds.md`

#### Step 3: Copy the Template
1. Go back to `TEMPLATE.md`
2. Click the "Raw" button
3. Copy all the content
4. Paste into your new file

#### Step 4: Fill in Your Content
Edit directly in the browser and fill in all sections

#### Step 5: Commit & Create PR
1. At the bottom, select **Create a new branch** (don't commit directly)
2. Name it: `add/your-game-name`
3. Click **Propose changes**
4. Review your changes and click **Create Pull Request**
5. Add a description and submit!

---

### Option 3: GitHub Issues (Low-Effort Contribution)

Don't have a full card ready? Suggest resources instead!

#### Step 1: Open an Issue
1. Click **Issues** on the repository
2. Click **New Issue**

#### Step 2: Describe Your Suggestion
**Template:**
```
## Game: [Title] ([Year])

### Resources Found:
- 📖 Book: [Title] by [Author] — [Why it's relevant]
- 📽 Video: [Title] by [Creator] — [Link]
- 📰 Interview: [Details] — [Source]
- 🎨 Art Reference: [Details] — [Why influential]

### Notes:
[Any additional context or observations]
```

#### Step 3: Submit
Click **Submit new issue** — the community will compile this into a card!

---

## 📝 Card Structure Guide

### Required Sections (Every Card Must Have)

```markdown
# Game Title (Year)

**Developer:** Studio Name | **Director:** Person Name | **Original Platform:** PS2, GBA, etc.

**Genre:** [e.g., Action RPG, Metroidvania] | **Rating:** [ESRB/PEGI]

## 📌 Synopsis

[1-2 paragraph overview of the game and its cultural significance]

## 🎮 Remakes, Remasters & Ports

[Timeline of ports across platforms]
```

### Optional But Encouraged

- 📖 **Books, Essays & Novels** — Literary references and tie-in media
- 📽 **Video Essays & Documentaries** — YouTube analysis and behind-the-scenes
- 📰 **Historical Interviews** — Developer interviews and post-mortems
- 🎨 **Artistic References** — Painting, architecture, literature, music, cinema
- 🏆 **Cultural Impact & Legacy** — How the game influenced gaming and culture

---

## 🎯 Quality Standards

**All contributions must follow the [QUALITY_STANDARDS.md](QUALITY_STANDARDS.md) document.**

### Key Rules:

✅ **Every fact must be cited** — Citation links must be adjacent to claims  
✅ **Speculation must be labeled** — Clearly distinguish between fact and interpretation  
✅ **Evidence required** — If you speculate, provide supporting evidence (quotes, comparisons, analysis)  
✅ **Researched** — Sources should be real and verifiable  
✅ **Cross-media** — Link the game to other cultural works  
✅ **Specific** — Name artists, directors, composers when possible  
✅ **Balanced** — Mix critical and celebratory perspectives  
✅ **Engaging** — Write for both game fans and cultural researchers

**See [QUALITY_STANDARDS.md](QUALITY_STANDARDS.md) for detailed guidelines and examples.**  

### Writing Style:

- Clear, accessible English
- Use markdown formatting (bold, italics, links)
- Cite sources where possible
- 1,000-3,000 words per card is ideal

---

## 🔗 Markdown Tips

### Links
```markdown
[Text to display](https://example.com)
```

### Bold & Italics
```markdown
**Bold text** for important terms
*Italic text* for emphasis
```

### Lists
```markdown
* First item
* Second item
  * Nested item
```

### Collapsible Sections (Used in Templates)
```markdown
<details>
<summary><b>Section Title</b></summary>

Content goes here

</details>
```

### Tables
```markdown
| Year | Game | Platform |
|------|------|----------|
| 2003 | AoS  | GBA      |
```

---

## ❓ FAQ

**Q: Do I need to be a programmer to contribute?**  
A: No! Option 2 (GitHub's web editor) or Option 3 (Issues) require no coding skills.

**Q: How long should a card be?**  
A: 1,000-3,000 words is ideal, but shorter (500+ words) is acceptable.

**Q: Can I add games that aren't famous?**  
A: Absolutely! Indie games, cult classics, and lesser-known titles are welcome.

**Q: What if I can't find all the sections?**  
A: That's fine! Fill in what you can find. Incomplete cards are better than none.

**Q: How do I format interviews/links?**  
A: See TEMPLATE.md for examples. Generally:
```markdown
* **Game:** [Title]
* **Source:** [Interview Archive Name]
* **Link:** [URL]
* **Topic:** [What it covers]
```

**Q: Can I edit existing cards?**  
A: Yes! Use the same fork → edit → PR process.

**Q: How long until my PR is reviewed?**  
A: Usually within 3-7 days, depending on maintainer availability.

**Q: What if my contribution gets rejected?**  
A: We'll explain why. The most common reasons:
- Sources aren't verifiable
- Content isn't about the game's cultural impact
- Formatting doesn't match the template

**Q: Can I suggest new sections?**  
A: Yes! Open an Issue with your idea.

---

## 📚 Example: What a Good Card Looks Like

Check out **`content/games/castlevania-aria-of-sorrow.md`** for a complete example including:
- Academic and critical essays
- Video analysis references
- Historical developer interviews
- Artistic inspirations (painting, architecture, philosophy, music, cinema)
- Complete porting history
- Cultural impact analysis

---

## 🚀 Contribution Workflow (Visual)

```
1. Fork Repo
     ↓
2. Create Branch (add/game-name)
     ↓
3. Add content/games/game.md
     ↓
4. Commit & Push
     ↓
5. Create Pull Request
     ↓
6. Maintainer Reviews
     ↓
7. ✅ Merged → Live on site!
```

---

## 🎓 Research Resources

### Finding Cross-Media References

- **Academic journals:** Google Scholar, JSTOR
- **Video essays:** YouTube (Game Maker's Toolkit, Jacob Geller, Noclip)
- **Developer interviews:** Shmuplations, GDC archives, Gamasutra
- **Art history:** Museum collections, Wikipedia art pages
- **Philosophy:** Stanford Encyclopedia of Philosophy
- **Literary references:** Goodreads, Project Gutenberg

### Documentation Tips

When you find a reference:
1. **Note the source URL**
2. **Record the date** (when published/interviewed)
3. **Explain the connection** (why does it relate to the game?)
4. **Test the link** (does it still work?)

---

## 💬 Community Guidelines

- Be respectful of other contributors
- Accept constructive feedback gracefully
- Provide sources for factual claims
- Don't spam or promote unrelated content
- Have fun! This is a passion project

---

## 🙏 Thank You!

Your contributions make CPCA richer and more useful for:
- Game researchers
- Cultural analysts
- AI systems learning about games
- Designers seeking artistic inspiration
- Anyone curious about games and culture

**Questions?** Open an Issue or start a Discussion!

---

**Happy contributing!** 🎮📚✨
