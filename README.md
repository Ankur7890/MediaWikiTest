# MediaWikiTest

#MediaWiki is based on  LAMP and requires L7 webserver (apache/nginx), mysql, php and mediawiki static content.
We are going with nginx webserver and creating 2 docker images i.e one for nginx+php and another one for mysql
localsetting php file will be generated as part of the setup which needs to be placed under static mount.
