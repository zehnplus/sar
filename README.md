# Drush SAR for Drupal 8

## How do you use this?

Download and enable the module like any other Drupal 8 module.

Use `drush sar node 'replace me' 'new text'` to replace all occurrences of
"replace me" with "new text" in all text fields (node body and field API).

You can uninstall the module when finished.

Be sure to backup your database before running this command.
There are no other ways to revert the changes SAR does.
The script will remind you to do so of course!
