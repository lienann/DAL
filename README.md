# Data Access Levels

Wordpress plugin. Restrict access to posts by user access level.

-----------------------

### Description

This plugin allow to set access level value for users and materials and limit 
access to materials of a specific type (posts, pages, custom post types) when 
user access level lower then material access level.

Also this plugin creates a new capabilities:

1. dal_admin - capability to change plugin settings
2. dal_edit - capability to change user access level

**Attention to developers!** 
Filters used in this plugin does not work when using get_posts() with
the parameter 'suppress_filters' => true.

Install script don't assign any values of user access levels and post access levels.
By default post access level = 100 and user access level = 0 (except Administrator = 100 ).
By default access to posts is limited in front-end. There is an option 
"Should we apply restrictions in admin console?" in plugin settings to limit access in 
administrator interface too.
Users can assign records access level equal or lower their own access level.

**Languages:** English, Русский

I apologize for possible mistakes in plugin translation.
I will be glad to accept the help with the correct translation of a plugin into
English and to correction of my mistakes.


### Installation

1. Upload the `data-access-levels` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to the Tools -> DAL settings


### Changelog
Please see `readme.txt` for changelog
