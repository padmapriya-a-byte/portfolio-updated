# Padmapriya V: portfolio

## Run locally
Install Node.js 18+, then in this folder:

    npm install
    npm run dev        # opens http://localhost:5173
    npm run build      # production build in dist/

## Update content
All text, links and certificate paths are in src/data/data.js. Put files from ASSETS_NEEDED.md into public/. Buttons for missing files show "file not added yet" and switch to working links once the file exists.

## Contact form
Get a free key at web3forms.com, copy .env.example to .env, set VITE_WEB3FORMS_KEY, restart. Without a key the form says it is not connected and the email button works.

## Deploy to Vercel
1. Push this folder to a GitHub repository (do not commit .env).
2. On vercel.com choose Add New > Project, import the repository. Vercel detects Vite automatically.
3. Under Environment Variables add VITE_WEB3FORMS_KEY, then Deploy.

## Not included yet
Tamil/English toggle, Portfolio Assistant chatbot, live GitHub API panel, interactive playgrounds, architecture diagrams and full case-study sections.


## Navigation improvements
- Added Home to the primary navigation and renamed Internships to Experience for a cleaner label.
- Added accessible mobile menu controls (`aria-expanded` and `aria-controls`) with a clear open/close label.
- Added active-section styling, smooth anchor navigation, and scroll offsets so headings are not hidden behind the sticky header.
- Included the supplied resume at `public/resume/Padmapriya-V-Resume.pdf`.

Run these commands from the folder that contains `package.json` (the `portfolio` folder):

```bash
npm install
npm run dev
```
