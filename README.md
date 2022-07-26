INTRODUCTION
------------

The Default Drupal's Theme Has been used in The Events Management System.
<br>
A Custom Module "eventmodule" has been implemented to host all Events CRUD Operations. 
<br>
Event Module Comes with a Database table migration and a Routing to the 
Controller to list or show Events and a Store , update and Delete Event.

INSTALLATION
------------

* Install as you would normally install a contributed Drupal module. Visit
  https://www.drupal.org/node/1897420 for further information.

REQUIREMENTS
------------

First make sure to Install Drupal 9 on your machine.

Go to Administration Panel and navigate to Extend -> Then Install our module.

on *ur_domain.com/EventsManagementSystem/admin/modules* . 

Before This Step you may need to clear Cache by One of those:
* Navigate to Configuration then Performance.
* Use drush cr command, if you already have drush installed on your machine.

After Install The Custom Module.

You Know Able to Navigate the Module and do your CRUD Operations 


* [List Events](http://localhost/admin/events/index)
* [Show Event](http://localhost/admin/eventmodule/{id}/show)

CONFIGURATION
-------------

The module has no menu or modifiable settings. There is no configuration. When
enabled, the module will prevent the links from appearing. To get the links
back, disable the module and clear caches.

TROUBLESHOOTING
---------------

* If the menu does not display, check the following:

    - Are the "Access administration menu" and "Use the administration pages
      and help" permissions enabled for the appropriate roles?

    - Does html.tpl.php of your theme output the $page_bottom variable?

FAQ
---

Q: I enabled "Aggregate and compress CSS files", but admin_menu.css is still
there. Is this normal?

A: Yes, this is the intended behavior. the administration menu module only loads
its stylesheet as needed (i.e., on page requests by logged-on, administrative
users).


