# Tiantong Wang — Academic Homepage

Personal academic website for Tiantong Wang at Nanyang Technological University.

Website: https://tiantongwang.com/

## Files

- `index.html`: biography, research directions, selected publications, education, teaching, and contact details.
- `style.css`: academic profile sidebar, reading layout, responsive typography, keyboard focus states, and print styles.
- `publications.bib`: BibTeX entries for the five selected publications, also available through each paper's expandable citation.
- `profile.jpg`: original profile photograph.
- `CV_WangTiantong.pdf`: current public CV, with personal telephone numbers removed and the academic email retained. Keep this filename when updating so existing links continue to work.
- `favicon.svg`: site icon.
- `CNAME`: existing custom domain configuration.

## Updating the site

Edit the relevant section in `index.html` and the styling in `style.css`. All content is static HTML; there is no build step, package installation, or JavaScript requirement. GitHub Pages publishes the repository's configured source branch.

For each publication, preserve the full title, author order, venue, year, and official paper link. Emphasize Tiantong Wang's name with `<strong>`. Add contribution or presentation designations only when verified. Put new papers in the appropriate year group, and keep each expandable BibTeX entry consistent with `publications.bib`.

Replace `CV_WangTiantong.pdf` with the latest CV and update the footer's last-updated month. When changing `style.css`, update the stylesheet version query in `index.html` so returning visitors receive the new styles.

The October 2026 content update follows the supplied CV. Research directions are concise summaries of its publication topics. The academic layout uses a profile sidebar and a separate reading column, with papers grouped by year. All publication content and citation panels remain usable without JavaScript. The original profile photograph, Chinese name, PhD-candidate designation, and custom domain are retained from the existing site.

## Preview

Open `index.html` directly in a browser, or use a local static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. Check narrow and wide layouts, section links, external publication links, and the CV download before publishing.
