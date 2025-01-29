# Hugo Up Business Theme

Up Business is a clean and modern landing page, inspired on light illustrations
with a modern look, that can be used for companies or to showcase a product.

![Screenshot](https://github.com/jmeridth/up-business-theme/blob/main/images/screenshot.png)

## Live Demo

See [here](https://jmeridth.github.io/up-business-theme/).

## Quick Start

If you are creating a new website, the quickest way to get up and running is to
clone the theme into your themes folder:

```bash
git clone git@github.com/jmeridth/up-business-theme.git themes/up-business-theme
```

The folder `hugoBasicExample` contains a working version of a website with the
theme. It includes: the configuration file `config.yaml`, the content folder
`content` and the `data` folder. It's a good idea to copy this over to the
project folder to get an initial version of the website up and running.

You can also use it as s Git submodule. If you are starting a new website:

```
hugo new site NewSite
cd NewSite
git init
git submodule add https://github.com/jmeridth/up-business-theme.git themes/up-business-theme
rm hugo.toml
cp themes/up-business-theme/hugoBasicExample/config.yaml .
cp -a themes/up-business-theme/hugoBasicExample/content/* content/
cp -a themes/up-business-theme/hugoBasicExample/data/* data/
```

Now `hugo server` will start the local development server with a working
version of the website with the theme.

## Credits

Original repo was created by [Iago Bozza](https://gitlab.comwriteonlyhugo/up-business-theme) but has been inactive for a while and doesn't seem to merge in new merge requests. I'm more than willing to move this repo's content back to his repo if he wants to pick it back up.

Hugo Up Business Theme is based on a [Figma Design by Abell
Vo](https://www.figma.com/community/file/1022163547182520272).

## License

Up Business is licensed under the MIT license.
