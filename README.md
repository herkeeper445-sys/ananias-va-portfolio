# Ananias Jr. D. Catangui — VA Portfolio

A lightweight, eye-catching portfolio built with Next.js and custom CSS. The design uses modern animated UI patterns inspired by component galleries such as Magic UI / Aceternity-style interfaces, but the implementation is custom and intentionally keeps dependencies minimal.

## Important

- The portrait file in `public/ananias-profile.png` is an untouched copy of the photo supplied for the portfolio.
- No passwords, API keys, private IDs, or other credentials are included.
- The project uses a static export (`output: 'export'`), so it can be hosted without a continuously running server.

## Run locally

1. Install Node.js 20+.
2. Open a terminal in this folder.
3. Run:

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`.

## Build for deployment

```bash
npm install
npm run build
```

The generated static site will be in the `out/` folder.

## Easiest free publishing path

1. Create a GitHub repository and upload this project.
2. Import the repository into Vercel.
3. Vercel detects Next.js automatically and publishes it.
4. Your laptop can be turned off; the portfolio remains online.

You can later connect a custom domain in the hosting dashboard.
