# BS-DASC-1A Date Sheet

A responsive, interactive exam date sheet for BS-DASC-1A. It includes a live countdown, search and status filters, preparation tracking, private browser notes, and Google Calendar links.

## Run locally

No installation or build step is required. Open `index.html` directly, or serve the folder with any static web server:

```bash
npx serve .
```

## Deploy to Vercel

1. Push this repository to GitHub.
2. In the [Vercel dashboard](https://vercel.com/new), import the GitHub repository.
3. Leave **Framework Preset** as `Other` and leave the build command empty.
4. Deploy. No environment variables are required.

You can also deploy with the Vercel CLI:

```bash
npx vercel
```

## Update the exam schedule

Edit the `EXAMS` array near the bottom of `index.html`. Dates use `YYYY-MM-DD` format and countdowns use Pakistan Standard Time (`UTC+05:00`).

Preparation status and notes are stored only in the visitor's browser using `localStorage`; they are not sent to a server.

## License

MIT
