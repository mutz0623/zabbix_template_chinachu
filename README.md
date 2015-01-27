# zabbix_template_chinachu


# ファイルについて

* zabbix_Template_App_Chinachu.xml

 * zabbixの監視テンプレート

* chinachu-operator

* chinachu-wui

 * ```service chinachu-{operator,wui} status```を実行した後に戻り値で状態を参照出来るように起動スクリプトを変更

 * /etc/init.d/に配置

* userparameter_chinachu.conf

 * Chinachu用監視テンプレートの為のユーザパラメータ設定ファイル

 * zabbixの設定ファイルのインクルードディレクトリ(/etc/zabbix/zabbix_agentd.d/等)に配置



# 最後に
このChinachu監視テンプレートは個人的に作成している物でChinachu開発元とは無関係です。
また、本テンプレートを使用した上で発生した如何なる問題に対しても責任は負いかねます。

このテンプレートは、Debian GNU/Linux7(wheezy)上に、開発元のチュートリアルにしたがって導入した環境を想定しています。


