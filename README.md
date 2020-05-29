# Scotch Box for Heroku

This repository is a very simple starter kit for PHP development hosted on Heroku.

It is based on [Scotch Box](https://box.scotch.io/) and it has been modified to be "Heroku-ready." What this amounts to is a development environment that can be deployed to Heroku in literally 2 minutes.

## Prerequisites

In order to get everything to work you need to have the following tools installed:

- [Vagrant](https://www.vagrantup.com/) for the Vagrant box (Scotch Box)
- A virtual machine manager like [VirtualBox](https://www.virtualbox.org/)
- The [Heroku Toolbelt](https://toolbelt.heroku.com/) for Heroku deployments

## Getting Started

1. Clone this repository (`git clone https://github.com/julien731/Scotch-Box-Heroku.git`)
2. Create your own Git repository and push the code to it (you'll need that for the Heroku deployment)
2. Run `vagrant up`
3. Start creating your application in the `public` directory

## Deployment

To deploy your application to Heroku:

1. Create a Heroku app: `heroku create`
2. Deploy your application: `git push heroku master`

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
