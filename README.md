# The Little Love Quest

A self-contained, responsive mini-game modeled on the supplied phone-video flow: a four-digit keypad, an unlock transition, three gift boxes, a playlist card, a letter, and a date choice. Open `index.html` in a modern browser. The entrance PIN is `1402`.

## Publish through GitHub Pages

After signing in with `gh auth login`, create a public repository, push this directory, then enable GitHub Pages from the repository's `main` branch and `/ (root)` folder. Once the public URL is known, generate a QR image for that exact URL; do not point the QR code at a local file.

## Personalising it

Edit `const CODE='1402'`, the letter text, and the gift labels near the bottom of `index.html`. Add a real music URL in the `#play` handler before sharing.
