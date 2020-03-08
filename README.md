Menu Per Role
========
This module allows you to restrict access of menu items per roles.

KNOWN CONFLICTS
---------------

 * Menu token (https://www.drupal.org/project/menu_token): Menu token erase the access result of Menu per role, see https://www.drupal.org/node/2044963


INSTALLATION
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- configure options at  admin/config/system/menu_per_role


CONFIGURATION
-------------

Global settings: /admin/config/system/menu_per_role

Just activate the Menu per Role module and edit a menu item as usual. There will be one or two fieldsets, depending on the configuration of the module, that allows you to restrict access by role.

If you don't check any roles the default access permissions will be kept.

Otherwise the module will additionally restrict access to the chosen user roles.


License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.

Current Maintainers
-------------------

This module is currently maintained for Backdrop by Ericfg .

Credits
-------

Ported to Backdrop by Eric Goldhagen (https://github.com/ericfg/)

Drupal Module maintainers:
 * Daniel Wehner (dawehner) - https://www.drupal.org/user/99340
 * Florent Torregrosa (Grimreaper) - https://www.drupal.org/user/2388214

Previous maintainers:
 * Wolfgang Ziegler (fago) - https://www.drupal.org/user/16747
 * AlexisWilke (AlexisWilke) - https://www.drupal.org/user/356197
