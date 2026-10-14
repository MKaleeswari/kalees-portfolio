# Lucas's Delight

https://devlucas.website/  clone this website

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://lucas-web-muse.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/1298be04-e959-4cd4-adea-9f2ed3fd13fc).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

On mobile (below 640px), Selected Work is a horizontally scrollable, snap-to-card
list with the next project partially visible as a swipe cue. Wider screens retain
the two-column grid.

The hero's Download CV button downloads the bundled
`src/assets/projects/kaleeswari_resume_m.pdf` file. Replace that PDF to update
the downloadable resume.

Buttons share a visible keyboard focus ring. The My work action stays
transparent on hover, while navigation and outlined buttons use the primary
color. Decorative underline and shimmer hover effects only run with a mouse
or other fine pointer.

## Contact form

The contact form sends messages through Web3Forms using its browser-safe access
key. To rotate or override that key, copy `.env.example` to `.env.local`, set
`VITE_WEB3FORMS_ACCESS_KEY`, and add the same value to the hosting provider's
environment variables before rebuilding.

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
