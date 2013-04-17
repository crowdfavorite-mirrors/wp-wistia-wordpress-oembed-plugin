=== Wistia WordPress Plugin ===
Contributors: wistia
Tags: wistia, oembed, video, embed
Requires at least: 2.9.1
Tested up to: 3.3.2
Stable tag: 0.5

Enables all Wistia embed types to be used in your WordPress blog.

== Description ==

Wistia's embed codes are designed to be very durable, but WordPress has a
history of being particularly troublesome. This plugin transparently makes
sure that your Wistia embeds will work, no matter what you do.

With this plugin, you can put oEmbed links in your posts which will be replaced with the actual Wistia video when your page renders. The easiest way to specify the link is like this:

    [embed]http://app.wistia.com/embed/medias/3a3b7090ca?width=960&height=360&autoplay=false&playbutton=true&controls_visible=false&end_video_behavior=default[/embed]

You can also put just the link (without any [embed] tags) on its own line (no extra spaces) and blank lines above and below.

== Installation ==

1. Make a 'wistia-wordpress-oembed-plugin' directory in '/wp-content/plugins/'.
2. Upload 'wistia-wordpress-oembed-plugin.php' to the
'/wp-content/plugins/wistia-wordpress-oembed-plugin/' directory.
3. Upload 'wistia-anti-mangler.php' to the
'/wp-content/plugins/wistia-wordpress-oembed-plugin/' directory.
4. Activate the plugin through the 'Plugins' menu in WordPress.

== Changelog ==

= 0.5 =
* Updated the oembed endpoint for Wistia
* Updated the regexes for matching Wistia video URLs to the latest recommended in the doc

= 0.4 =
* Added support for the new Playlist embed structure

= 0.3 =
* Added support for all SuperEmbed style Wistia embeds

= 0.2 =
* Added support for SuperEmbed style oEmbeds

= 0.1 =
* Initial release
