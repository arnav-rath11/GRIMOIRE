# Contributing to Grimore

Grimore is built and maintained by a solo developer — which means every reader who spots a bug, hits a weird edge case, or has an idea for a feature is genuinely part of how this project gets better. You don't need to write a single line of code to contribute. Finding bugs and suggesting features **is** a contribution.

---

## 🐛 Found a Bug?

If something breaks, looks wrong, or just feels off — report it. Here's how:

### 1. Check it hasn't already been reported
Go to the **[Issues](../../issues)** tab of this repository and search for keywords related to your problem (e.g. "mobile nav", "login", "chapter count"). If someone's already flagged it, add a 👍 reaction or a comment with any extra detail instead of opening a duplicate.

### 2. Open a new issue
Click **New Issue** → choose the **Bug Report** template if one is available, or just start a blank issue. Include:

- **What happened** — a clear, one-line summary as the title (e.g. "Reading progress bar doesn't update after marking a chapter read")
- **Steps to reproduce** — numbered steps so it can be recreated exactly:
  1. Go to a title page
  2. Click "Reading · Update"
  3. Set chapter to 50
  4. Progress bar still shows 0%
- **Expected behavior** — what you thought would happen
- **Actual behavior** — what actually happened
- **Screenshots or screen recording** — genuinely the most useful thing you can attach. Drag and drop images directly into the issue text box on GitHub.
- **Device & browser** — e.g. "iPhone 14, Safari" or "Windows 11, Chrome 126" — mobile rendering bugs especially depend on this
- **Account context if relevant** — no need for credentials, just note if it happens while signed in, signed out, or on a specific theme

### 3. Submit it
Hit **Submit new issue**. That's it — no need to assign, label, or follow up unless asked.

---

## 💡 Have a Suggestion or Feature Idea?

Same place, different label. Open a **New Issue** in the **[Issues](../../issues)** tab and either pick a **Feature Request** template or start blank. Describe:

- **The problem** you're trying to solve (e.g. "I have no way to sort my library by rating")
- **Your proposed solution**, if you have one in mind
- **Why it'd help** — even a single sentence on your own use case is genuinely useful context

Vague ideas are still welcome. "It'd be cool if..." is a perfectly good way to open an issue.

---

## 🔤 Writing a Good Issue Title

| Bad | Good |
|---|---|
| "bug" | "Character modal doesn't close on mobile Safari" |
| "doesn't work" | "Forgot Password email never arrives" |
| "feature" | "Add sort-by-rating option to Library tab" |

A specific title means faster triage — and a faster fix.

---

## 🧑‍💻 Contributing Code

If you'd like to fix something yourself:

1. **Fork** the repository
2. **Create a branch** off `main` (`git checkout -b fix/reading-progress-bar`)
3. Make your changes — keep commits focused and readable
4. **Open a Pull Request** against `main`, and reference the issue it resolves (e.g. "Fixes #42")
5. Describe what changed and why in the PR description; a before/after screenshot helps a lot for UI changes

Not every PR will be merged as-is, but every one is read and appreciated.

---

## 🙏 A Note

This project is actively developed and iterated on constantly. If you've found something and it feels small — report it anyway. Small bugs compound, and the people who take the time to flag them are the reason Grimore keeps getting better.

Thanks for reading. Thanks for tracking your reading here.
