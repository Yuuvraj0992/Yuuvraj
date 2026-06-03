[README.md](https://github.com/user-attachments/files/28541670/README.md)# Yuuvraj — Video Editor Portfolio

A single-file, bold/colorful portfolio site ready to deploy to GitHub Pages.

## Deploy to `yourname.github.io`

1. On GitHub, create a new public repo named **exactly** `yourusername.github.io` (e.g. `yuuvraj.github.io`).
2. Upload `index.html` to the root of the repo (drag and drop in the GitHub web UI, or `git push`).
3. Go to **Settings → Pages**. Under "Source," pick the `main` branch and `/ (root)`. Save.
4. Wait ~1 minute. Your site is live at `https://yourusername.github.io`.

## Customize

Open `index.html` and search for:

- **`Showreel goes here`** — replace the `<div class="placeholder">` block with an iframe:
  ```html
  <iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe>
  ```
- **`Project Title One`** through **`Project Title Six`** — swap titles, descriptions, and tags. Replace each card's `<div class="ph">▶</div>` with a YouTube embed iframe (same format as above).
- **Social links** — search for `YOUR_HANDLE` and replace with your Instagram, YouTube, and LinkedIn usernames.
- **About copy** — edit the paragraphs in `<section id="about">`.
- **Skills** — add/remove `<span class="skill">` tags.

## Contact form

The form uses [FormSubmit](https://formsubmit.co) — no backend needed. On the first real submission, you'll get a confirmation email at `isishaan178@gmail.com` to activate it. To disable, just remove the `<form>` block.

## Colors

The palette is defined as CSS variables at the top of the `<style>` block (`--c1` through `--c4`). Swap those hex values to retheme the whole site instantly.

