# _Afton Downey's Portfolio_

#### This is my personal portfolio written in Drupal  | April 22, 2016

#### By: Afton Downey

## Description

This website is my personal Drupal Portfolio. It contains professional information about me, contact info and some custom modules that I have built.

## Prerequisites

You will need the following things properly installed on your computer:<br>
• [Drupal](https://www.drupal.org/project/drupal)<br>
• [MAMP] (https://www.mamp.info/en/)

## Setup/Installation Requirements

1. Open Terminal and clone this repository: https://github.com/aftondowney/my_drupal_portfolio.git
2. In your browser navigate to ```http://localhost:8888/phpmyadmin```, here is where you can select the Import tab and in the project directory go to ```sites > db-backups > aftons_portfolio.sql(1).zip``` and click GO at the bottom of your screen
3. Also in phpmyadmin, recreate the user you created initially in the database (username: afton and password: afton, can also be found in the settings.php file)
4. Open MAMP, select ```Preferences```, select ```Web Server``` tab, direct the ```Document Root``` at the top level of your project folder
5. Navigate to ```http://localhost:8888```
6. Login as user:admin pw:password

## For 5/13 Code Review
1. Displaying projects for Ajax view, module named projects_ajax.
2. Tests are in the DNA module.

## Known Bugs

1. The ajax call on the projects sidebar links is giving an Ajax HTTP error 500.
2. Unit tests for DNA module are currently failing, although module seems to be functioning as expected.

## Support and Contact Details

If you have any issues, questions, ideas, or concerns contact me through GitHub.

## Technologies Used

• Drupal<br>
• phpMyAdmin<br>
• Simpletest<br>
• PHP<br>
• GIT<br>


## License
MIT License

Copyright (c) 2016  |  Afton Downey  |  Epicodus  |  Portland, OR
