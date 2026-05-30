# Family Garden

Family Garden is a small shared virtual garden made for a family celebration. It is a gentle web experience where family members can enter as a character, walk around the garden, leave messages, save memories, and add travel postcards or photos.

Live site: https://peilinpeng.github.io/FamilyGarden/

## What You Can Do

- Choose a family character and display name.
- Explore a hand-drawn garden scene.
- Leave and read messages in the garden.
- Save postcards and travel memories.
- Upload photos connected to places and family stories.
- Keep shared data synced through cloud storage.

## Project Status

This is an MVP release. The current public version is designed primarily for desktop and laptop browsers. Mobile support is limited, and the best mobile experience is on larger screens or in landscape orientation.

## Tech Stack

- Godot Engine
- Godot Web export
- GitHub Pages for hosting
- Supabase for cloud data and storage

## Repository Notes

This repository contains the exported web build used by GitHub Pages. The main Godot source project is maintained separately, then exported into this folder for deployment.

Important generated files include:

- `index.html`
- `index.js`
- `index.wasm`
- `index.pck`

## Running Locally

From the repository root:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/index.html
```

## Deployment

The site is deployed through GitHub Pages from the `main` branch.

When updating the game:

1. Export the latest Godot Web build into this repository.
2. Test it locally.
3. Commit the exported files.
4. Push to GitHub.
5. Wait for GitHub Pages to refresh.

## Credits

Created with love for family memories, birthdays, travel stories, and a small digital garden that can keep growing.
