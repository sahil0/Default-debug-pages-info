# 

Default-debug-pages-info

These are also referred to as default files/folders/url that contain crucial information of servers. Hackers exploit these default files which further helps them to plan their attacks. Below are few examples of default files that you may find in a website.

1. Robots.txt - One can find this file in the base directory of a website. This file is used by server administrators to disallow search engines like Google, Bing, etc. to record certain pages/folders as it may contain interesting folders and files which a developer is trying to hide.

2. Phpinfo.php - This file is a common debug file in PHP applications that contains huge amount of information regarding the server.

3. Users.xml - This file generally contains usernames and passwords which hackers may exploit.

4. Backup.sql - This default file is crucial as it may contain complete database backup.

5. Config.bak - This may be a configuration file that stores passwords and keys.

6. error_log / error.log - This file contains all error logs of the server which can reveal vulnerabilities to hackers.

7. server-status and server-info - These are common Apache page that contains server information.

8. manager/html - This default url takes you to Tomcat login page that can further disclose sensitive server information.

9. phpmyadmin - It is the login page for PHPmyadmin - a software used for managing SQL databases from the website. Exploiting a database can compromise all the data inside it.

Apart from these, there are many more default files that you should check and search for. You might not be able to find these default files as they may have been restricted by server administrators.
