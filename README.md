Debian-Imagemagick
==================

And Now a Touch of Magick ImageMagick® is a software suite to create, edit, compose, or convert bitmap images.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-imagemagick }

Tasks
-----

  - Install [ImageMagick](http://www.imagemagick.org/)

License
-------

BSD