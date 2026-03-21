---
description: Deploy the InsurXProtect website to Vercel
---

# Deploy to Vercel

This workflow deploys the InsurXProtect static website to Vercel production.

## Steps

// turbo-all

1. Commit any pending changes:
```bash
cd /Users/brandonpriest/brandons_hub/projects/insurance-website && git add -A && git diff --cached --quiet || git commit -m "Update site"
```

2. Push to GitHub:
```bash
cd /Users/brandonpriest/brandons_hub/projects/insurance-website && git push origin main
```

3. Deploy to Vercel production:
```bash
cd /Users/brandonpriest/brandons_hub/projects/insurance-website && vercel --prod --yes
```

4. Report the live URL to the user from the Vercel output.
