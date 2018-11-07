<p align="center">
    <h1 align="center">Yii 2 Extended Basic Project Template</h1>
    <br>
</p>

Yii 2 Extended Basic Project Template is a skeleton [Yii 2](http://www.yiiframework.com/) application best for
rapidly creating small projects, based on Standard Yii2 Basic Project Template.
The Base of the project takes from an article of the [ElisDN blog](https://elisdn.ru/blog/60/seo-service-on-yii2-installing-of-application)

The template differs from the base template in a convenient deployment system. It offers the easy supporting in the Git system.

DIRECTORY STRUCTURE
-------------------

      assets/             contains assets definition
      commands/           contains console commands (controllers)
      config/             contains application configurations
      controllers/        contains Web controller classes
      environments/       contains sets of files for environments deploy    <-- added
      mail/               contains view files for e-mails
      models/             contains model classes
      runtime/            contains files generated during runtime
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      views/              contains view files for the Web application
      web/                contains the entry script and Web resources



REQUIREMENTS
------------

The minimum requirement by this project template that your Web server supports PHP 5.5.0.


INSTALLATION
------------

### Install via Composer

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).

You can then install this project template using the following command:

~~~
composer create-project --stability=dev sansurf/yii2-extended-basic project
~~~

or clone the repository for `pull` command availability:

~~~
git clone git@github.com:Sansurf/yii2-extended-base-template.git project
cd project
composer install
~~~

Init an environment:

~~~
php init
~~~

Fill your DB connection information in `config/common-local.php`.