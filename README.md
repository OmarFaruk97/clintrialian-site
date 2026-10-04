# ClinTrialian website

Static SPA + SEO package.

## Deploy

### Netlify
- Drag this folder to https://app.netlify.com/drop
- Or connect this repo: publish directory `.`

### Vercel
```bash
npx vercel --prod
```

### Cloudflare Pages
Upload folder or connect Git; no build command; output `.`

## Backend API (optional)
```html
<script>window.CLINTRIALIAN_API = { base: 'https://api.clintrialian.com' };</script>
```
