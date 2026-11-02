# Arcade Sampler

Twelve tiny, complete games in one arcade cabinet, each a different genre in its own art style: space deliveries, a platformer, a rooftop runner, merge and word puzzles, a tactics duel, tower defense, pixel-art rooms with sword fights, a neon arena for two, mini golf, lakeside fishing and a synthwave racer. Medals and best scores on every cabinet.

## Play

- **PushPlay (Steam Deck, Legion Go, PC):** find it in the launcher's **Discover** tab, or **Add game → GitHub → watch this repo**. Every push to `main` builds the game and publishes it to this repo's `pushplay-latest` release.
- **Browser:** `npm run setup`, then `npm run dev` (http://localhost:5173).

| Command | |
|---|---|
| `npm run dev` | Play locally with live reload |
| `npm run check` | Headless play test + art render (run before pushing) |

Plays with a controller, keyboard, mouse or touch. Agents: rules are in [`AGENTS.md`](AGENTS.md); the design brief is [`DESIGN.md`](DESIGN.md).

## Rights

© Visual Zone Development. All rights reserved. The source is public so PushPlay can build and verify the game; that doesn't make it open source, and it may not be copied, modified or redistributed without permission. Third-party assets (fonts and similar) keep their own licences, listed in the game's credits files.
