# Speedwork Homestead
=================================
[![codecov](https://codecov.io/gh/speedwork/homestead/branch/master/graph/badge.svg)](https://codecov.io/gh/speedwork/homestead)
[![StyleCI](https://styleci.io/repos/65539131/shield)](https://styleci.io/repos/65539131)
[![Latest Stable Version](https://poser.pugx.org/speedwork/homestead/v/stable)](https://packagist.org/packages/speedwork/homestead)
[![Latest Unstable Version](https://poser.pugx.org/speedwork/homestead/v/unstable)](https://packagist.org/packages/speedwork/homestead)
[![License](https://poser.pugx.org/speedwork/homestead/license)](https://packagist.org/packages/speedwork/homestead)
[![Total Downloads](https://poser.pugx.org/speedwork/homestead/downloads)](https://packagist.org/packages/speedwork/homestead)
[![Build status](https://ci.homesteadveyor.com/api/projects/status/10aw52t4ga4kek27?svg=true)](https://ci.homesteadveyor.com/project/2stech/homestead)
[![Build Status](https://travis-ci.org/speedwork/homestead.svg?branch=master)](https://travis-ci.org/speedwork/homestead)


The official Speedwork local development environment.

## Introduction

Speedwork strives to make the entire PHP development experience delightful, including your local development environment. [Vagrant](http://vagrantup.com) provides a simple, elegant way to manage and provision Virtual Machines.

Speedwork Homestead is an official, pre-packaged Vagrant box that provides you a wonderful development environment without requiring you to install PHP, HHVM, a web server, and any other server software on your local machine. No more worrying about messing up your operating system! Vagrant boxes are completely disposable. If something goes wrong, you can destroy and re-create the box in minutes!

Homestead runs on any Windows, Mac, or Linux system, and includes the Nginx web server, PHP 7.0, MySQL, Postgres, Redis, Memcached, Node, and all of the other goodies you need to develop amazing Speedwork applications.

> **Note:** If you are using Windows, you may need to enable hardware virtualization (VT-x). It can usually be enabled via your BIOS. If you are using Hyper-V on a UEFI system you may additionally need to disable Hyper-V in order to access VT-x.
