# Takshashila Institution — PGP Executive Brochure

A polished, self-contained HTML brochure and corporate proposal for the **Post Graduate Programme in Public Policy (PGP)** by [The Takshashila Institution](https://takshashila.org.in).

Targeted at C-Suite and Board-level executives navigating government regulation, geopolitical disruption, and policy-driven market change.

---

## 🚀 Live Site

Once deployed via GitHub Pages, the brochure will be available at:

```
https://<your-username>.github.io/<your-repo-name>/
```

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | The complete, self-contained brochure (all images & fonts embedded) |
| `README.md` | This file |

> The `index.html` is fully self-contained — all faculty photos are embedded as base64 data URIs and fonts are loaded from Google Fonts. No additional assets or build steps are required.

---

## 🛠️ Deploy to GitHub Pages

### Option 1 — Via GitHub UI (simplest)

1. Create a new repository on [github.com](https://github.com/new)
2. Upload `index.html` and `README.md`
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Choose `main` branch and `/ (root)` folder
6. Click **Save** — your site will be live within a minute

### Option 2 — Via Git CLI

```bash
# 1. Initialise a local repo
git init
git add index.html README.md
git commit -m "Initial commit: Takshashila PGP brochure"

# 2. Connect to your GitHub repo
git remote add origin https://github.com/<your-username>/<your-repo>.git
git branch -M main
git push -u origin main

# 3. Enable GitHub Pages in Settings → Pages → Source: main / root
```

### Option 3 — GitHub CLI

```bash
gh repo create takshashila-pgp-brochure --public --source=. --push
# Then enable Pages in repo settings
```

---

## ✏️ Updating Content

All content is in `index.html`. Key sections to edit:

| Section | Search for (in HTML) |
|---------|----------------------|
| Cover title | `Navigating the` |
| Programme dates | `20 June 2026` |
| Fee | `1,95,000` |
| Faculty bios | `fac-bio` class |
| CTA text | `Start Your Policy` |
| Contact address | `Cobalt Building` |
| Apply link | `formbricks.com` |

---

## 🎨 Brand Colours

| Name | Hex | Usage |
|------|-----|-------|
| Lama | `#620d3c` | Primary — backgrounds, headings |
| Marigold | `#f1a222` | Accent — labels, borders, CTAs |
| Nimbu | `#fbe800` | Highlight — cover stats, italics |
| Slate | `#040404` | Body text |
| White | `#ffffff` | Backgrounds |

---

## 📄 Downloads

The PDF versions of this brochure can be found in the repository or generated from the HTML using any browser's **Print → Save as PDF** function (set margins to None, enable Background graphics).

---

## 📬 Contact

**Takshashila Institution's Policy School**  
2nd Floor, 46/1, Cobalt Building, Church Street, Bengaluru – 560001  
[school.takshashila.org.in/pgp](https://school.takshashila.org.in/pgp)
