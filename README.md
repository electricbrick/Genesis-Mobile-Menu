Genesis-Mobile-Menu
===================

Mobile menu child theme drop-in for Genesis Framework. It is imperative that you have jQuery included in your core WP or theme files.

1) Place this lib folder in your Genesis child theme if you don't already have one.

2) Place the following code in child theme's functions.php, directly below the line "require_once( get_template_directory() . '/lib/init.php' );
":

<code> 
//* Mobile Menu
require_once(CHILD_DIR.'/lib/mobile-menu/init.php');
</code>
