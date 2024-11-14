# 実行方法

```shell
# sudo -s
# ansible-playbook -i hosts.yml ex-server.ansible.yml
```

# ファイル/フォルダ内容

- files:

設定ファイル、スクリプトなどを配置するディレクトリ

- ex-server.ansible.yml:

playbookのYAML形式ファイル

- hosts.yml: 

インベントリYAMLファイル。対象がローカルホストなのでなくてもいいかも。