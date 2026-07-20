# Changelog

All notable changes to **Grimore** are documented in this file.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project uses [Semantic Versioning](https://semver.org/).

---

## [Unreleased]

### Planned
- Language & Region settings (currently marked "Soon" in Settings)
- Additional theme presets

---

## [1.0.0] — 2026-07-20

The first full release. Grimore goes from prototype to a complete, gamified reading tracker.

### Added
- **Social layer**: follow/unfollow, public reader profiles, user search by `@tag`
- **Power Level system**: Bronze → Silver → Gold gamification tied to chapters read
- **Per-title reviews**: star rating + written review, postable directly from a title page
- **Custom user lists** for organizing titles beyond Reading/Completed/On Hold/Dropped
- **Mobile navigation**: dedicated bottom nav bar for small screens
- **Privacy controls**: reading list visibility and profile discovery settings
- **Analytics dashboard**: total chapters, completion rate, favorite genres, format breakdown, and reading highlights (longest series, weekly velocity)
- **Five UI themes**: Void (Dark), Abyss, Shadow Realm, Parchment, Ivory (Light)
- **Author pages**: bio, social links, and full bibliography grid per author
- **Character pages**: full cast grid per title, with an expandable full-detail view per character
- **Community hub**: discussions, reviews, recommendations, and polls, filterable by type
- **Notifications**: profile likes, new followers, and system alerts

### Changed
- Landing page hero rebuilt: removed the 3 floating book covers and the "Active Readers" stat, replaced with a single-book auto-advancing **Top 10 Trending carousel**
- Mobile bottom navigation trimmed from 5–6 items down to Home, Explore, and Sign In/Profile
- Trending carousel now swaps to the next of the Top 10 automatically every 5 seconds on loop

### Fixed
- Race condition in `TitleActions.tsx` on library load
- Undefined social link fields causing silent Firestore write failures
- Firestore listener error recovery added to prevent silent resets on reauthentication
- Phone/tablet rescaling bug affecting Samsung Internet and similar mobile browsers

### Performance
- Debounced author search input
- Added `priority` image props to above-the-fold images
- Tuned Next.js image configuration for faster load times
- Introduced `computeLibraryStats()` to derive stats live from library snapshots instead of maintaining mirrored counters

---

## [0.3.0] — Gamification & Social

### Added
- Power Level/gamification system
- Follow/unfollow and public profile pages
- User search by `@tag`

---

## [0.2.0] — Data & Reliability

### Added
- `getLibraryDisplayLabel` utility to centralize Reading / Up to Date / Completed status logic
- Firestore security rules: public profile reads, owner-only writes, with carve-outs for follower/like counts

### Fixed
- AniList API's hard 5,000-result pagination ceiling, clamped to page 208 to prevent crashes

---

## [0.1.0] — Foundation

### Added
- Initial Next.js + TypeScript + Firebase + Tailwind scaffold
- AniList / Jikan API integration for title data
- CSS-variable-driven Tailwind theming system
- Core library tracking (Reading / Completed / On Hold / Dropped)

---

[Unreleased]: #
[1.0.0]: #
[0.3.0]: #
[0.2.0]: #
[0.1.0]: #
