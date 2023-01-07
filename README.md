nodejs
=================

Install node.js

OS Platform
-----------------

### Debian

- bullseye
- buster

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `nodejs_version`

Node.jsのバージョン

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: nodejs
```

License
--------------

Apache License 2.0
