Role Name
=========

Installs ssh banner which displays prior to login

Requirements
------------

None

Role Variables
--------------

```
banner_text: "banner text" # (for default see defaults/main.yml)
```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: bantl23.banner, banner_text: "hello", become:yes, become_user: root, become_method: sudo }

License
-------

MIT

Author Information
------------------

Use [github](https://github.com/bantl23roles/banner) to file issues
