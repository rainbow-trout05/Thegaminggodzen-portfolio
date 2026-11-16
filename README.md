# Fawwaz Portfolio

Static portfolio site: plain HTML, CSS, and vanilla JavaScript. No build step.

## Structure

- `index.html`: landing page (hero, About, Skills, Projects, Collaborate, Contact)
- `projects/rise.html`: RISE project page (copy it to add more projects)
- `css/styles.css`: all styling
- `assets/`: images, video, favicon

## Assets in `assets/`

Already included:

- `portrait.jpg`: the top-two-thirds crop of your portrait (6:5), shown without stretching
- `rise-screenshot.jpg`: RISE screenshot (1600x817)
- `rise-gameplay.mp4`: compressed RISE gameplay video (about 7 MB)

## Placeholders to replace before publishing

Search the project for `ADD`. Currently the only one left is the optional RISE GitHub button:

- Optional RISE GitHub button in `projects/rise.html` (uncomment when a verified URL exists)

The WhatsApp number must appear only inside the `wa.me` URL, never as visible text.

## Adding a project

1. Copy `projects/rise.html` to `projects/<name>.html` and replace the content.
2. Replace a "Coming soon" card in `index.html` with a card matching the RISE card, linking to the new page.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, open Settings, then Pages.
3. Set the source to the main branch, root folder, and save.
4. Open the published URL. All paths are relative, so it works from the repository subpath.

## Release checklist

- All asset paths load and all contact URLs work
- RISE name, copy, and visual direction approved by the owner
- No `ADD` placeholders remain
