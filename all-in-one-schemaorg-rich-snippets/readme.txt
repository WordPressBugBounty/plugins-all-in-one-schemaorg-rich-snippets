=== Schema - All In One Schema Rich Snippets ===
Contributors: brainstormforce
Donate link: https://www.paypal.me/BrainstormForce
Tags: schema markup, rich snippets, wordpress seo, structured data, google search
Requires at least: 3.7
Tested up to: 6.8
Stable tag: 1.7.4
Requires PHP: 7.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Improve SEO, elevate rankings and Boost CTR. Supports different types of content and works well with Google, Bing, Yahoo, and Facebook.

== Description ==
Get eye-catching results in search engines with the most popular schema markup plugin. Easy implementation of schema types like Review, Events, Recipes, Article, Products, Services etc

[Try Live Demo of All In One Schema Rich Snippets](https://zipwp.org/plugins/all-in-one-schemaorg-rich-snippets/)

= What is a Rich Snippet? =
It is basically a short summary of your page in the search results of Google, Yahoo, Bing and sometimes in the News feed of Facebook in nice format with star ratings, author photo, image, etc.

[See Examples of Rich Snippets Here.](https://wpschema.com/free-rich-snippets-schema-plugin-for-wordpress/?utm_source=wp-org-readme&utm_medium=rich-snippet-example "Rich Snippets Examples")

= How does a Rich Snippet help you? =
* It provides only the essential and accurate information for search engines to display in search result snippets.
* Rich snippets are highly interactive, featuring photos, star ratings, prices, authors, and more, helping you stand out from the competition.
* Helps you rank higher in search results
* Helps Facebook display proper information when users share your links on Facebook
* **[Check the difference it makes](https://wpschema.com/free-rich-snippets-schema-plugin-for-wordpress/ "See the difference")** in Click Through Rate (CTR)

= Supported Content Types: =
This plugin supports the following types of Schemas:

* Review
* Event
* People
* Product
* Recipe
* Software Application
* Video
* Articles

= Future release would include: =
* Breadcrumbs
* Local Business
* Books

= Want to contribute to the plugin? =
You may now contribute to the plugin on Github: [All in one Schema.org Rich Snippets on Github](https://github.com/brainstormforce/All-In-One-Schema.org-Rich-Snippets "Contribute on Github")

== Installation ==
= Through Dashboard =
1. Go to Plugins 
1. Add New 
1. Search for "All in One Schema.org Rich Snippets" Or Upload the plugins zip file

= Through FTP =
1. Upload the plugin into `wp-content/plugins` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. That's It.

Now go ahead and create a new post. Select the post type from the dropdown in the meta box, fill in the details, and publish it.

Google will start showing rich snippets in the search results, as soon as your post is crawled.

You can test the rich snippet on Google Webmasters Rich Snippets Testing Tool

== Frequently Asked Questions ==
= What is a Rich Snippet? =
The All in One Schema Rich Snippets plugin helps you add structured data markup to your WordPress website, enabling search engines to display rich snippets like star ratings, reviews, recipes, events, and more in search results.
= How does this plugin improve SEO? =
By adding schema markup, the plugin enhances search engine understanding of your content, increasing the chances of rich snippets appearing in search results, which can improve click-through rates (CTR) and SEO performance.
= Which Content Types are Supported? =
This plugin currently supports almost all of the content types that are released by Schema.org at one place.
= Do I need coding knowledge to use this plugin?= 
No, the plugin provides an easy-to-use interface where you can add schema markup without any coding.

== Screenshots ==
1. Meta box in post-new under the editor screen.
2. Select content type from dropdown
3. Fill the details as much as you can
4. Test the post or page URL in Google Rich Snippets Testing

== Changelog ==

### 1.7.4 ###
- Fixed: WooCommerce product editor compatibility - Added exclusions for WooCommerce post types.

= 1.7.3 =
- Improvement: Refactored and optimized the codebase to improve code quality.

= 1.7.2 =
- Fixed: Resolved the issue for function _load_textdomain_just_in_time was called incorrectly in WP 6.8.

= 1.7.1 =
- Improved security and updated the slug for better compatibility.
- This update includes important security fixes, improved accessibility compliance, and ensures a consistent text domain throughout the plugin.

= 1.7.0 =
- New: Added NPS Survey to gather your valuable feedback for All In One Schema Rich Snippets.
- Improvement: Enhanced the codebase to strengthen security measures.

= 1.6.13 =
* Improvement: Compatibility with WordPress 6.7.
* Improvement: Updated the video uploadDate field to use the d-m-y format.

= 1.6.12 =
* Improvement: Added Product Image field in Review Schema.
* Improvement: Updated plugin metadata tags to improve search optimization.

= 1.6.11 =
* Fixed: Improved code quality syntax and security checks for better coding standards and practices.
* Fixed: Recipe - Author type fix.
* Fixed: Video Upload Date issue.

= 1.6.10 =
* Fixed: Corrected the uploadDate format as per ISO 8601 standards with timezone.
* Fixed: Resolved url redirect issue for Test Rich Snippets button.

= 1.6.9 =
* Improvement: Improved plugin codebase for better security.

= 1.6.8 =
* Fixed: Ratings not visible on single product pages with Divi theme.

= 1.6.7 =
* Fixed: Customizer not loading when All In One Schema Rich Snippets plugin is active.

= 1.6.6 =
* Props to Patchstack for reporting security issues. Those are fixed in this release. Plus we've hardened security in other areas of the plugin.

= 1.6.5 =
* Fixed: Code updated according to coding standard.

= 1.6.4 =
* Improvement - Hardened the security of the plugin.
* Fixed: Reset functionality was not working in the backend settings.
* Fixed: Console warning jquery-fn-load-is-deprecated.

= 1.6.3 =
* Improvement: Compatibility with WordPress 5.5.
* Improvement: Updated the Hashchange jquery.
* Fixed: Tabs UI breaks in the backend.

= 1.6.2 =
* New: Users can now share non-personal usage data to help us test and develop better products. (https://store.brainstormforce.com/usage-tracking/?utm_source=wp_dashboard&utm_medium=general_settings&utm_campaign=usage_tracking)

= 1.6.1 =
* Improvement: Compatibility with the latest WordPress PHP_CodeSniffer rules.
* Improvement: Updated the Schema URL to the https instead of HTTP.
* Fixed: Tabs conflict with the Astra theme.
* Fixed: Image field is required error showing in the Recipe schema.
* Fixed: Remove the support for Rating in the service schema as per the new Google update.

= 1.6.0 =
* New: Added ItemReviewed types in Review schema.
* Fixed: error "Thing is not a known valid target type for the item reviewed the property" in the review schema.

= 1.5.6 =
* Improvement: Updated plugin name - `All In One Schema Rich Snippets` to `Schema - All In One Schema Rich Snippets`.
*  Improvement: Updated product availability strings according to the Google requirement.
*  Improvement: Added alt tag to the publisher image for SEMrush plugin compatibility.

= 1.5.5 =
*  Fixed: Schema markup displayed before the post content or hidden when page content is built using a page builder plugin.

= 1.5.4 =
*  Improvement: Dashboard UI Updated.
*  Fixed: Removed publisher logo width-height meta tags.
* Fixed: Removed default border CSS for images in frontend.

= 1.5.3 =
* Improvement: Updated schema exiting action and enqueue files function.

= 1.5.2 =
* Fixed: Frontend Summary box structure validation issue.
* Fixed: Editor object undefined issue lead js issue in the page.

= 1.5.1 =
* Fixed: Plugin outputting extra output causing Ajax calls to break after last update.

= 1.5.0 =
* Improvement: Improved overall the security of the plugin by using sanitization and escaping the attributes wherever possible, checking nounce and user capabilities before any actions are performed.
* Fixed: XSS Vulnerability in the settings page, Thanks for the report Neven Biruski (DefenseCode).
* Fixed: Missing closing div tag in the generated schema markup breaking style for some themes.
* Fixed: Load the external scripts without protocol to prevent it from breaking on https sites.

= 1.4.4 =
* Fixed: PHP fatal error to older version of PHP

= 1.4.3 =
* Fixed: WooCommerce Support Added

= 1.4.2 =
* Improvement: Added company/organization and address in people schema.
* Improvement: Added nutrition & ingredients in recipe schema.
* Improvement: Added software image & operating system in software application schema.
* Improvement: Added video description in software application schema.
* Improvement: Added author, publisher organization and publisher logo in article schema.
* Improvement: Added provider location, provider location image, and telephone in service schema.
* Improvement: Changes admin bar test rich snippet redirect link to the structured data testing tool.
* Fixed: removed all error in schema according to structured data testing tool.

= 1.4.1 =
* Fixed: Compatibility Fix WordPress 4.7.

= 1.4.0 =
* Added new service schema
* Minor CSS fixes

= 1.3.0 =
* Improvement: Updated markup data to meet Google Structured data guidelines
* Fixed: WordPress 4.4 compatibility
* Fixed: Admin UI on small screens

= 1.2.0 =
* Improvement: WordPress 4.0 compatibility
* Fixed: Colorpicker breaking other plugins colorpicker settings.

= 1.1.9 =
* Fixed: Image uploading in meta issue resolved.
* Fixed: Compatibility with WordPress 3.9

= 1.1.8 =
* Fixed: CSS and JS now loads on the page / post where rich snippets are configured.

= 1.1.7 =
* Improvement: Added "Test Rich Snippets" menu in admin bar for testing rich snippets in Google Webmasters Tools
* Fixed: retina.js issue resolved
* Removed unnecessary code

= 1.1.6 =
* Improvement: Compatibility with WordPres 3.8
* Fixed: Admin CSS breaking tabs in WP 3.8
* Added: reference post url field in "contact developers" form on settings page

= 1.1.5 =
* Improvement: Replaced rating 'count' with 'votes' on products - as directed by Google
* Fixed: Article snippet not displaying accurate when snippet title is blank
* Fixed: Recipe string 'Published on' can be changed.

= 1.1.4 =
* Fixed:  Illegal string offset `user_rating` Warning

= 1.1.3 =
* Improvement : Network Activation

= 1.1.2 =
* Fixed: Edit media functionality.

= 1.1.1 =
* Added: Article type
* Added: Compatibility with WooThemes Plugins and themes
* Added: New Media Manager for uploading images in metabox

= 1.1.0 =
* Added: Admin options
* Fixed: Ratings on recipe, products and software application
* Improvement: Admin options for customizing everything
* Improvement: New snippet box design with responsive layout

= 1.0.4 =
* Fixed: Rating on Comments
* Fixed: On deleting any deactivated plugin
* Fixed: Error message comming on commenting
* Fixed: On post save draft

= 1.0.3 =
* Clean up the code
* Fixed: Plugin activation error
* Fixed: Error on editing theme and plugin files.
* Removed : Breadcrumbs

= 1.0.2 =
* Added: RDFa Breadcrumbs Plugin is now a part of All in One Schema.org Rich Snippets !
* Added: Star rating and review for recipe
* Fixed: Recipe type
* Fixed: Post update error

= 1.0.1 =
* Fixed: Minor Bugs

= 1.0 =
* Initial Release.