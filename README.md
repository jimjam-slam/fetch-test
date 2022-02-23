# fetch-test

Quick example of downloading ZIP files using Fetch. Example deploy for a Jamstack (eg. Cloudflare Pages)

(Check the Developer Tools to see `console.log` messages to verify the Fetches!)

## Deploy with Cloudflare Pages (or Netlify, or similiar)

1. Connect your GitHub or GitLab account

2. Select a repository to deploy (note that it doesn't need to be publicly accessible: you authorise Cloudflare Pages to access the repo in the previous step)

3. Choose:

- the branch on the repo to deploy.
- if you would normally build the site using a command (eg. `npm run build`), you can put that under "build command" (or leave it blank if the site is already built).
- if the built output is (or will be, following build) i na subdirectory, like `public`, put that under "build output directory"

4. Hit Save & Deploy

5. The site now uploads and, if you added a build command, builds.

6. Once it's done, it becomes available at an automatically generated address. Whenever you commit to the branch designated above, it updates.

7. Now you can set up a custom domain. Go to the project view and select the :custom domains" tab.

8. Select "set up a custom domain"

9. Type the domain in.

10. Unfortunately, unlike some other services (eg. Netlify), Cloudlfare Pages needs DNS to be transferred to Cloudflare, so you'll need to go through that process.
