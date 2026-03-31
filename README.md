# D&D Compendium
A searchable encyclopedia of Dungeons & Dragons 5th Edition spells and monsters.
Browse, filter, sort, and save your favorites to a personal spellbook, all in one dark-fantasy themed web app.

# Project Purpose
The D&D Compendium is a fan-made reference tool built for players and Dungeon Masters who want quick access to spell and monster data from D&D 5e. Instead of flipping through a rulebook, users can instantly search for a spell, filter monsters by type, or sort by challenge rating, right in the browser.

# API Being Used
D&D 5e API — [https://www.dnd5eapi.co](https://www.dnd5eapi.co)
- Endpoints used:
  - /api/monsters — full list of D&D monsters with stats
  - /api/spells — full list of D&D spells with details
- Returns structured JSON data including names, types, stats, descriptions, and more

# Planned Features
Core Features (Required)
- Search : Search monsters or spells by name using a live search bar
- Filter : Filter monsters by type (beast, undead, dragon, etc.) and spells by school (Evocation, Necromancy, etc.)
- Sort - Sort monsters by Challenge Rating and spells by level (ascending/descending)
- Favorites/Spellbook — Save favorite spells and monsters to a personal spellbook using localStorage

# Technologies Used
HTML5
CSS
JavaScript 
D&D 5e API

# How to Run the Project
1. Clone or download this repository
2. Make sure all three files are in the same folder:
   - index.html
   - style.css
   - script.js
3. Open index.html in any modern web browser
4. No installation, no server, no dependencies required

# Project Structure
d&d/
│
├── index.html       # Main HTML file — structure and layout
├── style.css        # All styling — theme, cards, modal, responsive
├── script.js        # All JavaScript — API calls, rendering, interactions
└── README.md        # Project documentation
