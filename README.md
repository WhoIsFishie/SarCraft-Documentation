
![https://github.com/WhoIsFishie/SarCraft-Documentation/blob/main/source/content/SarCraft/Seasons/S1_images/sarcraft_banner.png](https://github.com/WhoIsFishie/SarCraft-Documentation/blob/main/source/content/SarCraft/Seasons/S1_images/sarcraft_banner.png)
# SarCraft Documentation Wiki

Documentation of SarCraft history and lore.

## Getting Started

This documentation is built using [Quartz](https://quartz.jzhao.xyz/), a tool for turning Markdown files into a digital garden/wiki.

### Prerequisites

- [Node.js](https://nodejs.org/) (v20 or later)
- [Git](https://git-scm.com/)
- [Obsidian](https://obsidian.md/) (recommended for editing)

## How to Contribute

### Initial Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/WhoIsFishie/SarCraft-Documentation.git
   cd SarCraft-Documentation
   ```

2. Install dependencies:
   ```bash
   cd source
   npm install
   ```

3. Local preview:
   ```bash
   npx quartz build --serve
   ```
   This will start a local server at http://localhost:8080 where you can preview the site.

### Contribution Workflow

#### For Lore/Content Contributors

1. **Using Obsidian (Recommended)**:
   - Open Obsidian
   - Import the `source/content/SarCraft` folder as a vault
   - Make your changes
   - Use Git to commit and push your changes

2. **Organization Structure**:
   - `/Seasons/` - Documentation for each server season
   - `/Players/` - Player profiles
   - `/Factions/` - Information about server factions
   - `/Lore/` - General server lore, events, and mechanics

3. **Formatting Guidelines**:
   - Use appropriate frontmatter (at the top of each file):
     ```md
     ---
     tags:
       - player
       - faction-name
     aliases:
       - Nickname
     ---
     ```
   - Include player images in the format `![[player_images/Username.png|300]]`
   - Use wikilinks (`[[Page Name]]`) to reference other pages
   - For events, include dates when possible
   - Keep language neutral and accurate
   - Add screenshots where helpful
   - Use timestamps for dated events

#### For UI/UX Contributors

If you want to modify the site structure or functionality:

1. Make sure not to modify files in the `source/content/SarCraft` folder (that's for content only)
2. Understand the Quartz configuration in `source/quartz.config.ts` and `source/quartz.layout.ts`
3. Test your changes locally before committing

## Content Guidelines

### Adding a New Player

Use the template at `Templates/player_template.md` as a starting point:

```md
---
tags:
  - player
  - faction-name
aliases:
  - Nickname
---

![[player_images/Username.png|300]]   
## Player Title or Description

Brief introduction to the player's significance on the server...

### Quick Stats

| First Season | Last Active | Current Faction | Notable Role |
| ------------ | ----------- | --------------- | ------------ |
| [[Season X]] | [[Season Y]] | [[Faction Name]] | Role |

...rest of content...
```

### Adding a New Season

1. Create a new file at `Seasons/Season X.md`
2. Use existing seasons as templates
3. Include:
   - Season dates
   - Major events
   - Faction activities
   - Server changes/updates
   - Significant builds
   - Player conflicts

### Images and Media

1. Place images in appropriate folders:
   - Player images in `player_images/`
   - Season-specific images in `SX_images/` (where X is the season number)
2. Compress videos before uploading
3. Use webp format for images when possible to reduce size

## Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the main branch. The CI process will:

1. Build the site using Quartz
2. Deploy to GitHub Pages
3. Make the updated site available at the configured domain

## Need Help?

If you have questions or need assistance, please reach out to the repository maintainers or open an issue on GitHub.

Thank you for helping document SarCraft's rich history!
