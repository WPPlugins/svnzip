=== Plugin Name ===
Contributors: flashpixx
Tags: svn, subversion, download, zip, revision, repository
Requires at least: 2.7
Tested up to: 3.4.1
Stable tag: 0.1
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WCRMFYTNCJRAU
License: GPLv3 or later
License URI: http://www.gnu.org/licenses/gpl-3.0.en.html


With this plugin a zip download link of a subversion repository can be created within blog articles and pages 


== Description ==

<strong>This plugin is not be in developing anymore, all functionality is moved to a new plugin <a href="http://wordpress.org/extend/plugins/repositoryzip/">Repository Zip</a></strong>

The plugin creates zip download links within articles and pages of a subversion repository. On each call the subversion revision number, link text, css name and download
name can be set, so that each link points to different subversion. The plugin need no configuration or something else.


== Installation ==

1.  Upload the folder to the "/wp-content/plugins/" directory
2.  Activate the plugin through the 'Plugins' menu in WordPress


== Frequently Asked Questions ==

= How can I use the plugin ? =
Add to your ppost or page content only <pre>[svnzip url="url-to-your-svn"]</pre>

= Can I change the download name or add additional options ? =
Yes you can do this, the plugin tag allows some option values <pre>[svnzip url="url-to-your-svn" revision="your-revision" downloadname="name-of-the-download-file-without-extension" target="target-parameter-of-the-href-tag" cssclass="css-class-of-the-href-tag" linktext="text-of-the-href-tag"]</pre>

= Does the plugin need any requirements ? =
Yes, the plugin need the PHP subversion ( http://de3.php.net/manual/en/book.svn.php ) and PHP ZIP ( http://de3.php.net/manual/en/book.zip.php ) extension.



== Changelog == 

= 0.1 =

* first version with the base functions