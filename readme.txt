=== Accessible Tag Cloud ===
Contributors: automaton
Donate link: http://www.automaton.be/
Tags: tags, widgets, widget, accessibility
Requires at least: 2.5
Tested up to: 3.2
Stable tag: 1.2

Accessible replacement for the default tag cloud

== Description ==

This plugin creates a tag cloud that has, per tag, an indication of that tag's size, between brackets right after the tag and within the anchor text. This is for the benefit of screenreaders, who will read this information aloud.
This additional text is hidden from screenreaders by an included styling class. I am working on an option to include your own.

I'd like to add some localization options, but I have insufficient PHP knowledge to implement that. If you'd like to help out, please let me know at http://www.automaton.be/contact/

== Installation ==

This plugin requires a sidebar-enabled theme, as it uses a sidebar widget.

1. Upload `accessible-tagcloud.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to 'design' -> 'widgets' and add the widget to a sidebar.

== Frequently Asked Questions ==

= Why is the regular tag cloud not accessible to visually impaired users? =

Because it uses only (CSS) font size to display the amount of posts linked to a tag. Screenreaders do not read out that information, and all impaired users therefore see is a list of words, with no idea of the size of each tag.



== Changelog ==

= 1.2 =
* Changed display code to less verbose version (nr. of posts between brackets instead of full text)
* Included styling class for hiding screenreader content (.acc_tag_cloud_screenreader)

= 1.1 =
* Tags updated, no code changes

= 1.0 =
* English-language version
