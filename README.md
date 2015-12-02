ansible-silk
=========

ansible-silk - based on SiLK in a box https://tools.netsa.cert.org/confluence/pages/viewpage.action?pageId=23298051

Requirements
------------

Ubuntu 12.04/14.04 are tested

Role Variables
--------------

Software versions: 
- silk_ver
- libfixbuf_ver
- yaf_ver

- eth_device: ethernet device for SiLK to listen on
- networks: list of cidrs to parse


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: andyhky.ansible-silk, x: 42 }

License
-------

BSD

Author Information
------------------

Andy Hill - andyhky.com @andyhky
