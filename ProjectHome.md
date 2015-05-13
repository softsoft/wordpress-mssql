### MSSQL For Wordpress ###
Contributors: Aizu Ikmal Ahmad & Iwani Khalid

Requires at least: 2.3.0

Tested up to: 2.7.1

Development Status: Alpha

Database Abstraction Class: ezSQL by Justin Vincent (http://php.justinvincent.com)


**How to install MS-SQL support for Wordpress**

1. Download this version of Wordpress ( http://wordpress.org/wordpress-2.7.1-IIS-RC1.zip ) preferably
2. Then, upload it on your webhosting that supports MSSQL and IIS like how you would usually do it
3. Download our Magic Plugin at ( http://code.google.com/p/wordpress-mssql/ )
4. Then upload that db.php to your wp-contents folder
5. Edit the MSSQL database setting in db.php file according to your MSSQL settings
6. You're done :D

At this moment, this workaround works for these functions, to where we have debugged and tested

  * Basic submit, edit, manage posts and pages
  * Comments system
  * Dynamic sidebar
  * Changing themes
  * Installing plugins
  * Long text retrieval

What we didn't have time to debug

  * Pagination
  * Categories > Posts retrieval
  * Dates / Time of posts
  * Others which we look forward to debug later :D