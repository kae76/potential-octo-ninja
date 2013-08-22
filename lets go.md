##Purpose for this repo:
I need/would like a VM which will run on two diff local environments.  

Which will include LAMP/Drupal friendly stuff: Git, Drush, Sublime more probably that I've forgotten.

I plan to have the 'VM' on a disk and use the native 'host machines' to run the Virtual box.
looking to try and utilise Vagrant/PHPhet

**I am cross referencing these Repos/Gists/Blogs:**

*  TESTING THIS!
--> https://github.com/MFoster/instantdrupal  
* [Kiwimind](https://drupal.org/user/749470) help for setting up an environment:  
--> https://github.com/kae76/stealing-kiwiminds-mind  
* [Therobyouknow](https://drupal.org/user/197207)'s [experiment](https://drupal.org/node/2055947) using Vagrant [PuPHPet](https://puphpet.com/) etc...  
--> https://github.com/kae76/yolo-octo-dubstep 
* My [Quickstart](https://drupal.org/project/quickstart) / [Open Atrium](https://drupal.org/project/openatrium) set up malarky:  
~ I'm not happy with this process hence why I am doing this!  
--> https://gist.github.com/kae76/8aa7b7dd5ae0d3325873 (shh its secret!)  
* [Lauras](https://drupal.org/user/18973)'s set up is very useful:   
--> http://pingv.com/blog/precisely-drupal-setting-up-ubuntu-12-04-precise-pangolin-lamp-stack-for-your-drupal-7-site  
* Headless Unbuntu etc:  
--> http://hybridlogic.co.uk/2011/07/setting-up-ubuntu-server-in-virtualbox-for-a-headless-lamp-server-in-mac-os-x-lion  
* Some permission fun games:  
--> http://stackoverflow.com/questions/1580596/how-do-i-make-git-ignore-mode-changes-chmod   

###Starting from scratch:

Two machines each with [Virtual Box 4.2.16 r86992](https://www.virtualbox.org/wiki/Downloads) installed.

**Machine one:**  
* MBP (13-inch, Mid 2009)  
* OSX 10.8.4   
* 2.2GHz INTEL Core 2 Duo  
* 8GB  
* 64-bit  

**Machine two:**  
* Acer Aspire 721 (11 inch, bought 2009)  
* Windows 7 Home Premium Service pk1  
* AMD Athlon II Neo K145 Processor 1.8GHz  
* 4GB  
* 64-bit  

**The VM disk:** 
32GB SD HC card formatted to fat32
