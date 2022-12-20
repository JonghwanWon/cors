# Tiny proxy server running on Vercel.

## Using the Vercel CLI
To deploy from the command line you must first install the [Vercel CLI globally](https://vercel.com/docs/cli#installing-vercel-cli).

```bash
npm i -g vercel
```
Run the [vercel](https://vercel.com/docs/cli/deploying-from-cli) command to deploy your project.

```bash
vercel
```

[Declare an environment variable.](https://vercel.com/docs/concepts/projects/environment-variables#declare-an-environment-variable)
`APP_URL=YOUR_APP_URL_HERE`

After the first deployment this command will deploy to a preview branch. You will need to include --prod to push changes directly to the live site for future deployments.

```bash
vercel --prod
```