# ansible-amimoto-wordpress-update
複数ある[網元](http://ja.amimoto-ami.com/)で作ったサイトのWordPressを一括でアップデートするAnsible Playbookです。

## 摘要条件
[網元](http://ja.amimoto-ami.com/)のデフォルトのインストールディレクトリに設置されたWordPressのみがアップデートの対象となっています。

バーチャルホストなどで、新たにWordPressを設置している場合は別途Playbookを作ってください

## 使い方
hostsにアップデートさせたい網元サイトの接続情報を記述してください

## Play it!
```bash
$ ansible-playbook -i hosts site.yml
```
