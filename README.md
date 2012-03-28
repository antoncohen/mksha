# mksha #

Little Python script to create SHA-512 hashes compatible with Linux shadow
passwords. The hashes can be used in Puppet manifests or Kickstart configs.

Right now it has no options and only does SHA-512.

## Requires ##

python-passlib

Red Hat (requires EPEL in RHEL/CentOS):

    yum install python-passlib

Debian-based (in Debian wheezy and squeeze-backports, and Ubuntu precise):

    apt-get install python-passlib

Cheeseshop:

    pip install passlib

Or:

    easy_install passlib

## Usage ##

Clone the git repo, cd to the directory and:

    ./mksha

Enter a password at the prompt, a SHA hash will be printed to stdout.

## Author ##

* Anton Cohen <anton@antoncohen.com>
* [Source](https://github.com/antoncohen/mksha)
* [Homepage](http://www.antoncohen.com/)
* [@antoncohen](http://twitter.com/antoncohen)
