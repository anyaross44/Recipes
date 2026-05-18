# Anna's Recipe Collection

A personal recipe app built as a single HTML file — no framework, no build step, no database needed.

## Features
- 50 built-in recipes (breakfast, lunch, dinner, snacks, drinks, sweet, BBQ)
- AI recipe import — paste text, a URL, or upload a photo
- Edit any recipe including categories
- Star ratings & favourites
- Photo support per recipe
- Export / print to PDF
- View-only share link for collaborators
- Fully offline-capable after first load

## Deploy to Vercel (2 minutes)

1. Create a new repository on GitHub
2. Upload both files: `recipes.html` and `vercel.json`
3. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
4. Click **Deploy** — no settings to change

Your app will be live at `https://your-project.vercel.app`

## Share as view-only

Add `?view=1` to your URL and share that link. Visitors can browse all recipes but cannot add, edit or delete anything.

Example: `https://your-project.vercel.app?view=1`

## Adding recipes

Tap **＋ Add recipe** and choose:
- **Paste text** — any format, any language (including Russian 🇷🇺)
- **From URL** — paste any recipe website link
- **Photo** — upload a photo of a recipe card, cookbook page or handwritten note

AI formats everything automatically.

## Data storage

All user data (added recipes, edits, ratings, favourites, photos) is stored in your browser's `localStorage`. It persists across sessions on the same device/browser. To back up, use the Export feature to save individual recipes as PDF or text.
