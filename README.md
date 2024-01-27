nodejs
=================

Install node.js

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `nodejs_version`

Node.jsのバージョン

### `nodejs_global_install_yarn`

yarnのグローバルインストール

### `nodejs_global_install_pnpm`

pnpmのグローバルインストール

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
