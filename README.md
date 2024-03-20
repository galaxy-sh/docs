# Galaxy.sh docs
Howdy! You've found the GitHub repo for the [Galaxy.sh docs site](https://docs.galaxy.sh/).

## Contributions Welcome!
You are more than welcome to contribute new pages and edits. Just make your changes, and then open a Pull Request on the [GitHub repo](https://github.com/galaxy-sh/docs).

## How This Site Works
1.  The documentation for this site is written in Markdown, with a couple of modifications for [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/), and is hosted on GitHub.
2.  When changes are pushed to the `main` branch, Cloudflare Pages pulls in the branch and builds the site using [Material for MkDocs Insiders](https://squidfunk.github.io/mkdocs-material/insiders/).
3.  The build process then pushes the finished site out across the Cloudflare CDN. Cloudflare handles termination of the `docs.galaxy.sh` subdomain and takes care of HTTPS, etc.
4.  When a build succeeds or fails, we also get a notification in the `#deploys_prod_static` Slack channel.
  
More nitty-gritty info and random notes about our MkDocs build process are over on the [Black Cat Labs Wiki](https://wiki.blackcatlabs.dev/meta/mkdocs/).

## Getting in Touch
Want to contact us about this site or anything contained herein? Send us an email at `wiki+galaxy@ops.blkcat.space`