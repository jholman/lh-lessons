# LHL-on-Windows : Vagrant

## Introduction

This file attempts to plan and document a strategy for doing the LHL curriculum on a Windows computer.  This is one of multiple approaches I am documenting.

In this approach, we try to install and use Vagrant and VBox, as similarly to the main curriculum instruction as we can.

### Expected hurdles

* `PATH` problems (preventing us from just opening a prompt and typing `vagrant`
* `PATH` problems (preventing vagrant from finding `ssh`)
* filesystem challenges with the linux/windows shared directory

## Log

Watched https://www.youtube.com/watch?v=mPBWWu7sZU4&vl=en and followed instructions therin:
1) Download and install virtual box (per lighthouse 5.2.x)
2) Download and install Vagrant (https://www.vagrantup.com/downloads.html) (restart required)
3) Download extract and run cmder (https://cmder.net/)
IN CMDER
4) vagrant -v  (to confirm vagrant install)
follow lighthouse instructions from here
5) cd to C:\Users\youruser
6) mkdir lighthouse
7) cd lighthouse
8) curl -O http://d10ofk0qhbh8u9.cloudfront.net/vagrant/Vagrantfile  (per lighthouse step 3)
9) vagrant up
10) vagrant ssh
11) create test file and check it in windows

all appears to be working.   key thing.  use cmder




