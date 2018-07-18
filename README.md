#Memberlite: An Easy to Customize Theme for Membership Sites
===
##Description
---------------

**Build a Professional WordPress Membership Site**
Memberlite is the ideal theme for your membership site - packed with integration for top membership site plugins including Paid Memberships Pro. It's fully customizable with your logo, colors, fonts, and more global layout settings. Extend the site appearance further with the Memberlite Elements and Memberlite Shortcodes plugins. Memberlite is responsive, clean and minimal.

##Copyright
---------------

Memberlite WordPress Theme, Copyright (C) 2017 Stranger Studios, LLC and other contributors
Memberlite is distributed under the terms of the GNU GPL

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

Memberlite WordPress Theme bundles or has used original or modified code from the following third-party resources:

Font Awesome icons Copyright Dave Gandy
License: CC BY 4.0 License
Source: https://fontawesome.com/license

Font Awesome CSS Copyright Dave Gandy
License: MIT License
Source: https://fontawesome.com/license

Paid Memberships Pro icon and templates
License: GPLv2
Source: https://www.paidmembershipspro.com/paid-memberships-pro-is-100-gpl-and-why/

bbPress icon, CSS and templates
License: GPLv2
Source: https://bbpress.org/about/gpl/

BuddyPress CSS and templates
License: GPLv2
Source: https://buddypress.org/about/gpl/

WooCommerce icon, CSS and templates
License: GPLv3
Source: https://github.com/woocommerce/woocommerce/blob/master/license.txt

The Events Manager icon
License: GPLv3
Source: https://eventsmanagerpro.com/terms-conditions/

MarketPress template
License: GPLv2
Source: https://wordpress.org/plugins/wordpress-ecommerce/

CSS grid based on Foundation by Zurb
License: MIT License
Source: https://foundation.zurb.com/get-involved/faq.html

##Getting Started
---------------

Memberlite makes it easy to customize the appearance and layout of your site using the Theme Customization Screen (Appearance > Customize). 

###Adding Your Logo
Use the Customize > Site Identity screen to add a custom logo (formatted for retina display), update your Site Title and Tagline, and toggle the display of your Site Title & Tagline.

