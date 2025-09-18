
# AIsend Interactive Website

This is the Next.js interactive website for AIsend, featuring custom AI agents with unique personalities.

## Features

- Interactive agent demos with text-to-speech
- Custom agent builder form
- Responsive design with Tailwind CSS
- Integration with Botpress chat widget
- HubSpot contact form integration

## Deployment Steps

### For GitHub + Vercel:

1. **Prepare Repository:**
   - Delete all files in your GitHub repository
   - Upload all files from this package (except node_modules)
   - Commit and push

2. **Deploy to Vercel:**
   - Import project from GitHub in Vercel
   - Set Framework Preset to "Next.js"
   - Set Install Command to: `npm install --legacy-peer-deps`
   - Deploy

3. **Add Environment Variables in Vercel:**
   ```
   ABACUSAI_API_KEY=2fecabd1c70a4666a9fdf8e395bf6bcc
   HUBSPOT_API_KEY=CiRuYTEtYTBkZC03NzY0LTQ1NGQtYWFhNi1kMGJmNjg4MTc5MGYQp6nCFxjmlPYkKhkABeaRguY6tCGaUXGIMu466fApg9spGnXYSgNuYTE
   BOTPRESS_TOKEN=bp_pat_UVxxv6T6KPDV5xCoK8u9ImMcDeXpt8XCarQz
   NEXTAUTH_URL=https://your-domain.vercel.app
   ```

4. **Connect Custom Domain:**
   - Add domain in Vercel dashboard
   - Update DNS in GoDaddy as instructed by Vercel

## Local Development

```bash
npm install --legacy-peer-deps
npm run dev
```

## Build Issues Fixed

- ✅ ESLint version compatibility (using 8.57.1)
- ✅ Next.js configuration simplified
- ✅ npm legacy-peer-deps for dependency resolution
- ✅ TypeScript compilation errors resolved
- ✅ All required dependencies included
