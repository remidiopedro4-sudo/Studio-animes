# Studio Animes AI Motion

Image-to-video MVP using fal.ai Kling 2.6 Pro. Upload an image, prompt motion, choose 5 or 10 seconds, generate, and download.

## Run locally
- npm install
- Set FAL_KEY in .env.local (your fal.ai API key)
- npm run dev

## Vercel setup
Set FAL_KEY in Vercel Project Settings > Environment Variables for Production and Preview. The key is used server-side only. Generation consumes provider credits. This MVP has no login, per-user quotas, or persistent video history yet.
