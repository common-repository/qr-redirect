=== QR Code Redirect ===
Contributors: kionae
Donate Link: http://nlb-creations.com/donate/
Tags: qr code, redirection
Requires at least: 3.2.0
Tested up to: 3.4.2
Stable tag: trunk

QR Code Redirect lets you set up your own QR Code redirection site.  Generate a QR code for a URL on your site, and redirect that URL anywhere.

== Description ==

QR Code Redirect lets you set up your own QR Code redirection site.  The plugin creates a new custom post type called QR Redirect, which generates a QR code that points to the post's permalink.  You may then specify any URL you like for the post to redirect to.  Great if you have an offsite contest, form, newsletter sign-up, etc. You can even change the URL you're redirecting to without having to worry about updating the QR code in your advertising media.

More information at http://nlb-creations.com/2011/09/27/wordpress-plugin-qr-redirect/

== Installation ==

1. Upload plugin .zip file to the `/wp-content/plugins/` directory and unzip.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Add new redirects under the "QR Redirets" menu option.   

== Frequently Asked Questions ==

= How can I add my QR code to a post? =
Use the following shortcode:

`[qr-code id="xx" size="xx"]`

where id is the post ID of your QR Redirect, and size is the desired width of the image in pixels.  Size is optional, and will default to 250 pixels.

= If I need to change the URL I want to redirect to, do I have to update the QR Code image in all of my ads? =

No.  The QR Code points to a Wordpress permalink on your site.  The only time you would ever have to switch out an image is if you change your site's permalink settings, and thus change the permalinks of the QR Redirect posts.  Presumably this is something you won't be doing too often, if ever.

= Why do I need this? =

QR Codes on their own are static.  In order to update them, you have to generate a whole new image (which would suck if you were putting them on flyers or some other printed medium and suddenly needed to change them).  This plugin lets you point your QR code's embeded URL to a different web address if you need to.  For example, if you are using an off-site service to host a contest, you can point a QR code at that site for the duration of the contest and later change it to point to another page with the contest winners. 

= How are your QR Codes generated? =

Courtesy of Google Chart Tools, specifically their Infographics.
http://code.google.com/apis/chart/infographics/docs/overview.html

== Screenshots ==

1. QR Redirect admin screen

== Changelog ==

= 0.2.4 =
* Added ability to specify error correction level of the generated QR code.

= 0.2.3 =
* Fixed a bug that was causing 404 errors for some users

= 0.2.2 =
* Added notes field for admin use
* QR Code edit screen now auto-generates shortcode for copy/pasting.

= 0.2.1 =
* Added shortcode for displaying QR Redirect images in posts

= 0.2 =
* Fixed a major backwards compatibility bug
* Added some basic stat tracking

= 0.1 =
* Initial release

== Upgrade Notice ==

= 0.2.4 =
* Added ability to specify error correction level of the generated QR code.

= 0.2.3 =
* Fixed a bug that was causing 404 errors for some users

= 0.2.2 =
* Added notes field for admin use
* QR Code edit screen now auto-generates shortcode for copy/pasting.

= 0.2.1 =
* Added shortcode for displaying QR Redirect images in posts

= 0.2 =
* Fixed a major backward compatibility bug

= 0.1 =
* Initial release