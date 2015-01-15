# Tables-Module
This module is used for easing the database commands in PHP.

To use the module you have to configure local.php file.

1) Add the host name, username, password and database name.<br />
2) To use this module you need to include Table.inc file to your project file.

Example:<br />
1) Download and add files to your project.<br />
2) Consider index.php file.

<code>
require_once("Table.inc");</code>

<code>$userListTable = new Table("users");</code><br />
<code>$users = $userListTable->getAll(); //$users = will have all the data of users table</code><br />
<code>$userListTable->close();
</code>
