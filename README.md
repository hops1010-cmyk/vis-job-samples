# vis-job-samples
samples of designs

## Deploy to Vercel

This is a static site. Vercel can publish it directly from the repository root; no build command or framework preset is required.

### Git integration

1. Import this repository from the [Vercel dashboard](https://vercel.com/new).
2. Leave the Root Directory as `.` and select **Other** for Framework Preset.
3. Leave Build Command and Output Directory empty, then deploy.

Vercel will create a production deployment for the connected branch (usually `main`) and preview deployments for pull requests. Pushes to the production branch update the hosted site.

### Vercel CLI

From the repository root, run `npx vercel` and follow the prompts to link the project and create a preview deployment. Run `npx vercel --prod` to publish a production deployment. The CLI will prompt you to authenticate if needed.
