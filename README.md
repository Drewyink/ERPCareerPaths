# ERP and AI Careers Q&A

An interactive page from Echolink Solutions that shows ERP, Power BI, Power Automate and AI Copilot career paths, class details, software links, questions and answers, and how the four tools connect.

## Files

- `index.html` holds the whole page, including the styles, script and content. It needs no build step.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `erp-career-paths`.
2. Upload `index.html` and this `README.md` to the root of the repository.
3. Open **Settings**, then **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Choose the `main` branch and the `/ (root)` folder, then select **Save**.
6. After a minute or two, the page is live at `https://<your-username>.github.io/erp-career-paths/`.

## Direct links to each tab

Add one of these to the end of the page address:

| Link ending | Opens |
|---|---|
| `#erp`, `#power-bi`, `#power-automate`, `#ai-copilot` | Career paths, on that track |
| `#class-info` | Software, reading and Q&A |
| `#how-they-connect` | How they connect |

## Updating content

- Career roles, salaries and certifications are in the `TRACKS` object in the script near the bottom of `index.html`.
- The diagram text is in the `HUB` object, and the walkthroughs are in `STORY` (general business) and `STORY_H` (healthcare).
- Class details, software links and questions and answers are plain HTML in the section with `id="view-info"`.

## Contact

info@echolinksolutions.com
