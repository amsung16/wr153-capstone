# wr153-capstone

# Encouraging Word

A simple, browser-based interactive tool that offers biblical encouragement to people experiencing loneliness. Users can select from common feelings or describe their emotions in their own words, and receive a relevant Bible verse and a short faithful reflection.

This project was built as a capstone for a writing course at Boston University, based on a proposal submitted to the Department of Religion exploring the intersection of technology, loneliness, and Christian faith.

---

## Background

Modern society — especially following COVID-19 — has seen a sharp rise in loneliness. Yet loneliness is not a new human experience. Scripture acknowledges it from the very beginning of creation:

> *"It is not good that the man should be alone."* — Genesis 2:18 (ESV)

This tool is a small attempt to connect people's feeling of loneliness with the comfort found in God's Word. It is not a replacement for community, pastoral care, or professional support — it is simply an accessible space where someone can hear a biblical reminder that they are not alone.

---

## Features

- **Toggle-based feeling selector** — choose one or more feelings from 8 options
- **Multi-feeling logic** — when multiple feelings are selected, the app finds a single verse that speaks to that combination rather than listing them separately
- **Free-text input** — users can describe their feelings in their own words; the app uses keyword pattern matching to find the most relevant verse
- **Fallback response** — if no keyword match is found, a general verse of comfort (Psalm 23) is shown with a message that their words were still heard
- **No login, no account, no data collection** — fully private and runs entirely in the browser
- **No internet connection required** — once the file is downloaded, it works offline

---

## How to Run

No installation or setup is needed.

1. Download `index.html`
2. Double-click the file — it opens directly in any web browser
3. That's it

To edit the code, open `index.html` in any text editor or in VS Code. The file contains HTML, CSS, and JavaScript all in one place.

---

## How to Deploy (free)

To share the app as a live website:

**Option A — Netlify (easiest)**
1. Go to [netlify.com](https://netlify.com) and create a free account
2. Drag and drop `index.html` onto the Netlify dashboard
3. Netlify gives you a shareable URL instantly

**Option B — GitHub Pages**
1. Create a free account at [github.com](https://github.com)
2. Create a new repository and upload `index.html`
3. Go to Settings → Pages and enable GitHub Pages
4. Your site will be live at `https://yourusername.github.io/your-repo-name`

---

## Bible Verses Used

All verses are from the English Standard Version (ESV).

| Feeling | Verse |
|---|---|
| I feel invisible | Matthew 10:29–31 |
| I feel forgotten | Isaiah 49:15–16 |
| I feel isolated | Romans 8:38–39 |
| I feel misunderstood | Psalm 139:1–2 |
| I feel abandoned | Deuteronomy 31:6 |
| I feel like a burden | Matthew 11:28–29 |
| I feel hopeless | Psalm 42:11 |
| I feel afraid | Isaiah 41:10 |

**Combined verses** (shown when multiple feelings are selected together):

| Combination | Verse |
|---|---|
| Invisible + forgotten | Psalm 84:3 |
| Isolated + hopeless / abandoned | Psalm 34:18 |
| Abandoned + like a burden | Psalm 55:22 |
| Misunderstood + hopeless + afraid | Hebrews 4:15–16 |
| Invisible + isolated + abandoned | Psalm 139:7–8 |
| Fallback (no match) | Psalm 23:1–3 |

---

## Project Structure

```
index.html      # The entire application — HTML, CSS, and JavaScript in one file
README.md       # This file
```

---

## Limitations

- The free-text pattern matching is keyword-based and simple. It will not understand complex or indirect expressions of emotion.
- The tool is designed specifically around loneliness and Christian faith. It is not equipped to handle serious mental health crises. If you or someone you know is in crisis, please reach out to a trusted person, pastor, or mental health professional.
- The reflections on each verse represent a faithful but non-professional interpretation. They are not a substitute for pastoral guidance or theological study.

---

## Planned Future Improvements

- Expanded keyword library for richer pattern matching
- Additional feelings and verses
- Voice-based prayer feature
- Support for more emotional categories beyond loneliness
- Accessibility improvements (screen reader support, larger text option)

---

## Built With

- HTML
- CSS
- JavaScript (vanilla — no frameworks or libraries)

---

## Author

Aiden Sung
Boston University, College of Data Science — Class of 2029
