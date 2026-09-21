# AOE Scout — Age of Empires Player Intelligence

[AOE Scout](https://aoescout.com/) is a player-intelligence and match-preparation companion for **Age of Empires II: Definitive Edition**, **Age of Empires III: Definitive Edition**, and **Age of Empires IV**.

It brings rankings, active games, multiplayer lobbies, civilization performance, player comparisons, unit data, match history, and practical opponent insights into one consistent experience. Instead of making players study several disconnected pages, AOE Scout turns public match data into information that is easy to understand before and during a game.

> **Scout the opponent, not just the map.**

## Live product

- Website: [aoescout.com](https://aoescout.com/)
- Age of Empires II DE: [aoescout.com/age-of-empires-2-de](https://aoescout.com/age-of-empires-2-de)
- Age of Empires III DE: [aoescout.com/age-of-empires-3-de](https://aoescout.com/age-of-empires-3-de)
- Age of Empires IV: [aoescout.com/age-of-empires-4](https://aoescout.com/age-of-empires-4)
- Contact and community: [aoescout.com/contact](https://aoescout.com/contact)

## Supported games

AOE Scout provides dedicated pages and game-aware data for:

- **Age of Empires II: Definitive Edition**
- **Age of Empires III: Definitive Edition**
- **Age of Empires IV**

Each game keeps its own civilizations, rankings, modes, player statistics, lobbies, and terminology while sharing the same visual system and navigation.

## Leaderboards

The leaderboards make competitive performance easier to browse without losing the context behind a number. Players can explore ranked ladders by supported mode, view rank and rating information, and open a player profile for a deeper look.

AOE Scout includes game-specific leaderboard modes such as:

- Ranked 1v1 and team ladders
- Random Map and Empire Wars modes where supported
- Deathmatch modes for Age of Empires II DE
- Console solo and team rankings for Age of Empires IV

Leaderboard rows connect naturally to player profiles, so a ranking can become a useful read of that player's experience, civilizations, recent games, and performance.

## Live games and multiplayer lobbies

The **Live Games** pages show matches currently in progress, including participating players and available match context. They provide a quick route from a live match to the players involved.

The **Lobbies** pages help players browse available multiplayer rooms, game settings, maps, player counts, and other useful lobby details. Live games and lobbies are kept separate so visitors can quickly choose between watching current activity and finding a game to join.

## Civilization statistics

Civilization statistics turn match data into an understandable view of the current meta. Players can compare civilization performance using information such as:

- Pick and play rates
- Win rates
- Match counts
- Ranked mode and map context
- Performance differences across available filters

Each game's civilization page is built around its own roster rather than forcing unrelated game data into one generic table.

## Compare units

The unit comparison tools place important unit information side by side. They are designed to answer practical questions about cost, combat role, movement, durability, attack, armor, range, and other game-specific attributes.

Comparisons use the correct civilization and game assets so players can recognize units visually as well as numerically. The goal is not simply to display a large data table; it is to make meaningful differences easy to scan.

## Compare players

Player comparison brings two profiles into one focused view. It helps players compare:

- Current and highest ranks
- Rating or ELO
- Wins, losses, and win rate
- Total matches
- Favorite civilizations
- Recent form and available performance history

This makes it easier to understand how two players differ without switching repeatedly between profile pages.

## Player profiles and match history

Player profiles bring together the identity and competitive history available for that game. Depending on the title and available public data, a profile can include rank summaries, recent matches, civilization preferences, win/loss performance, and match details.

The interface keeps solo and team performance distinct. Current rank and highest rank are shown as separate signals so a player can understand both present form and previous achievement.

## Opponent intelligence

Opponent intelligence is the central idea behind AOE Scout. It translates a player profile into a fast pre-match read, including available signals such as:

- Current and highest solo rank
- Current and highest team rank
- Rating or ELO
- Current and frequently played civilizations
- Total matches, wins, losses, and win rate
- Recent strategic patterns
- Fast second Town Center, early army, and Fast Castle timings
- Economy averages and likely unit composition

The information is presented in compact cards that are shared across the website and Windows companion. The purpose is to help a player prepare for the opponent's likely habits—not to overwhelm them with another spreadsheet.

## Auto Queue villagers

The optional Windows companion can help players remember recurring villager queues during demanding moments of a match.

The player chooses the **Town Center** and **Queue Villager** shortcut keys and sets the preferred interval. AOE Scout then triggers those selected shortcuts at the scheduled time while the player remains focused on scouting, micro, or a fight.

**Auto Queue is not game injection and does not modify the game.** It works by pressing the keyboard shortcuts selected by the player at the appropriate time.

## Single-player cheats

AOE Scout includes searchable single-player cheat references for:

- Age of Empires II and Age of Empires II DE
- Age of Empires III and Age of Empires III DE
- Age of Empires IV

These pages organize supported cheat codes with plain-language explanations so players can quickly find the command they need for a single-player or custom-game session. Cheat reference pages are separate from competitive player intelligence and Auto Queue functionality.

## Consistent web and Windows experience

AOE Scout uses one design language across its public website and Windows companion. Rank badges, civilization icons, unit artwork, data cards, spacing, typography, and status colors are designed to remain familiar as players move between surfaces.

The website provides discovery, statistics, comparisons, and profile research. The optional Windows companion brings the most time-sensitive information closer to the match.

## Screenshots

### Opponent intelligence

![AOE Scout opponent intelligence card](screenshots/opponent-intelligence.png)

### Website overview

![AOE Scout homepage and game selection](screenshots/homepage-full.png)

## Public repository scope

This repository is the public-facing, static showcase for AOE Scout. It contains:

- `index.html` — semantic, crawlable product content and a responsive showcase
- `screenshots/` — browser-generated product captures
- `README.md` — detailed product documentation

It intentionally does **not** include private application source code, APIs, authentication logic, data services, deployment configuration, credentials, Windows binaries, or Microsoft Store packages.

## Local preview

Open `index.html` directly in a browser or serve this directory with any static file server. No package installation or build process is required.

## Credits and disclaimer

AOE Scout is built by Talha Zahid for the Age of Empires community.

Age of Empires and related names, artwork, and marks belong to Microsoft and their respective owners. AOE Scout is a community project and is not endorsed by or affiliated with Microsoft.
