# Lab.Perl
A repository that serves as my lab for exploring Perl programming

References
* https://www.perl.org/

Perl for Windows
* http://strawberryperl.com/
* http://www.activestate.com/activeperl

Learning Resources
* http://learn.perl.org/



Upgrading Perl (e.g. on Ubuntu)
NOTE: It is suggsted that upgrading your 'system' perl, spearately, may be a bad idea - in that for a given release of Linux, there are system dependencies - and [it is suggested] (http://stackoverflow.com/questions/34762819/how-can-i-upgrade-my-perl-version-in-ubuntu) to do a source build and install in /usr/local/bin
* ```sudo cpan```
  * cpan[1]>```upgrade```

Or,
* ```sudo perl -MCPAN -e 'upgrade'

Or, (Note: I haven't tested this command myself...just adding to my notes for future reference)
* ```sudo apt-get install perlbrew```
* ```perlbrew init```
* ```perlbrew install perl-5.xx.x``` - where xx.x is the version  you want to install...


