Bootstrap 3.1.1 for Shopify SASS
======================

A single Bootstrap SCSS file for use with Shopify

To use, upload to your Shopify Asset directory, and include the following: 

  {{ 'bootstrap.scss.css' | asset_url | stylesheet_tag }}
  
Shopify will compile it for you. 

What I'd Use It For
======================

I'd use it if you're building a theme, SASS makes it a LOT easier to get input from the theme settings into action.
