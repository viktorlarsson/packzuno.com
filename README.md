# packzuno.com

Statisk webbplats för Packzuno. Allt ligger i `index.html`, utan byggsteg.

Driftsätts via Vercel. Importera repot som ett projekt med Framework Preset "Other", utan byggkommando och med roten som output.

## SEO-filer

- `robots.txt` och `sitemap.xml`: uppdatera `lastmod` och lägg till nya sidor i sitemapen när de skapas.
- `og.png` (1200 × 630): delningsbild för sociala medier.
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`: ikoner.
- `vercel.json`: rena URL:er och cache-headers.
