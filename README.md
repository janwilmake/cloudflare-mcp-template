# Image Generation Worker Template

This is a minimal Cloudflare Worker template for generating images using the [workers-mcp](https://github.com/cloudflare/workers-mcp) package and Cloudflare’s Workers AI.

## Features

- Uses the flux-1-schnell model for image generation.
- Minimal configuration and project structure.
- Ready for local development with Wrangler.

## Setup

1. Install dependencies:
   npm install

2. Run the worker locally:
   npm run dev

3. Deploy the worker:
   npm run deploy

## Files

- **src/index.ts**: The worker code.
- **tsconfig.json**: TypeScript configuration.
- **wrangler.toml**: Cloudflare Workers configuration.
- **worker-configuration.d.ts**: Type definitions for the worker’s environment.
- **package.json**: Project dependencies and scripts.
- **.gitignore**: Ignored files.

Happy coding!