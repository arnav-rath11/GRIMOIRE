# Releases

---

## v1.0.0 — "Ascension" — 2026-07-20

> *Track. Discover. Ascend.* This is the update where Grimore stops being a prototype and becomes an actual grimoire.

### 🔥 Highlights

**Your reading, gamified.**
The Power Level system is live — Bronze, Silver, Gold and beyond. Every chapter read pushes your bar forward. Your Library and public profile both show it off, because 6,000+ chapters read deserves more than a silent counter.

**Find your people.**
Follow other readers, search by `@tag`, and land on a public profile that actually says something — favorite books, favorite characters, top genre, longest series completed. The Community tab now has a real pulse: discussions, reviews, recommendations, and polls.

**Know your own reading habits.**
The new Analytics dashboard breaks down your favorite genres, manga-vs-manhwa split, completion rate, and reading streak — a full stat screen for your obsession.

**A homepage worth opening.**
The hero got a full rebuild — a single-book auto-advancing Top 10 Trending spotlight replaces the old static floating covers. Five themes now ship out of the box, from obsidian-and-crimson Void Dark to warm Parchment.

**Every author and character, one tap away.**
Full author profiles with complete bibliographies, and every title's cast now has a clickable character grid with expandable full-detail dossiers.

### ✨ New
- Power Level gamification (Bronze → Silver → Gold)
- Public profiles + follow/unfollow + `@tag` search
- Per-title written reviews with star ratings
- Custom user lists
- Analytics dashboard
- Author bio & bibliography pages
- Character grid + full character detail modal
- Community discussions, reviews, recommendations & polls
- 5 UI themes (Void Dark, Abyss, Shadow Realm, Parchment, Ivory Light)
- Notifications for profile likes and new followers
- Privacy controls for reading list visibility

### 🛠️ Improved
- Mobile bottom nav trimmed to essentials (Home / Explore / Sign In-Profile)
- Homepage hero rebuilt around a rotating Trending carousel
- Faster image loading via tuned Next.js image config + debounced search

### 🐛 Fixed
- Mobile rescaling bug on Samsung Internet and similar browsers
- Silent Firestore write failures from undefined social link fields
- Library load race condition
- Firestore listener resets on reauthentication

---

## v0.3.0 — "Rise Above the Pack"

Social features and gamification land: follow/unfollow, public profiles, `@tag` search, and the first version of the Power Level system.

---

## v0.2.0 — "Foundations of Trust"

Firestore security rules hardened, live library stats computation introduced, and the AniList pagination ceiling bug squashed.

---

## v0.1.0 — "First Chapter"

The original scaffold: Next.js + TypeScript + Firebase + Tailwind, AniList/Jikan API integration, and core library tracking.

---

*Full technical details for every release live in [CHANGELOG.md](./CHANGELOG.md).*
