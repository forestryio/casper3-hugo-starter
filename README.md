# Casper 3 Hugo Starter for Forestry

[Hugo port of the Casper 3 theme](https://github.com/jonathanjanssens/hugo-casper3) originally by Ghost.

<a href="https://app.forestry.io/quick-start?repo=forestryio/casper3-hugo-starter&engine=hugo&version=0.81.0"><img alt="Import this project into Forestry" src="https://assets.forestry.io/import-to-forestryK.svg" />
</a>

## Prerequisites

- Hugo > 0.65.0

## Content Management

![Forestry user interface](static/images/hugo-casper3-forestry.jpg)

This project has been pre-configured to work with [Forestry](https://forestry.io), just [import the repository](https://app.forestry.io/quick-start?repo=forestryio/casper3-hugo-starter&engine=hugo&version=0.81.0) ✨.

Any changes you make will be commited back to the repository.

## Customization

You can customize the theme through the [params in the `config.toml` file](https://github.com/forestryio/casper3-hugo-starter/blob/master/config.toml#L13-L19). Those values are accessible from within Forestry.

## Deployment and hosting with Netlify

Import your site in [Netlify](https://netlify.com)

1. Create a new site in Netlify and import your repository.
2. Set the build command to: `hugo --gc --minify`
3. Set the publish directory to: `public`
4. Make sure to set `HUGO_VERSION` to 0.65.0 or above (tested with latest version)
3. Set the publish directory to: `public`

That's it, now your site gets deployed automatically on `git push` or when saving documents from Forestry.

## Development

```bash
# clone the repository
git clone git@github.com:forestryio/casper3-hugo-starter.git

# cd in the project directory
cd casper3-hugo-starter

# Start local dev server
hugo server
```

For more information, see [official Hugo documentation](https://gohugo.io/getting-started/).
