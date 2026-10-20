# Vengeance

Public website for Vengeance Client, the Minecraft 1.21.11 PvP client. Vengeance V2 is the new build. The original client is still available on the download page.

## Run it on your computer

You need Node.js 22 or newer.

```bash
npm install
npm run dev
```

Open http://localhost:8080

## Build check

```bash
npm run build
```

`DATABASE_URL` is not required. The migrate step skips itself when that variable is missing.

## Put it on GitHub

1. Create a new **Public** repository on GitHub. Do not add a README there.
2. Upload the contents of this folder (not the zip itself). `node_modules` should not be uploaded. If you use git:

```bash
git init
git add .
git commit -m "Vengeance site"
git branch -M main
git remote add origin https://github.com/YOUR_NAME/vengeance.git
git push -u origin main
```

## Deploy on Vercel for free

1. Sign in at https://vercel.com with GitHub.
2. Add New → Project → import this repository.
3. Leave the build settings as they are. The build command is `npm run build`.
4. Deploy.
5. Open the project Settings → Deployment Protection and turn **Vercel Authentication** off, so anyone with the link can open the site.

The live URL looks like `https://your-project.vercel.app`.

## What is in the download buttons

- Vengeance V2: `public/downloads/VC-V2-1.21.11.jar`
- Original Vengeance: `public/downloads/VC-1.21.11.jar`

Both are for Minecraft 1.21.11.
