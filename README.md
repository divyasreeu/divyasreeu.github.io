# Cini — website

This repository hosts the public web pages for **Cini**, an iOS app I'm building for ranking and tracking the movies and TV shows you watch. It is served with GitHub Pages at **https://divyasreeu.github.io/**.

It contains only the app's website, not the app itself:

| Page | Purpose |
|---|---|
| [`index.html`](index.html) | Home page: what Cini is, plus a support contact |
| [`privacy.html`](privacy.html) | Privacy policy, linked from the App Store listing and the Google sign-in consent screen |
| [`terms.html`](terms.html) | Terms of use, including the community rules on objectionable content and abuse |
| [`style.css`](style.css) | Shared styling (light and dark mode) |

The app's source code lives in a separate repository.

## About Cini

Cini is a social app for people who love movies and TV. Instead of star ratings, you rank titles by comparing them head to head, and your list builds itself from those choices. You can follow friends, see what they're watching and how they ranked it, and plan watch nights together.

Some of what it does:

- **Head-to-head ranking:** each new title is placed into your list through a short series of "which did you like more?" comparisons, and scores come from its position.
- **Social feed:** follow friends, react, comment with @-mentions, and get notified when people you follow rank something you've seen.
- **Watchlist and progress tracking:** save titles, track what you're currently watching, and plan watch nights with friends.
- **Recommendations:** suggestions based on what you've ranked highly.
- **Safety and privacy:** private accounts, reporting and blocking, and sign in with Apple or Google.

### Built with

- **React Native + Expo** (TypeScript, Expo Router) for the iOS app, with a web build used during development
- **Supabase**: Postgres with row-level security for every table, SQL functions, triggers, Edge Functions, auth and storage
- **TMDB API** for movie and TV data

## Contact

Questions or support: [cinisupport@gmail.com](mailto:cinisupport@gmail.com)