[Explore Documentation on Custom Headers in Memberlite](http://www.memberlitetheme.com/documentation/site-branding/)

###Customize the Theme
Use the Customize > Memberlite Options screen to modify theme layout, logo, fonts, colors, copyright message and more.

[Explore Documentation on Customizing Memberlite »](http://memberlitetheme.com/documentation/customize/)

###Using Child Themes
If you need to customize the theme beyond theme settings, use a child theme.

[Download a Blank Child Theme »](https://github.com/strangerstudios/memberlite-child) | [About Child Themes (WordPress Codex) »](http://codex.wordpress.org/Child_Themes)

###Integrated Plugins
Memberlite includes formatting for use with:

**Paid Memberships Pro**
[Install Paid Memberships Pro »](http://www.paidmembershipspro.com/documentation/download/)

**WooCommerce**
[Install WooCommerce »](https://wordpress.org/plugins/woocommerce/) | [Install Paid Memberships Pro - WooCommerce Add On »](https://wordpress.org/plugins/pmpro-woocommerce/)

**bbPress**
[Install bbPress »](https://wordpress.org/plugins/bbpress/) | [Install Paid Memberships Pro - bbPress Add On »](https://wordpress.org/plugins/pmpro-bbpress/)

**Events Manager**
[Install Events Manager »](https://wordpress.org/plugins/events-manager/)

**Testimonials Widget**
[Install Testimonials Widget »](https://wordpress.org/plugins/testimonials-widget/)

We highly recommend using these plugins for every site running Memberlite:

**Multiple Post Thumbnails**
[Install Multiple Post Thumbnails »](https://wordpress.org/plugins/multiple-post-thumbnails/)

**Theme My Login**
[Install Theme My Login »](https://wordpress.org/plugins/theme-my-login/)


###Changelog

**3.1 - 2017-XX-XX**
* ENHANCEMENT: Improving print styles for better output
* BUG FIX/ENHANCEMENT: Prefixing all hooks with theme slug. Adding deprecated file for old hook names.
* BUG FIX: Hiding 'Register' link in meta menu if registration is disabled.
* BUG FIX: Wrapping strings in customizer to fix redirect issue.
* SECURITY/BUG FIX: Added esc_url to wp-admin links on theme welcome page.
* ENHANCEMENT: Updating to version 4.7 of Font Awesome.
* ENHANCEMENT: Removing theme updates from Memberlite license server.
* ENHANCEMENT: Removing theme elements that are plugin territory to the memberlite-elements plugin.
* ENHANCEMENT: Removing welcome page redirect on theme activation.
* ENHANCEMENT: Remove widget_text shortcode and moving to memberlite-elements plugin.
* ENHANCEMENT: Adding WooCommerce page template 3.x support
* ENHANCEMENT: Adding feature to define a member-menu area for logged out visitors

**3.0.4 - 2017-10-27**
* SECURITY/BUG FIX/ENHANCEMENT: Added sanitization and escaping to the banner metabox on the edit post page, fixed the cropping settings for the uploaded images, and refactored the code to make it more readable. (Thanks, Massimo Marazzi)
* ENHANCEMENT: Improved checkout template to work with the div-based layout now used in PMPro 1.9.4+.

**3.0.3 - 2017-08-07**
* BUG: Fixed float for Full Width and Narrow Width page templates when default pages layout set to left sidebar.
* NOTE/ENHACEMENT: Now only showing the post meta generated by memberlite_get_entry_meta() on the post CPT.
* NOTE/ENHANCEMENT: Now only showing the footer widgets primary background stripe if there are active widgets in the area.
* ENHANCEMENT: Added CSS for JetPack contact form submission/results blockquote.

**3.0.2 - 2017-01-02**
* BUG: Fixed issue with update code when PMPro is not installed.
* BUG/ENHANCEMENT: Now running "do_shortcode" on the "Banner Right" content.
* BUG/ENHANCEMENT: CSS tweak for input elements in iOS browsers.
* ENHANCEMENT: Added Narrow Width page template for an 8 column centered main content layout with no sidebar.

**3.0.1 - 2016-12-06**
* BUG: Now hiding the wrapping <p> tag for memberlite_get_entry_meta before and after when set to none via customizer.
* ENHANCEMENT: Added masthead with profile user name to bbPress single user profile view.
* BUG: Now filtering memberlite_banner_right to allow shortcodes.
* BUG: Fixing some display issues with no masthead and the blog sidebar float.
* NOTE/ENHANCEMENT: Added the code back to update from the PMPro license server until we get approval in the WordPress repository.

**3.0 - 2016-09-20**
* ENHANCEMENT: Page banner description and banner right column now inheriting ratio of primary columns.
* ENHANCEMENT: Adding support for toggling display of page masthead banner.
* BUG: Fixing index error on memberlite_cpt_sidebar_id.
* ENHANCEMENT: Added page setting for page icon and banner right icon display.
* BUG: Fixing error when viewing archive and no $post is set.
* BUG: Fixing error when missing pagemenuid in sidebar.
* Cleaning blank spaces in style.css
* BUG: Fixing CSS on checkout page headings (h2) for boxes added via Register Helper.
* BUG: Fixing some dark.css colors for Paid Memberships Pro and bbPress.
* ENHANCEMENT: Added customization setting for columns ratio of primary and sidebar.
* BUG: Removed add_image_size('large') declaration
* ENHANCEMENT: Added image size for 'fullwidth' (full width 12 columns - 1170px)
* ENHANCEMENT: Added fallback to author avatar for recent posts widget when featured image is not set
* BUG: Fixing content_width for full width or fluid width page template.
* ENHANCEMENT: Added single post meta settings with template variables for before and after post.
* ENHANCEMENT: Added Back to Top footer link
* ENHANCEMENT: Added customizer settings for page and post navigation
* ENHANCEMENT: Added single page navigation within parent/child page hierarchy
* ENHANCEMENT: Updating theme for compatibility with pmpro-advanced-levels-shortcode addon
* ENHANCEMENT: JS for smooth scroll to # target links in page
* BUG: Fixing nav menus when using pmpro-nav-menus addon
* BUG: Fixing errors and alerts from Theme Check plugin.
* ENHANCEMENT: Moving all shortcodes to 'memberlite-shortocdes' plugin for better compatibility for theme changes.
* ENHANCEMENT: Improved handling of CPT titles, breadcrumbs, and sidebars for single and archive view.

**2.0.3.7**
* ENHANCEMENT: Added JS code to swap to a tab if an anchor is in the URL.

**2.0.3.6**
* ENHANCEMENT: Added responsive appearance to compare_table Membership Levels layout.
* Added hooks for before and after content hooks to single page and single post.
* BUG: Fixed notices in memberlite_levels shortcode.

**2.0.3.5**
* FEATURE: Added memberlite_banner shortcode
* BUG: Fixed comment/ping/trackback count for 'approve' status only.
* BUG: Updated Comment Walker to respect PHP strict standards
* BUG: Fixed homepage bottom banner when page template is defined.
* BUG: Fixed highlighted level in the compare_table layout when highlighted level is first column.
* BUG: Fixed current_user level class on compare_table layout in membership levels shortcode.
* BUG: Fixed notice when bbpress is not activated for memberlite_page_title function

**2.0.3.4 - 2015-11-07**
* SECURITY: Now using get_search_query() and the_search_query() to prevent XSS issues in h1s and breadcrumbs on search results pages. (Thanks, retr0)
* ENHANCEMENT: Tweaks to checkout page CSS.

**2.0.3.3**
* BUG: Updated memberlite_defaults for banner hover background color.

**2.0.3.2 - 2015-10-08**
* BUG: Updated sidebar registration order so default widgets of new WP install are placed in the Posts custom sidebar.
* BUG: Fixed dropdown submenu menus at the third level/depth.
* BUG: Fixed case where the member menu wouldn’t appear for a logged in member.
* BUG: Fixed bug where the mobile menu icon would sometimes not show on mobile or ipad layouts.
* BUG: Fixed bug where the wrong banner image would sometimes show on blog and archive pages.
* BUG: Better handling of custom sidebars with quotes and other special characters in them.
* ENHANCEMENT: Now falling back to primary menu (if set) if mobile menu widgets are not defined.
* ENHANCEMENT: Now using the main navigation bar color for dropdown menus.
* ENHANCEMENT: Added support for assigning custom sidebars to detected CPTs.
* ENHANCEMENT: Added "lock" icon to membership-restricted post titles (requires PMPro v1.8.5.4 or higher)
* ENHANCEMENT: Added the ability to select a separate banner and feature image when the Multiple Post Thumbnails Plugin () is enabled.
* ENHANCEMENT: Setting the hover colors of primary, secondary, and action links to a lighter version of the color instead of using other colors from the color scheme.
* ENHANCEMENT: Moved memberlite_defaults array to a separate included file.
* ENHANCEMENT: Design improvements for galleries and image captions.

**2.0.3.1 - 2015-08-26**
* ENHANCEMENT: Support added for dark background via customizer setting and additional dark.css
* BUG: Fixing issue with [memberlite_subpagelist] shortcode thumbnail size setting
* BUG: Header text color fix in customizer

**2.0.3 - 2015-08-26**
* SECURITY: Fixed XSS issue with the h1 display of search queries.
* BUG: Removed pmpro_content_filter from banner description so it is not duplicated in post content.
* BUG: Fixing issue where archvies and index weren't showing full the_content when set in customizer.  
* ENHANCEMENT: Updating Title of Contents and general stylesheet formatting improvements.
* ENHANCEMENT: Added post_parent and thumbnail_size attributes to [memberlite_subpagelist] shortcode.
* ENHANCEMENT: Improved memberlite_getLevelCost function to respect price formatting filters in Paid Memberships Pro.
* ENHANCEMENT: Added masthead banner background image support to front-page template.
* ENHANCEMENT: Added customizer settings for primary navigation bar background color and link color.
* ENHANCEMENT: Added 'scheme_SCHEMENAME' to body classes array when an included color scheme is selected in customizer.'
* ENHANCEMENT: Improved formatting for comments, nested comments, pingbacks and trackbacks

**2.0.2**
* ENHANCEMENT: Now respecting your choice if you set a specific page template on the "static front page".
* BUG: Updates to member menu area to only show the "member menu" selection if current user has membership level.

**2.0.1**
* BUG: Added hook to reset update_themes cache when pmpro license is updated.
* ENHANCEMENT: Added the "pmpro_license_check_key_timeout" filter which can be used to set the timeout of the call to the PMPro License Server to something other than 5s. This is useful if you find your website timing out or having trouble getting updates.

**2.0**
* Initial version.
