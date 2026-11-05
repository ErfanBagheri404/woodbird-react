# Woodbird - agency landing page

React + Vite recreation of the Woodbird agency landing page: sticky header and a
fullscreen video hero with oversized custom typography.

## Sections

- `Header` - logo, nav links, CTA.
- `Hero` - background video, headline, scroll cue.

## Run

```bash
git clone https://github.com/ErfanBagheri404/woodbird-react.git
cd woodbird-react
```

```bash
npm install
npm run dev
```

`npm run build` produces `dist/`.

## Stack

React 18 - Vite - CSS with self-hosted fonts and a video background.

## Structure

| path | role |
|---|---|
| `src/App.jsx` | header + hero |
| `src/components/Header.jsx` | navigation |
| `src/components/Hero.jsx` | video hero |
| `src/fonts/`, `src/assets/` | type and media |
