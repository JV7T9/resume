# John Va'afuti – Custom Digital Resume

An interactive digital resume (Professional Trait Stack) built as a single-page site.

**Live:** https://jv7t9.github.io/resume/
**Projects & Developments:** https://jv-projects.tfmsupport.workers.dev/

## What's in it
- Profile, key traits and skills, training and education, employment history, projects and contact sections
- Animated name reveal, three.js background, sliding header and a built-in track player
- Project cards with video previews that load as you scroll to them
- Referee and contact details are unlocked on request and are not stored in this repository

## Files
```
index.html     the whole site (HTML, CSS and JavaScript)
pointer.html   one-page cover letter template that links to the resume
assets/        images and project videos used by the page
tracks/        audio tracks for the built-in player
LICENSE        MIT licence (applies to the code only, see below)
```

Keep the file names in `assets/` and `tracks/` exactly as they are. GitHub Pages is case-sensitive, and the Projects site loads some of these files directly.

To add a track, put the file in `tracks/` and add a matching `<option>` line to the track list in `index.html`.

## Running it
No build step. Open `index.html` in a browser, or serve the folder with any static host. It is published with GitHub Pages from the main branch.

## Licence
The **code** is released under the [MIT Licence](LICENSE).

The **content is not covered** by that licence and remains © John Va'afuti, all rights reserved. This includes the written text, employment and education details, photos and images, videos and audio tracks. Please don't copy or reuse them without permission.

## Contact
Use the unlock form in the Contact section of the live site.
