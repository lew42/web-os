# Advanced API Licensing/Control

Let's say your module has several levels of functionality you would like to license at various levels:

* Free Tier
* Premium Tier
* Enterprise Tier

Many services do this.

I can imagine developers might want fine-grained control with regards to their features:
* Allow users to try some premium features N times, or for X days.
* Allow users to use a feature with some limitations.

These licensing controls need to be very granular, so a developer could easily grant/revoke/reconfigure access to features/functions at the API level.

Many of these concepts are similar to the user/group permissions system that is baked into file systems (read/write access), or the user roles/permissions system in WordPress.

I would also expect the licensing permissions to be closely integrated with the plugin/hook system.  If someone wants to extend a module to be able to add some custom logic at a certain event/hook, they might need a specific license level.
