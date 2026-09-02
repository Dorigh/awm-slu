# AWM Student Chapter @ SLU — website

A small, static, ad-free website for the Association for Women in Mathematics
student chapter at Saint Louis University. Two pages, no build step, no
backend — just `index.html`, `events.html`, and `style.css`.

## Publish it for free with GitHub Pages

1. Create a new **public** GitHub repository (e.g. `awm-slu`).
2. Upload these three files to the repository (drag-and-drop works fine on
   github.com, via **Add file → Upload files**):
   - `index.html`
   - `events.html`
   - `style.css`
3. Go to the repo's **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`,
   branch `main`, folder `/ (root)`. Save.
5. GitHub will give you a live URL, usually
   `https://<your-username>.github.io/awm-slu/`, within a minute or two.

That's it — no ads, no tracking, no cost.

## Updating it later (e.g. adding a new event)

Open `events.html` in any text editor and copy one of the existing
`<div class="event">...</div>` blocks, then edit the date, title, and poster
link. New events can go at the top of the relevant year, or you can add a new
`<div class="year-group">` for a new year. Commit the change on GitHub (or
push via git) and the live site updates automatically.

## About the content

The text and event listing were carried over from the chapter's previous
site (`mathstat.slu.edu/resources/awm`), recovered via the Wayback Machine
after SLU's site migration. Event posters currently link out to the archived
images on web.archive.org rather than being re-hosted here — if you'd like
them hosted directly on this site instead, download the poster images and
drop them in an `images/` folder, then update the `href`/`src` in
`events.html` to point to `images/filename.png`.

Double-check the meeting time/location on the homepage each semester, since
that changes and this site doesn't update itself.
