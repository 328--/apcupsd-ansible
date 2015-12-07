hostsにIPアドレスを記述

実行
```
ansible-playbook -i hosts playbook.yml --ask-pass --ask-sudo-pass -vvvv
```
確認コマンド
apcaccess status
