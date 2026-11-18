Following the steps below, you can setup a personal website on either a custom domain or a free github.io subdomain. All website content can be added/updated through GitHub.

# Getting Started

Fork this repo :)

## Setup GitHub Pages Deployment

Next, we will setup GitHub pages to deploy from GitHub actions and optionally setup a custom domain.

Go to your repo settings, select Pages, select a deployment source of "GitHub Actions"

If you wish to setup a custom domain, copy the \*.github.io URL under the Custom Domain heading and setup a CNAME/ALIAS (or apex) pointing to your subdomain. By default, this is YOURUSERNAME.github.io.

Paste the domain/subdomain you setup into the custom domain field in GitHub and click save to perform the DNS check.

## Deploy Site

Go back to the Actions tab in your forked repo and enable the pre-provided GitHub action.

Go to the Code tab and open the `hugo.toml' file at the root of the repository. Edit the "baseURL" to match the domain/subdomain you setup earlier.

Save and commit the change.

Go back to the Actions tab and wait for the action to deploy.

## Site is Live

Go check out your new live website!!!

To add a new post, simply add a .md file to your content/posts folder and commit. The site will rebuild and publish your changes.

# Adding a CMS

A CMS is a Content Management System. While you can add new posts manually through the GitHub interface in markdown files, a CMS helps you managed content, images, files and more.

A FREE easy CMS that deploys in one-click is [PagesCMS](https://pagescms.org)

## Install PagesCMS

1. Go to https://pagescms.org
2. Click Sign-in in the top right corner.
3. Click "Sign in with GitHub"
4. Authorize the app to see your GitHub profile
5. Click "Install GitHub App"
6. Select "Only select repositories" and select your website repo.
7. Select "Install"
8. The PagesCMS dashboard should now load, select your repo to open in the CMS.
