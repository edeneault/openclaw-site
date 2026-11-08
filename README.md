# openclaw-site

The public home page and privacy policy for `openclaw`, a private, single-user assistant. Google
requires both pages before an External OAuth app can be published to production. The app's code
and infrastructure live elsewhere, in a private repository.

- `index.html`: what openclaw is, what it does, and which Google data it reads.
- `privacy.html`: how that data is used, stored and protected, and how to revoke it.

The site is static: plain HTML and inline CSS, with no JavaScript, cookies, trackers or external
resources.

It's served by GitHub Pages from the `main` branch, at the repository root:

- https://edeneault.github.io/openclaw-site/
- https://edeneault.github.io/openclaw-site/privacy.html

If the app's access or data handling changes, update `privacy.html` and its effective date first.
