# The Butler

> A ready to use static blog, powered by [Cecil](https://cecil.app) and [Hyde](https://github.com/Cecilapp/theme-hyde).

![Cecil preview](static/images/cecil-preview.png)

## There is a demo?

:arrow_forward: [demo.cecil.app](https://demo.cecil.app/)

## How to use?

### Managing content

#### With [Forestry](https://forestry.io)

If your goal is managing content quickly, and decide later where to deploy to it, use the following button to import the starter blog to Forestry CMS and start editing immediatelly!

[![Import this project into Forestry](https://assets.forestry.io/import-to-forestryK.svg)](https://app.forestry.io/quick-start?repo=cecilapp/starter-blog&engine=hugo)

#### Manually

Edit content files in `content/blog/` directly from your repository.

### Deploy

#### With [Netlify](https://www.netlify.com) ([demo](https://demo.cecil.app))

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Cecilapp/starter-blog)

To use [**Netlify CMS**](https://www.netlifycms.org) ([demo](https://demo.cecil.app/admin/)) you must:
1. enable [Netlify Identity](https://docs.netlify.com/visitor-access/git-gateway/#setup-and-settings) and Git Gateway
2. invite a user
3. connect to `https://<your-blog>.netlify.com/admin/` with the user credentials

#### With [ZEIT Now](https://zeit.co) ([demo](https://cecil-starter-blog.now.sh))

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/new/project?template=https://github.com/Cecilapp/starter-blog)

#### With [Travis CI](https://travis-ci.com)

See [Travis config file](/.travis.yml).

#### With [GitHub Actions](https://github.com/features/actions) ([demo](https://cecilapp.github.io/starter-blog/))

See [GitHub Actions workflow file](/.github/workflows.disabled/build-and-deploy.yml) and rename `workflows.disabled`to `workflows` to enable the workflow.

### Customize your blog

1. Update configuration by editing `config.yml` file
2. Change templates by copying files from [`themes/hyde/layouts/`](https://github.com/Cecilapp/theme-hyde/tree/master/layouts) to your own `layouts/` directory to _override_ them.

## Need Help?

Read the [Cecil's documentation](https://cecil.app/documentation/).

## License

Starter blog is a free software distributed under the terms of the MIT license.

© [Arnaud Ligny](https://arnaudligny.fr)
