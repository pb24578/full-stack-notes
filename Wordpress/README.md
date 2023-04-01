# Wordpress
Wordpress is a free and open source content management system (CMS) to build websites using themes and plugins from the marketplace.
- Wordpress Themes: https://wordpress.org/themes/
- Wordpress Plugins: https://wordpress.org/plugins/

### Why Wordpress?
The power of wordpress comes with the speed of how fast you can develop a website. Because you can re-use Wordpress themes and edit them to your liking, you can easily publish a website in a few hours. This is perfect for developing a minimal viable product (MVP) for small businesses.

#### Pros of Wordpress
1. No coding required! Load up a template add some plugins and you can develop a portfolio, blog, e-commerce, learning management system (LMS), and anything you can think of.
2. Many cheap hosting websites (e.g. Bluehost) support Wordpress in their control panel.
3. Search engine optimization (SEO) friendly by default.
4. Powers 42% of the internet, so there's tons of support for Wordpress.

The fast, cheap, and SEO-friendly environment of Wordpress makes it a great solution for small businesses, startups, and individuals to start their online presence on the Internet.

#### Cons of Wordpress
1. Limited by themes and plugins that are available. If you need a very custom solution, then Wordpress may not be the best. Although it is still possible to make it fully customizable, a Wordpress website is not best suited for that complexity.
2. Wordpress is vulnearable to hackers due to its popularity, so it's a big target for attackers.

### Installation
Wordpress uses Apache, PHP, and MySQL stack. For Mac, the best way to install this stack is with [MAMP](https://www.mamp.info/en/mamp/mac/), which is a local server environment for Mac Apache MySQL PHP (MAMP).

Once you start the MAMP server on the desktop app, visit the local MAMP landing page at http://localhost:8888/MAMP/.

To see your MySQL databases, go to the phpMyAdmin CP at http://localhost:8888/phpmyadmin.

Create a new database named "wordpress" on phpMyAdmin. Next, let's install Wordpress on your MAMP server, so download Wordpress from https://wordpress.org/download/. Then, place the wordpress folder inside of your MAMP/htdocs folder. Now visit http://localhost:8888/wordpress to setup Wordpress on your local machine!

Finally, visit http://localhost:8888/wordpress/wp-admin to view your Wordpress admin dashboard.

### Themes
A theme is a collection of files that make up the foundation of the site's appearance, including page layouts, style sheets, and sidebar positioning.

Visit http://localhost:8888/wordpress/wp-admin/themes.php to set the theme of your Wordpress website.

### Plugins
A plugin can add new functionality or extend existing functionality on your site, allowing you to create virtually any kind of website, from ecommerce stores to portfolios to directory sites.

Visit http://localhost:8888/wordpress/wp-admin/plugins.php to install plugins to your Wordpress website.

Popular Wordpress plugins to install:
1. All-in-One WP Migration: A simple plugin to backup up your website and database
2. Elementor: Design builder for your website using a drag-and-drop visual editor
3. WooCommerce: Open source e-commerce builder to make an online store with a checkout system
4. Yoast: SEO tools for your website to hit #1 in Google search