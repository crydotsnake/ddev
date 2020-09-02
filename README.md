你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
# ddev

[![CircleCI](https://circleci.com/gh/drud/ddev.svg?style=shield)](https://circleci.com/gh/drud/ddev) [![Go Report Card](https://goreportcard.com/badge/github.com/drud/ddev)](https://goreportcard.com/report/github.com/drud/ddev) ![project is maintained](https://img.shields.io/maintenance/yes/2020.svg)

![ddev logo](images/ddev_logo.png)

ddev is an open source tool that makes it simple to get local PHP development environments up and running in minutes. It's powerful and flexible as a result of its per-project environment configurations, which can be extended, version controlled, and shared. In short, ddev aims to allow development teams to use Docker in their workflow without the complexities of bespoke configuration.

## Getting Started

1. **Check System Requirements:** We support recent versions of macOS, Windows 10, and Linux distributions that will run Docker (ddev requires Docker and docker-compose). ([more info here](https://ddev.readthedocs.io/en/stable/#system-requirements)).
2. **Install ddev:** [Options include](https://ddev.readthedocs.io/en/stable/#installation) macOS homebrew (recommended), an install script, or manual installation.
3. **Read the Basics and Choose a CMS Quick Start Guide:**
    * [DDEV-Local Basics](https://ddev.readthedocs.io/en/stable/users/cli-usage)
    * [PHP (Generic Project) Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage/#php-project-quickstart)
    * [WordPress Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#wordpress-quickstart)
    * [Drupal 6 and 7 Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#drupal-6/7-quickstart)
    * [Drupal 8 Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#drupal-8-quickstart)
    * [Drupal 9 Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#drupal-9-quickstart)
    * [Backdrop Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage/#backdrop-quickstart)
    * [TYPO3 Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#typo3-quickstart)
    * [Magento 1 Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#magento-1-quickstart)
    * [Magento 2 Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#magento-2-quickstart)
    * [Laravel Quickstart](https://ddev.readthedocs.io/en/stable/users/cli-usage#laravel-quickstart)

Having trouble? See our [support options below](#support). You might have trouble if [another local development tool is already using port 80 or 443](https://ddev.readthedocs.io/en/stable/users/troubleshooting/#unable-listen).

## Partial Feature List

* Quickly create multiple local web development environments based on code repositories.
* Import database for a project you're working on.
* Import upload files to match the project (e.g. Drupal's sites/default/files or WordPress's wp-content/uploads).
* Pantheon integration - grab a Pantheon archive and work locally with the database and files.
* Run commands within the docker environment using `ddev exec`.
* View logs from the web and db containers.
* Use `ddev ssh` to explore the linux environment inside the container.
* List running projects with `ddev list`.
* Snapshot databases with `ddev snapshot`.
* Temporarily share your development website with other using `ddev share`.
* Trusted HTTPS support

Just running `ddev` will show you all the commands.

## Support

We love to hear from our users and help them be successful with ddev. Support options include:

* [ddev Documentation](https://ddev.readthedocs.io) and [faq](https://ddev.readthedocs.io/en/stable/users/faq/)
* [ddev StackOverflow](https://stackoverflow.com/questions/tagged/ddev) for support and frequently asked questions. We respond quite quickly here and the results provide quite a library of user-curated solutions.
* [ddev issue queue](https://github.com/drud/ddev/issues) for bugs and feature requests
* The [gitter drud/ddev channel](https://gitter.im/drud/ddev) (it's easy to log in many diffferent ways)
* The `#ddev` channels in [Drupal Slack](https://www.drupal.org/slack), [TYPO3 Slack](https://my.typo3.org/index.php?id=35) for interactive, immediate community support.
* [ddev-contrib](https://github.com/drud/ddev-contrib) repo provides a number of vetted user-contributed recipes for extending and using ddev. Your contributions are welcome.
* [awesome-ddev](https://github.com/drud/awesome-ddev) repo has loads of external resources, blog posts, recipes, screencasts, and the like. Your contributions are welcome.
* [Twitter with tag #ddev](https://twitter.com/search?q=%23ddev&src=typd&f=live) will get to us, but it's not as good for interactive support, but we'll answer anywhere.

## Additional Information

* **Contributing** See the "How can I contribute" question in the [FAQ](https://ddev.readthedocs.io/en/stable/users/faq/).
* **Roadmap:** See the [ddev roadmap](https://github.com/drud/ddev/wiki/roadmap). We love your input! Make requests in the [ddev issue queue](https://github.com/drud/ddev/issues).
