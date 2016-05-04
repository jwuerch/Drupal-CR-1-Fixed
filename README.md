# Book Review Site In Drupal - April 22, 2016

## Description

This Drupal application allows for authenticated users known as "reviewers" to create their own book review, edit it and delete it. Anonymous users have the ability to view all contents of the site except a coupon code.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [MAMP](http://www.mamp.com/)

## Installation

* `git clone https://github.com/jwuerch/Druapl-CR-1.git`
* change into the new directory
* Start up MAMP and point servers to main directory
* Go to localhost:8888/phpmyadmin in browser and import `CR-1-Fixed.sql.zip` DB   
  found in Drupal-CR-1/sites/DB-Backup
* Create DB username `admin5` with password `admin5`
* Go to localhost:8888 to view Drupal project.

## Databases Used
* `CR-1-Fixed`

## Usernames and Passwords
* DB: `admin5:admin5`
* Drupal site maintenance account: `admin5:admin5`
* Reviewer user: `reviewer:reviewer`

## Running / Development

* Visit your app at [http://localhost:8888](http://localhost:8888).

### Deploying

All you need to deploy is to visit localhost:8888. The app is currently not hosted.

##License

This software is licensed under the MIT license.
Copyright (c) 2016 _**Jason Wuerch**_.
