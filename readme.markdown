# FathomNet User Interface

https://fathomnet-ui.tobbi.co

This is a space to document and test UI elements for the FathomNet project:
https://fathomnet.org

It’s also a helpful place to work, while making changes to the CSS.

* [How to download the latest CSS](#how-to-download-the-latest-css)
* [How to make changes](#how-to-make-changes)
* [How to develop locally](#how-to-develop-locally)
* [Handy guides](#handy-guides)

## Deployment status

https://github.com/jimthoburn/fathomnet-ui/deployments

## How to download the latest CSS

The individual CSS files for the project are combined into a single, downloadable file:  
https://fathomnet-ui.tobbi.co/fathomnet-ui-v0.2.0-beta/fathomnet-ui.css

## How to make changes

The website is published with [GitHub Pages](https://pages.github.com), and the files are generated with [Jekyll](http://jekyllrb.com).

As you make changes and commit/push them to GitHub, the [website](https://fathomnet-ui.tobbi.co) will automatically update.

For example, if you [edit the icon page](elements/icon.markdown) on GitHub, and then press the “Commit changes” button–you should see your changes on the [icons page](https://fathomnet-ui.tobbi.co/elements/icon/) of the website within a few minutes.

### How to edit the CSS

The single, downloadable CSS file is generated from individual CSS files, which can be found in these folders:
1. [elements](elements)
2. [components](components)
3. [pages](pages)

For example, you can edit the CSS for the icons in this file:
[elements/icon.css](elements/icon.css)

### How to add a new CSS file

You can add a new file anywhere in the project, and then link to it from these two files:
1. [css/ui.css](css/ui.css)
2. [fathomnet-ui.css](fathomnet-ui.css)

## How to develop locally

If you want to see a preview of your changes while you work, you can [run a Jekyll server](https://jekyllrb.com) on your local machine. [Installing Ruby and Jekyll](https://jekyllrb.com/docs/installation/) is a good place to start.

After you have Jekyll installed, you can clone this project with [Git](https://git-scm.com) or [GitHub Desktop](https://desktop.github.com)…

```
git clone https://github.com/jimthoburn/fathomnet-ui.git
```

And then start running the Jekyll application like this...

```
bundle exec jekyll serve
```

## Handy guides

* [Markdown](https://guides.github.com/features/mastering-markdown/)
* [YAML](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html)
* [YAML Checker](http://www.yamllint.com)
* [Liquid](https://shopify.github.io/liquid/)
* [Liquid for Designers](https://github.com/Shopify/liquid/wiki/Liquid-for-Designers)
* [Jekyll](https://jekyllrb.com/docs/home/)
* [GitHub Pages](https://pages.github.com)
