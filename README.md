# VLCTechFest2024

Website for the VLCTechFest2024 event.
Created with ❤ by volunteers.

## How to use

Ruby 2.7.3 required. You must use the Github Pages Gem bundled Jekyll in order to make it work properly.

To build the site and serve it through the default 4000 port:

```
$ bundle install
$ bundle exec jekyll serve --watch
```

If you rather use Docker, you can start a functional working environment by issuing:

```
$ docker run -it -v $(pwd):/srv -p 1221:1221 -w /srv ruby:2.7.3 bash
# bundle install
# bundle exec jekyll serve --host 0.0.0.0 --watch
```

## Multilingual Jekyll

Based on https://github.com/sylvaindurand/jekyll-multilingual. For more info visit  the [**Making Jekyll multilingual**](https://www.sylvaindurand.org/making-jekyll-multilingual/) article

## Adding a new community

When adding a new community, there are two steps that need to be done:

1. Add the community logo (preferably in SVG format) to `images/communities/`
2. Modify the `_data/communities.yaml` file, with the next fields: `name`, `image` (the logo image name, with no path) and `links`: a list of social media links.

## Adding a new collaborator

When adding a new collaborator, there are two steps that need to be done:

1. Add the collaborator logo (preferably in SVG format) to `images/companies/`
2. Modify the `sponsors` section in the `_data/companies.yaml` file, with the next fields: `name`, `image` (the logo image name, with no path) and `link`.

## Adding a new sponsor

When adding a new sponsor, there are two steps that need to be done:

1. Add the company logo (preferably in SVG format) to `images/companies/`
2. Modify the `collaborators` section in the `_data/companies.yaml` file, with the next fields: `name`, `image` (the logo image name, with no path) and `link`.

## Theme

Original theme created over the [Jekyll default theme](https://github.com/jglovier/jekyll-new).


## License

MIT © VLCTechHub


## Question?

hola@vlctechhub.org
