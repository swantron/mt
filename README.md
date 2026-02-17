# mt.services

Static landing page for Montana-based consulting services, hosted on Firebase Hosting (free tier).

## Stack

- Static HTML/CSS (single `public/index.html`)
- Firebase Hosting
- Custom domain: [mt.services](https://mt.services)

## Deployment

Deployed via GitHub Actions (`.github/workflows/deploy.yml`) to Firebase Hosting on push to `main`.

## Local Development

Serve locally with the Firebase CLI:

```sh
firebase serve
```
