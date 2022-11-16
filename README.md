# Focus Consultiong environmentaljustice.gov Demo

The demo can be view here: http://focusconsulting.io/ej-gov-demo/

This repository contains the demo code for the environmentaljustice.gov site. It consists of a simple site generated via Jekyll and styled with components from USWDS. The content is powered by a headless CMS; content can be added via the site and as well as through the admin pages of the CMS. Additionally, other fields like tags and files can be added via the admin pages.

## Getting started

Below are requirements and steps to start the site locally.

### Requirements

In order to run the site locally, you'll need to have Ruby 2.7 installed.
Ruby installs can be managed with [asdf](https://asdf-vm.com/) and [asdf-ruby](https://github.com/asdf-vm/asdf-ruby)

1. Install the required dependencies

```sh
gem install jekyll bundler
```

2. Start the site

```sh
bundle exec jekyll serve
```

## Deploying

The site is deployed on Github pages via the [jekyll-build-pages](https://github.com/actions/jekyll-build-pages) action which is triggered when the `main` branch is updated

## Contributing

Though this is just a demo site, any contributions are welcome. Please submit a pull request if you would like to make a change.

## Tools used

-   [Jekyll](https://jekyllrb.com/)
-   [USWDS](https://designsystem.digital.gov/)
-   [Directus](https://directus.io/)
