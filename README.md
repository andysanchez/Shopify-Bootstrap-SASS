Bootstrap 3.1.1 for Shopify SASS
======================

A single Bootstrap SCSS file for use with Shopify

To use, upload to your Shopify Asset directory, and include the following: 

`  {{ 'bootstrap.scss.css' | asset_url | stylesheet_tag }}  `
  
Shopify will compile it for you, should be around 90 KB. 

This came from a post on Shopify's forum announcing the feature, 

What is this?
======================
This came from a post on Shopify's forum announcing the feature, I played around with it all weekend and was shocked at how much time using SASS saved when using Shopify. Unfortunately, it's not as full-featured as full-blown SASS, but it is a huge improvement. 

Here's the post you should definitely read:

https://ecommerce.shopify.com/c/ecommerce-design/t/you-can-now-use-scss-in-shopify-s-template-editor-133389


What I'd Use It For
======================

I'd use it if you're building a theme, SASS makes it a LOT easier to get input from the theme settings into action.
