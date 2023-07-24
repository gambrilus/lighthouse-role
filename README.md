Ansible role: lighthouse-role
=========

Deploy & configure Lighthouse on Centos 7 using ansible.

Requirements
------------

Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)
Git
epel-release
nginx

Role Variables
--------------

| vars | description                 | default value |
|------|-----------------------------|---------------|
|lighthouse_url   | URL for lighthouse git repo |https://github.com/VKCOM/lighthouse.git      |
|lighthouse_dir   | work directory              |/home/gambrilus/lighthouse               |
|lighthouse_nginx_user  | nginx user                  |root           |

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - lighthouse-role

License
-------

MIT

Author Information
------------------

Andrey Gavrilov, Netology Student