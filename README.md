Following the steps below, you can setup a personal website on either a custom domain or a free github.io subdomain. All website content can be added/updated through GitHub.

# Getting Started

## Fork Template

Fork one of the following template repos:

https://github.com/grindieweb/hugo-coder-template

https://github.com/grindieweb/hugo-risotto-template

## Setup GitHub Pages Deployment

Setup GitHub pages to deploy from GitHub actions and optionally setup a custom domain.

Go to your repo settings, select Pages, select a deployment source of "GitHub Actions"

If you wish to setup a custom domain, copy the \*.github.io URL under the Custom Domain heading and setup a CNAME/ALIAS (for apex) pointing to your subdomain. By default, this is YOURUSERNAME.github.io.

Paste the domain/subdomain you setup into the custom domain field in GitHub and click save to perform the DNS check.

## Deploy Site

Go back to the Actions tab in your forked repo and enable the pre-provided GitHub action.

Go to the Code tab and open the `hugo.toml' file at the root of the repository. Edit the "baseURL" to match the domain/subdomain you setup earlier.

Save and commit the change.

Go back to the Actions tab and wait for the action to deploy.

## Site is Live

Go check our your new live website!!!




