lesaint-mvn
===========

My Maven plugins for [Oh-My-Zsh](https://github.com/robbyrussell/oh-my-zsh) which can be integrated via [Antigen](https://github.com/zsh-users/antigen)


This is a fork of the mvn plugin bundled with oh-my-sh where :

* I removed all the existing aliases which I find to long and most of them are useless to me
* I added the alias I actually use
* Changed the wrapping function around mvn to support the following features
	+ enable multithreading by default (currenr value is 3 because my computer has 4 cores)
	+ multithreading can be disable with option `-n` from the command line
	+ maven output coloring (as is from the oh-my-zsh mvn plugin)
