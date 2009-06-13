=== Plugin Name ===
Contributors: wolly
Tags: author description,
Donate link: no link
Requires at least: 2.8
Tested up to: 2.8
Stable tag: 1.1

This plugin allow you to show the description of the author of the post. Useful for multi authors blog.

== Description ==

This plugin allow you to show where you want, inside the loop, a gravatar of the author of the post, the description of the author of the post, the nick of the author of the post and the date of the post.



== Installation ==

1. Upload `addauthor` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place `<?php if( function_exists( 'wolly_addaut' ) ) wolly_addaut();  ?>` in your templates where you want to show the author description WITHIN the loop.
4. Insert new class in yours style.css '.addaut' and '.addaut .avatar'. You find an example in the file 'sample.css'
5. register to gravatar.com yours authors
6. fill in, under yours profile, the description of the authors

For 2.8 use the 1.1 for 2.7 use only 1.0 cause the 1.1 has the new function.
== Frequently Asked Questions ==
Why use this plugin?
To show a gravatar and a descritpion of the author(s) of your blog

== Screenshots ==
No screen shot

== Arbitrary section ==

== A brief Markdown Example ==


