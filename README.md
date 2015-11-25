# lnbush


Create a directory structure whose files are symlinks to files within 
another directory structure. Written in BASH for easy modifications.

Directories are real local directories, files are symlinks.

I use this to keep a local copy of a very large and very slow ftp site. So that I can search the site without waiting. Once I've found what I need I can double click the local symlink and it opens the linked file from the FTP site.

Similar to the c program [lndir](http://linux.die.net/man/1/lndir).


Similar to the perl program [lntree](http://search.cpan.org/~rokr/App-lntree-0.0013/lib/App/lntree.pm). 



###Usage


```
	lnbush -[vh] sourcedir targetdir
```

