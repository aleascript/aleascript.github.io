# AleaScript

Source repository for [aleascript.github.io](https://aleascript.github.io/), the public portal for AleaScript tabletop role-playing game design projects.

## Public projects

- [Resonance](https://aleascript.github.io/resonance/) — an experimental game design paradigm for tabletop role-playing games.
- [Regard](https://aleascript.github.io/regard/) — a playable TTRPG framework designed with Resonance.
- [Glorantha Perspectives](https://aleascript.github.io/glorantha-perspectives/) — a Glorantha role-playing game designed with Regard.
- [Unmind](https://aleascript.github.io/unmind/) — a short, bounded role-playing game experiment designed with Resonance.

The portal is bilingual (English/French) and built with Docusaurus on GitHub Pages.

## Development

```bash
npm ci
npm run start:en
# or
npm run start:fr
```

Validate the production build with:

```bash
npm run typecheck
npm run build
```
