#UNCC Textbook Finder Launch Documentation

The textbook finder website requires a PHP and MySQL server to run. For ease of setup this
guide will use XAMPP (https://www.apachefriends.org/download.html) to provide both.

1. Install the appropriate version of XAMPP for your system with the Apache and MySQL servers selected.
2. After installing, open the XAMPP Control Panel and start both the Apache and MySQL servers.
3. Once started, click on the “Admin” button for the MySQL server which should link to http://localhost/phpmyadmin/
4. Select the “Import” heading along the top
5. In the section “File to import”, select browse and choose database_creation.sql provided in the src folder
6. Click the “Go” button at the bottom of the page and the setup for test version of the database should complete successfully
7. Now move the TextbookFinder folder and its contents provided in the src folder to the htdocs folder in your XAMPP directory so that you have the folder structure/xampp/htdocs/TextbookFinder
8. If you now navigate to http://localhost/Textbookfinder/index.php in your browser you should arrive at the homepage of the UNCC Textbook Finder and be able to navigate from there to the other pages