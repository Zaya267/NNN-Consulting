# NNN Consulting & Outsourcing website

Static website (one `index.html`, no build step). Pages are switched with links like `#about`, `#services`, `#faq`, `#contact`.

## Publish with GitHub Pages
1. Create a new repository on GitHub (for example `nnn-consulting`). Public repositories get Pages on the free plan.
2. Upload `index.html`, `.nojekyll` and `README.md` (Add file > Upload files), then commit.
3. Go to Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", Branch to `main` and folder `/ (root)`, then Save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/nnn-consulting/`. Send that link to the client.

Page links you can share: `.../#about`, `.../#services`, `.../#process`, `.../#faq`, `.../#contact`.

## Custom domain (later)
Settings > Pages > Custom domain, enter the client's domain (for example `www.nnnconsulting.co.za`), then add the DNS records GitHub shows at the client's domain provider. Tick "Enforce HTTPS".

## Editing
Contact details, opening hours and wording are plain text inside `index.html`. Search for the text and change it.

## Social media links
The Facebook and LinkedIn links in the footer and on the Contact page currently point to the sites' home pages. Search `facebook.com` and `linkedin.com` in `index.html` and replace them with the client's page addresses once confirmed.

## Forms
The site has no forms. GitHub Pages can use a form service (Formspree, Web3Forms or EmailJS), so contact and booking forms that email the client can be added later.
