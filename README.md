Peco installation
=========

Install peco
https://github.com/peco/peco

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Example Playbook
----------------

```
hosts: servers
roles:
   - role: kentrino.peco
     peco_version: 0.5.3
```

License
-------

MIT
