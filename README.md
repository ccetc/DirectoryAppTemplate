# CCETC/DirectoryBundle Template App
This Symfony app is a starting point for installing a Symfony app that uses the [CCETCDirectoryBundle](https://github.com/CCETC/DirectoryBundle).

## Installation
### 1. Clone from Github
In your terminal:

	$ git clone git@github.com:CCETC/DirectoryAppTemplate.git

### 2. Install dependencies
#### a. Install Composer
From the DirectoryAppTemplate root directory:

	$ curl -s https://getcomposer.org/installer | php

#### b. Install dependencies

	$ php composer.phar install

### 3. Copy dist config files
These file soften contain sensitive information, so their skeltons are in the git repo as "dist" files.  You can copy them, remove the "dist" extension, add the sensitive information and they will be ignored by git

#### a. Copy files
	$ cp app/config/security.yml.dist app/config/security.yml
	$ cp app/config/parameters.yml.dist app/config/parameters.yml.dist
	$ cp app/config/config_dev.yml.dist app/config/config_dev.yml

#### b. Customize files
The only requirement here is to add your database info to ``parameters.yml``.

### 4. Cleanup
#### a. Update DB?
#### b. Install assets?
#### c. Clear cache?
