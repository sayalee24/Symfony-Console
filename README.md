# PHP coding challenge
For the command line script, I have created symfony console application which can run using command. I have created array to store employee data.

### Assumptions for requirements

Vacation days will be 0 if input year is before their joining year


### Prerequisites
Download and install latest php version http://www.php.net/downloads.php

First install composer https://getcomposer.org/download/

 
Check if composer is installed or not and its version
```
composer --version
```

Composer version 2.0.6

Symfony CLI version v4.22.0


### Installing

1) download the zip file named Symfony_coding_challenge

2) open command prompt or shell and locate to folder

3) After locating folder run below command to find the symfony command 

```
php bin/console
```
There you can find Pepper-Employee command and its descritption

4) Run the command with year as a input

php bin/console Pepper-Employee input-year
for eg:

```
php bin/console Pepper-Employee 2021
```
After entering input, table with employee name and their respective days will be displayed


## Running the tests
Run the test for the command 

```
php bin/phpunit
```


