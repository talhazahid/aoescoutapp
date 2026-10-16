# Product interface updates

## 2026-10-16

### Mobile player profiles

- Removed duplicate player-name, AOE Scout profile-link and game-ID rows from the mobile layout while retaining them on desktop.
- Kept the Compare players action directly below the main player name/game header; removed the duplicated promotional copy on mobile.
- Ordered mobile ranked sections as solo card → solo season history → team card → team season history.
- Aligned matchup headings and civilization selectors with the existing section gutter.

### Statistics readability

- Full-width Most played civilizations panels on AoE II and AoE III.
- Explicit Win rate labels beside the displayed percentages; list ordering remains by matches played.
- Shared charcoal surfaces, subdued gold accents and semantic win-rate colors across the website, retaining rank-card artwork.

### Public example

Added `examples/mobile-profile.html`, a self-contained responsive illustration of the profile refinements. Its numbers are fictional; it does not query APIs or contain production application internals.
