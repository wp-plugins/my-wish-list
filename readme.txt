=== My Wish List ===
Contributors: kionae
Donate link: http://www.nlb-creations.com/donate
Tags: item lists, wish list, wishlist
Requires at least: 3.2.0
Tested up to: 3.4.1
Stable tag: trunk

This plugin allows you to create wish lists for your website, and display them on any post or page with simple shortcode.

== Description ==

This plugin allows you to create wish lists for your website, and display them on any post or page with simple shortcode.  Include Item names, prices, sizes, 
colors, links, and photos so everyone knows what you want/need.

== Installation ==

1. Upload plugin .zip file to the `/wp-content/plugins/` directory and unzip.
2. Activate the plugin through the 'Plugins' menu in WordPress
3. A new post type called "Wish Lists" will appear in the admin menu.  Use this to create your wish lists.
4. Use the shortcode [wishlist id=xx] in your posts and pages to display your wishlists.  

== Frequently Asked Questions ==

= How do I display my wishlist? =

Use the shortcode [wishlist id=xx] in any page or post, where id is the post id of the wishlist you created.  Wishlists do not have their own template file, 
so the only way to make them appear is using the shortcode.

= Can visitors reserve items to purchase from my wishlist? =

Yes.  This can enabled in the Wishlist settings box in any wishlist you create.  Information about promised items will appear in the edit page for the wishlist.

= Can visitors purchase items through this plugin? =

No.  This is not an e-commerce plugin.  It only allows you to list items you need/want, and tell people where they can buy them for you. 

= Can I change the CSS styles for the wishlist? =

Yes.  Just copy the my-wish-list/styles/wishlist.css file into your active theme's directory and make all the changes you like.

== Changelog ==

= 0.0.1 =
* Initial release

= 0.0.2 =
* Bug fix for wishlists save with no items added

= 1.0 =
* Moved all CSS to external file
* Added code to allow override of default CSS
* Added ability for donors to reserve items
* Added additional settings to each wishlist created to make them more customizable

== Upgrade Notice ==

= 0.1 =
* Initial release

= 0.0.2 =
* Bug fix for wishlists save with no items added

= 1.0 =
* Moved all CSS to external file
* Added code to allow override of default CSS
* Added ability for donors to reserve items
* Added additional settings to each wishlist created to make them more customizable