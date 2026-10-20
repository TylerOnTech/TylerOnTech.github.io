# TylerOnTech.github.io

Personal portfolio for Tyler Kunkel, live at **https://tylerontech.github.io**.

It showcases:

- **BindHQ**: multi-tenant agency management system + CRM for independent insurance agencies (TyKu Technologies)
- **Black Box Fragrances**: personal fragrance decision engine with Match Score and Bottle Check
- Smaller builds and client work, experience, and contact links

## How it's built

Plain HTML and CSS with no framework and no build step, so GitHub Pages serves the files as-is.
`.nojekyll` turns off Jekyll processing.

```
index.html            the whole page
assets/css/style.css  styles (light + dark follow the visitor's system setting)
assets/img/           portrait, Black Box logo, favicon, social share image (og.png)
```

## Editing

Edit `index.html`, commit, and push to `main`. GitHub Pages redeploys automatically within a
minute or two. To preview locally, open `index.html` in a browser, or run
`npx serve .` and visit http://localhost:3000.
