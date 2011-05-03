# Drupal - Simple Subscriptions

This module is an extremely simple subscriptions module which allows users to subscribe to a node's comments (specifically, NodeComment comments).

Users receive an email upon subscription and then a single email for each new comment published to the discussion. A user can subscribe either by clicking a link that can be placed on the node's display, or via a checkbox in the nodecomment form.

Users can unsubscribe by clicking either a link displayed in the node or the link present at the bottom of the default email included with the module.

## Drupal Topics

The main topic this code covers is the use of the `drupal_mail()` function, which due to its flexibility is somewhat cumbersome to use for simple purposes.

As with most modules, this code also shows examples of using custom permissions, different kinds of `hook_menu()` callbacks, and using the Form API to change how form submissions are handled.
