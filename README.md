Session #FlyViews Source Point website
======================================

This is an example Drupal website that used by Session #FlyViews as a demo material. It provides some content through a REST server.

I want to install the site!
---------------------------

Great! You need [Drush](http://drupal.org/project/drush) and [Drush Make](http://drupal.org/project/drush_make) installed on your computer to be able to build the code base for the website. Other than these the usual environment is required for running a Drupal website.

How does the installation look like?
------------------------------------

The repository contains a makefile that downloads Drupal core and the [installation profile for the website, which is a separated repository](https://github.com/balintk/Session-FlyViews-Source-Site-profile). This profile also contains a makefile, that Drush Make will detect and run, so all the contrib modules will be downloaded what we need. The site configuration is also shipped with the profile bundled to features.

All right, give me the steps!
-----------------------------

1. Clone the repository.
1. Run the <code>build</code> script.
1. Install the site manually from your favorite browser choosing the _#FlyViews Source Point_ installation profile, or run the following command inside the <code>web</code> folder:

        drush site-install sourcepoint-flyviews --site-name=#FlyViews Source Point
1. Enjoy!
