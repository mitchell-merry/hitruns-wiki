# HitRuns Wiki

## Site URL (Try it Yourself!)

**https://hitruns-wiki.vercel.app/**

## About

Hitman 3 speedrunning wiki. Gameplay tips, Livesplit setup, list of Hitman speedrunning resources, specific strategy tutorials, etc. included.

The site was built with [Docusaurus](https://docusaurus.io/docs), so reference their documentation for the basics of how this site functions.

More specifically, this site was built on a template from [easyops-cn](https://github.com/easyops-cn), so go read [the original repository's README](https://github.com/easyops-cn/docusaurus-search-local/blob/master/README.md) if you want more information on the technical details of the site / want to make refactoring changes.

The site is deployed on [Vercel](https://vercel.com/docs), although it can also be deployed on any static website host.

### Site Features:

HitRuns Wiki has several advantages over the build-in guides on speedrun.com, including:

- More control over the content (guides are still accessible if speedrun.com is down).
- More control over the styling (speedrun.com's Markdown version has some strange idiosyncrasies).
- Website loads faster (not choked full of advertisements as speedrun.com is).
- **Search bar to look up key phrases if you forgot which guide covered what.**

## Site Setup

- `yarn install` to install required node modules.
- `yarn start` to open the dev environment to preview the website.
- `yarn build` to build the website locally (needed if you want to test the search function before deployment).

## Contribution Guidelines

If you are a Hitman speedrunner seeking to contribute and have some basic coding knowledge, you should:

1. Review [Basic Markdown Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
2. Make a Github Account if you don't already have one.
3. [Make a fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
4. Go to Versioned Docs folder (`hitruns-wiki/website/versioned_docs/version-1.0.0`) and make your edits. Edit `hitruns-wiki/website/versioned_sidebars/version-1.0.0-sidebars.json` if you added a new guide.
5. [Make a Pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) for your changes.

If you don't have much coding knowledge but still want to contribute as a Hitman speedrunner:

- Edit the Markdown files specified in Step 4 above, and send me the edited files to me on Discord (Solder#2337).
- Or just tell me what you want changed on Discord.
