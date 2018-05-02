<p align="center"><a href="https://craftcms.com/" target="_blank"><img width="312" height="90" src="https://craftcms.com/craftcms.svg" alt="Craft CMS"></a></p>

## About Craft CMS

Craft is a content-first CMS that aims to make life enjoyable for developers and content managers alike. It is optimized for bespoke web and application development, offering developers a clean slate to build out exactly what they want, rather than wrestling with a theme.

Learn more about Craft at [craftcms.com](https://craftcms.com).

## About this repo

This is a starting point for my personal Craft 3 work.

The site has a basic template structure with a home page and an about page.

The workflow is written in Larvel Mix. The workflow does several things out of the box.

1. Compiles youe ES6 JS to ES5.
2. Utilites Tailwind CSS.
3. Purges your Tailwind CSS and other CSS of any unused code based on your Twig templates. 
4. It will genearte critical CSS for the home page and about page out of the box. You'll need to include those critical CSS files yourself in your templates though. I'll fix that eventually in this repo. You can add more pages to create critical CSS for in the `webpack.mix.js` file.

## Getting started

I have not tested these instruction yet since this is a new repo as I create this. 

To being, make a new `.env` file based on the `.env.example` file in the repo. You'll need your local DB info for that.

You will need to run 2 things in your command line to get this up and running.

1. composer install
2. npm install
