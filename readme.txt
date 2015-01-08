=== WpF Easy News Ticker ===
Tags: News ticker, News Headlines, Headlines, jQuery type effect, Type effect, jQuery news ticker,horizontal news ticker, smooth news ticker,news scroller.
Requires at least: 3.0.1
Tested up to: 4.1
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Fully customizable. You can change styles according to your theme color. Add unlimited News Ticker in posts/pages/widgets/templates etc. 

== Description ==

By using this plugin you can add unlimited news ticker in posts, pages, templates, widgets etc. 

Live Demo: http://wpfreeware.com/preview/wpf-easy-news-ticker

<b>Features:</b>

1. Very easy installation
2. Shortcode system
3. unlimited color variation by using shortcode attributes.
4. Responsive
5. custom post supported
6. custom taxonomy supported


<b>Shortcodes</b>

Remember: Must put a unique id in each shortcode, If you want to use 3 news ticker in one page then you can put in the first ticker id="1", second id="2" & 3rd id="3".
If you are using one news ticker in one page then leave it.

1. General News Ticker

<pre>[wpf_ticker id="1" text="Latest Updates"]</pre> //id=(unique-id-number)

2. Ticker form category

<pre>[wpf_ticker id="2" category="category name" text="Latest News"]</pre> //id=(unique-id-number)

 

3. Ticker form custom taxonomy

<pre>[wpf_ticker id="3" taxonomy="your-taxonomy-name" category="category name" text="Latest News"]</pre> //id=(unique-id-number)

4. Ticker Colors

<pre>[wpf_ticker id="4" text="Latest News" color="#1874B4" bg_color="#eeeeee" link_color="#222222"]</pre>	//id=(unique-id-number)
Note: you can HEX & color name in the color,bg_color,link_color attributes. Ex: #1874B4 or blue.

 
More shortcode attributes are:

<b>post_type="post type"</b>
Note: Your post type will be here, default is genaral post.

<b>category="category name"</b>
Note: Your category name will be here.

<b>taxonomy="taxonomy name"	</b>
Note: Your custom taxonomy name will be here, default is genaral post type category name.

<b>id="numeric unique id"</b>
Note: Put a numeric unique id for each news ticker for using multiple in one page,
if you use one news ticker in one page then leave it.

<b>text="Lebel text"</b>		
Note: News ticker level text. Default is Latest News

<b>count="posts amount to display"</b>
Note: Put a numeric value to display posts amount, default is unlimited

<b>color="color code"</b>
Note: put your color code. Ex: #cf0000 or Ex: red. Note if you put color codes in any shortcode then the color will 
be apply on all the news ticker you are using.

<b>bg_color=" background color code "</b>
Note: change background Color,default is #eeeeee;

<b>link_color=" Link color code"</b>
Note : change link color,default is #222222;


== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload `plugin-directory` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use shortcode in page, post or in widgets.
4. If you want news ticker in your theme php, Place `<?php echo do_shortcode('[wpf_ticker id="1" text="News Ticker"]'); ?>` in your templates. More shortcodes attributes are available. See description tab.


== Frequently Asked Questions ==



== Screenshots ==



== Changelog ==

= 1.0 =
* Initial Release