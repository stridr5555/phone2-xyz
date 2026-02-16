# Phone2.xyz

Speed-to-lead storytelling site for the Thumbtack safety net service. It explains the missed-call automation, lead qualification, and high-touch Retell + Twilio workflow.

## Local development

```bash
npm install -g serve
serve .
```

(Simply open `index.html` if you prefer.)

## Deployment

1. Push this repository to GitHub (see `gh repo create` command below).
2. Connect the repo to Vercel and set the production domain to `phone2.xyz`.
3. Use the `vercel --prod` command to deploy whenever the site changes.

```bash
gh repo create phone2-xyz --public --source . --remote origin --push --confirm
vercel --prod --confirm
```

The `vercel.json` file is already configured to use clean URLs and the `phone2-xyz` alias.
