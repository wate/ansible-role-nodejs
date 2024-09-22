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

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `nodejs_version`

Node.jsのバージョン

#### `nodejs_global_install_yarn`

yarnのグローバルインストール

#### `nodejs_global_install_pnpm`

pnpmのグローバルインストール

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `nodejs_apt_key_url`

#### `nodejs_apt_key_download_dest`

#### `nodejs_apt_key_dest`

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
