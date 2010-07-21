=== Accessible Tag Cloud ===
Contributors: automaton
Donate link: http://www.automaton.be/
Tags: tags, widgets
Requires at least: 2.5
Tested up to: 3.0
Stable tag: 1.1

Accessible replacement for the default tag cloud

== Description ==

This plugin creates a tag cloud that has, per tag, a complete description of that tag's size, in the form "The tag 'yourtag' contains X posts". This is for the benefit of screenreaders, who will read this information aloud.
This additional text can be hidden from regular users by styling the 'screenreader' class in your theme's CSS file. I use this CSS code:

.screenreader {
	height:0;
	left:-9000px;
	position:absolute;
	width:0;
}

Do not use 'display:none' as that will hide it from screenreaders.

I'd like to add some localization options, but I have insufficient PHP knowledge to implement that. If you'd like to help out, please let me know at http://www.automaton.be/contact/

== Installation ==

This plugin requires a sidebar-enabled theme, as it uses a sidebar widget.

1. Upload `accessible-tagcloud.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to 'design' -> 'widgets' and add the widget to a sidebar.

== Frequently Asked Questions ==

= Why is the regular tag cloud not accessible to visually impaired users? =

Because it uses only (CSS) font size to display the amount of posts linked to a tag. Screenreaders do not read out that information, and all impaired users therefore see is a list of words, with no idea of the size of each tag.


== Screenshots ==

== Changelog ==

= 1.1 =
* English-language version
