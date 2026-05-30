# TK SteelBot — AI Sales Assistant

**Live interactive prototype** for T.K. Steel Rolling Mills Pvt. Ltd. (TK Steels), Ludhiana, Punjab.

This is a **100% static, single-file website** designed for easy deployment on GitHub Pages, Vercel, Netlify, or any static hosting service.

---

## 🚀 Quick Deploy to GitHub Pages

### Method 1: Folder-based (Recommended)

1. Push this folder (`tk-steels-ai-assistant/`) to your GitHub repository
2. Go to your repository → **Settings** → **Pages**
3. Under "Build and deployment":
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or `master`)
   - **Folder**: `/tk-steels-ai-assistant`
4. Click **Save**
5. Wait 30–60 seconds — your site will be live at:
   ```
   https://yourusername.github.io/your-repo-name/tk-steels-ai-assistant/
   ```

### Method 2: Root deployment

If you want the demo at the root of your GitHub Pages site:
- Copy the contents of `index.html` directly into the root of a new repository (or `docs/` folder)
- Set GitHub Pages source to the root or `/docs`

---

## What's Included

- **Fully functional AI Sales Assistant chatbot**
  - Answers questions about 200+ steel grades (EN series, SAE, etc.)
  - Guided RFQ capture flow (product → grade → size → quantity → application → timeline → contact)
  - Professional RFQ summary generation
  - WhatsApp handoff with pre-filled message
  - Downloadable RFQ summary

- **Beautiful landing page** with:
  - Hero section
  - Live interactive demo
  - Key capabilities
  - How it works
  - Production readiness notes
  - Clear deployment instructions

- **Zero dependencies** after initial load (Tailwind + Font Awesome via CDN)

---

## Running Locally

Simply open `index.html` in any modern browser. No server, build step, or installation required.

```bash
# From the folder containing index.html
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

---

## Customization Ideas

- Replace the logo and contact details with real TK Steels assets
- Add your actual WhatsApp number and email
- Extend the `gradeKnowledge` object in the JavaScript with more grades
- Connect the "Submit RFQ" action to a real form handler or Google Sheets (via a small backend or Formspree)
- Add Google Analytics or Microsoft Clarity

---

## Production Path

This prototype was created as part of the **TK Steels AI Opportunity Audit** (May 2026).

A production version would typically include:
- Secure LLM backend (Grok, Claude, or GPT-4o) with RAG over your catalog
- WhatsApp Business API integration
- CRM sync (Zoho / Salesforce / custom)
- Lead scoring + routing
- File upload support for drawings
- Admin dashboard

---

## Attribution

Built by **Technowild** as a high-fidelity demonstration for TK Steels.

**Company**: T.K. Steel Rolling Mills Pvt. Ltd.  
**Location**: Ludhiana, Punjab, India  
**Website**: http://tksteels.com/

---

## License

This prototype is provided for demonstration and internal evaluation purposes.

---

**Ready to show your team or stakeholders?**  
Just deploy it to GitHub Pages using the instructions above. No DevOps required.
