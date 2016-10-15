# README #

### What is the Project status? ###
This project is unmaintained, since the extcv functionality is now included in VeraCrypt.
If you can, [go and fetch VeraCrypt](https://veracrypt.codeplex.com)
If you have to use TrueCrypt 7.1a for some reason, you can use this to extend your volumes. But take note that TrueCrypt contains unpatched bugs and security problems!

### What is this repository for? ###

* This is a fork of extcv updated to work with TrueCrypt 7.1a
* extcv 0.7 is a tool to enlarge a truecrypt container
* [original, unmaintained project is here](http://sourceforge.net/projects/extcv/)

### How do I get set up? ###

* Install TrueCrypt 7.1a, because the kernel driver is needed for extcv
* For convenience, TrueCrypt 7.1a is available here too. DO NOT USE TRUECRYPT 7.2 or anything other than the 7.1a version for now!
* Download and run extcv.exe

### Detailed usage ###
There is a [great blog post](http://goo.gl/Swm0dz) how to use extcv!

### Contribution guidelines ###

I am open to accept any useful patches because the original project is dead.
Please also do report all bugs you encounter!

### Security warning ###

While not filling the new allocated space with random data is much faster, it might lower your security!
Choose wisely!