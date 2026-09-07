=== Ocasio Disable Emojis ===
Contributors: ocas
Tags: disable emojis, remove emojis, speed up wordpress, performance, bloat remover
Requires at least: 6.0
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Removes extra emoji scripts, inline styles, and DNS prefetch links to speed up page load times.

== Description ==

By default, WordPress loads extra JavaScript and CSS files on every single page to support custom emoji icons. These extra HTTP requests slow down your site and hurt your Core Web Vitals scores.

Every modern phone, tablet, and computer already has full native emoji support built into its operating system. You don't need WordPress loading extra scripts to show a smiley face.

Ocasio Disable Emojis strips out the extra WordPress emoji detection script, inline styles, and external DNS prefetch calls. Native browser emojis continue to display perfectly, while your site loads faster.

= Features =

* **Removes Emoji Script Bloat:** Stops `wp-emoji-release.min.js` from loading on your pages.
* **Strips Inline Styles:** Removes extra inline emoji CSS from your page headers.
* **Cleans TinyMCE Editor:** Disables emoji converters inside the classic visual editor.
* **Stops DNS Prefetch:** Removes unnecessary prefetch requests to `s.w.org`.
* **Zero Front-End Assets:** Pure PHP execution with 0 bytes of extra CSS or JavaScript.
* **Instant Dashboard Switch:** Turn the feature on or off in one click directly from the Ocasio Plugins dashboard.

== Installation ==

1. Upload the `ocasio-disable-emojis` folder to your `/wp-content/plugins/` directory, or install it directly through the WordPress plugins screen.
2. Activate the plugin through the 'Plugins' screen in WordPress.
3. Go to **Ocasio Plugins -> Dashboard** in your sidebar to toggle your settings.

== Frequently Asked Questions ==

= Will emojis still work on my site? =
Yes. All standard emojis typed on keyboards, iPhones, Androids, Macs, and PCs continue to work normally through the device's native font system.

= Will this speed up my website? =
Yes. It removes blocking HTTP requests and inline CSS from every page header across your site.

== Changelog ==

= 1.0.0 =
* Initial public release.
