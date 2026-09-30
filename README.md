# KeyClick website

The landing page for [KeyClick](https://github.com/MohAlkurdi/keyclick), live at https://mohalkurdi.github.io/keyclick-site/.

Astro, static. The sounds are built from the app repo's `Sounds/`, so clone both side by side:

```sh
git clone git@github.com:MohAlkurdi/keyclick.git
git clone git@github.com:MohAlkurdi/keyclick-site.git
cd keyclick-site && npm install && npm run dev
```

Pushes to `main` deploy to GitHub Pages. After changing sounds in the app repo, run the Site workflow by hand.

Design rules are in `DESIGN.md`.
