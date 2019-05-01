# ansible-ruby

[Ruby](https://www.ruby-lang.org/) - A dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

[![Platforms](http://img.shields.io/badge/platforms-ubuntu-lightgrey.svg?style=flat)](#)

Tunables
--------
* `ruby_gems` (list) - Gems to be installed

Dependencies
------------
* [colstrom.apt-repository](https://github.com/colstrom/ansible-apt-repository/)

Example Playbook
----------------
    - hosts: servers
      roles:
         - role: colstrom.ruby
           version: 2.3
           ruby_gems:
             - ezmq
             - rbnacl
             - robot_sweatshop
             - self_identity

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* [Chris Olstrom](https://colstrom.github.io/) | [e-mail](mailto:chris@olstrom.com) | [Twitter](https://twitter.com/ChrisOlstrom)
* Aaron Pederson
* Justin Scott
