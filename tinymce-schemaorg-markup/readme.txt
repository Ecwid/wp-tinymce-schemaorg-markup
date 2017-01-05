=== Protect schema.org markup in HTML editor ===
Contributors: Ecwid
Tags: schema.org, microdata, rich snippets, tinymce, html editor
Requires at least: 4.0
Tested up to: 4.7
Stable tag: 0.3

Easy tool to stop HTML editor from removing schema.org/microdata tags from post or page content.

== Description ==

Wordpress HTML editor (tinyMCE) treats schema.org attributes like itemscope/itemtype/itemprop as invalid HTML attributes and strips them when you save the post or page content. This plugin alters this behavior and prevent the Wordpress HTML editor from removing the schema.org/microdata markup.

== Installation ==

Just install the plugin as usually and activate it. Once activated, it will keep your markup from being removed by the HTML editor. No setup required.

== Credits ==

@azaozz suggested the solution. See the issue discussion here: https://core.trac.wordpress.org/ticket/27931

== Changelog ==

= 0.3 =
Fixed schema.org attributes being removed from article and p tags.

= 0.2 =
Fixed schema.org attributes being removed from img tags.

= 0.1 =
Initial version
