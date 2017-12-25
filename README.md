EasyAdmin Demo
==============

A Symfony demo backend to show [EasyAdmin](https://github.com/javiereguiluz/EasyAdminBundle) features.

How to install this project
---------------------------

  1. `git clone https://github.com/baris1892/easy-admin-demo`
  1. `cd easy-admin-demo`
  1. `composer install`
  1. Edit `.env` and configure
     credentials to acces a database for this demo.
  1. `php bin/console doctrine:database:create`
  1. `php bin/console doctrine:schema:create`
  1. `php bin/console doctrine:fixtures:load --append`
  1. `php bin/console assets:install --symlink`
  1. Browse `http://localhost/easy-admin-demo/public/admin`
