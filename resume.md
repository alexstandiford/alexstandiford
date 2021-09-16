# Alex Standiford

## A self-driven, adventurous web developer
_Knowledgeable about modern web technologies, and thirst to apply it somewhere great._

## Work Experience:

### Sandhills Development:
**Senior Developer – January 2019 – September 2021**

My primary role at Sandhills development was being a senior developer for their top-grossing product, [AffiliateWP](https://www.affiliatewp.com). While working on this plugin, I played a key role in reducing existing technical debt, and building new features, as well as a key person on the team who advises on architectural decisions.

* Played a key role in the development of their most-recent plugin release, Affiliate Portal.
* Advised on architectural code decisions, and optimizations
* Conceptualized modern, advanced Javascript architecture for the core plugin as well as the addons.
* Wrote extensive unit tests, and participated in TDD practices
* Participated in code reviews, and advised junior level-roles.

#### Technologies Used:

* E-Commerce
* WordPress REST API
* Advanced PHP architecture
* React
* AlpineJS
* REST APIs
* Node.JS
* PHPUnit
* Git

## American Scientific WooCommerce Product Sync

**Contractor - May 2018**

The goal of the API Product Sync utility was to build a background utility that synchronizes the data from an Oracle server to thousands of WooCommerce products. This sync runs in the background, and automatically updates WooCommerce data whenever the data is updated in American Scientific's internal system.

Developed a background task to automatically keep track of what products are out of sync.

Added a way to force an item to sync should it fail to-do so.

Developed using an early version of my WordPress framework, [Underpin](github.com/underpin-WP/underpin).

* WooCommerce
* NetSuite & SOAP

## Cerebro API WooCommerce Integration:

**Contractor – January 2018**

The goal of the Cerebro API Integration was to provide their team with a way to automatically create orders in WooCommerce using a single API endpoint. This endpoint was configured to pass a single JSON object containing all product data, pricing, and any other data needed to place the order, and it then created the products if they didn’t exist, overwrote the price if it didn’t match, placed the order, and finalized the purchase.

Developed a WordPress-based custom API endpoint that allows the client to overwrite WooCommerce data, place orders, and create new users from a single API call. This API call reduced the amount of code Cerebro’s Node.js team needed to write to integrate from WooCommerce drastically

Developed using good PHP practices and OOP paradigms including class abstractions and extensions
Implemented detailed error reporting throughout the stack, providing the developer with critical information if the sync fails.
Technologies Used:

* WooCommerce
* WordPress REST API
* Modern PHP
* Node.JS
* Git

## Crain Communications:

**Contractor – February 2017**

Crain Communications came to me because they have about 6 or so WordPress-based websites that were each built by different freelancers. As such, each website used a completely different set of tools and design paradigms, making it a nightmare for Crain to maintain. I was hired to standardize these websites, and build tools that make it much easier to maintain long-term.

Redesigned utech-polyurethane.com from the ground up using the WordPress Genesis theme framework

Built out a custom WordPress plugin that renders email templates for Crain’s internal email system.

Built out a custom WordPress plugin that makes managing their Google DFP ads easier. This was used on 3 of their websites and has expanded into more than one ad framework. Written in PHP 

Integrated with a third-party content lockdown system to prevent visitors from viewing their content after so many page views

Built a WordPress plugin that makes it quick and easy to manage and enqueue commonly-used Crain scripts, such as tracking scripts and some custom GDPR scripts.
Technologies Used

* Gulp
* Grunt
* Javascript
* React
* WP-CLI
* WordPress
* PHP
* Git
* Travis CI and Unit Testing with PHP Unit
* Webpack
* SCSS/CSS
* Node.JS
* jQuery
* Foundation Emails (for email templating)Webpack
* BuddyPress
* SCSS
* Node.JS

## Personal Projects:

### alexstandiford.com

Built a single page blog application using an Express app that aggregates blog content written by me all over the web. The website is built using React, and React Router.

All of the content on this website is fetched from other resources. Page content comes from GitHub. Blog content is aggregated. All personal info is pulled from my GitHub profile.

* React
* Webpack
* Javascript
* Express
* Node.JS

### The Underpin Theme Framework – WordPress Framework
Developed an open-sourced WordPress framework that utilizes Composer to make developing in WordPress feel more-modern.

Implements a scale-able modern way to build enterprise-level WordPress websites.
Structures PHP templating syntax to work a little more like React. 

[GitHub Repo](https://github.com/underpin-WP/underpin)

* Webpack
* Composer
* WordPress
* PHP
* Node.JS
* Composer
* Registry Architecture
* Javascript

## Nicholas - a Nearly Headless WordPress Framework

Developed a WordPress framework that turns a WordPress website into a modern web application..
Implemented using Underpin.

Features a “compatibility mode” that allows any given page to load using a traditional WordPress request. This ensures compatibility with WordPress without sacrificing the “app like” experience provided by a fully headless approach.

[Demo Site](nearly-headless.dev/)

[Github Repository](github.com/nicholas-wordpress/)

[A case for the nearly headless WordPress app](https://www.wpdev.academy/concepts/headless-wordpress-is-overrated-a-case-for-the-nearly-headless-web-app/)

* WordPress
* Webpack
* Composer
* WordPress
* PHP
* SCSS
* Node.JS
* Advanced Javascript
* React
* AlpineJS

## WP Dev Academy

Created a Website that teaches people some of my approaches to WordPress theme and plugin development. I publish developer-focused blog content on this blog weekly, and am always working on courses and resources for my subscribers.