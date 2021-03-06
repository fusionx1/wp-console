WP Console
=============================================
The WordPress CLI. A tool to generate boilerplate code, interact with and debug WordPress.

## Releases Page
All notable changes to this project will be documented in the [releases page](https://github.com/weknowinc/wp-console/releases)


# Install

These instructions are intented for Unix, Linux, Mac OSX system, use sudo if you get permissions errors

```
curl https://weknowinc.com/wp-console/installer -L -o wordpress.phar
mv wordpress.phar /usr/local/bin/wordpress
chmod +x /usr/local/bin/wordpress
```

## Usage

### Available commands:
  
  * about                             Display basic information about Wordpres Console project
  * chain                             Chain command execution
  * exec                              Execute an external command.
  * help                              Displays help for a command
  * init                              Copy configuration files.
  * list                              Lists all available commands

 **cache**
  * cache:flush (cf)                  Flush the Wordpress object cache
 
 **chain**
  * chain:debug (cd)                  List available chain files.

 **container**
   * container:debug                  Displays current services for an application..

 **create**
  * create:users                      Create dummy users for your WordPress application.

 **generate**
  * generate:command (gc)             Generate commands for the console.
  * generate:metabox (gm)             Generate a meta box.
  * generate:plugin (gp)              Generate a plugin.
  * generate:shortcode (gs)           Generate a shortcode.  
  * generate:taxonomy (gta)           Generate a custom taxonomy.
  * generate:theme (gth)                   Generate a theme.
 
 **multisite**
  * multisite:install (mi)            Install a Wordpress multisite network
  * multisite:debug (md)              List all sites in network available to a specific user
  * multisite:new (mn)                Add New Site a Wordpress multisite network
 
 **plugin**
  * plugin:activate (pa)              Activate plugins or plugin in the application
  * plugin:deactivate (pd)            Deactivate plugins or plugin in the application
  * plugin:debug (pde)                Display current plugins available for application
 
 **site**
  * site:install (si)                 Install a Wordpress project
 
 **theme**
  * theme:activate (ta)               Activate theme in the application
  * theme:debug (td)                  Display current themes available for application

# How to contribute

## Fork
Fork your own copy of the [WordPress Console](https://bitbucket.org/weknowinc/wp-console/fork) repository to your account

## Clone
Get a copy of your recently cloned version of console in your machine.
```
$ git clone git@github.com:[your-git-user-here]/wp-console.git
```

## Configure a remote fork
```
$ git remote add upstream git@bitbucket.org:weknowinc/wp-console.git
```

## Sync your fork
```
$ git fetch upstream
$ git merge upstream/master
```

## Install composer dependencies

```
$ composer install.
```

# Supporting Organizations

[![weKnow](https://www.drupal.org/files/weKnow-logo_5.png)](http://weknowinc.com)

[![Anexus](https://www.drupal.org/files/anexus-logo.png)](http://www.anexusit.com/)

> WordPress is a registered trademark of [WordPress Foundation](http://wordpressfoundation.org/2010/trademark/).
