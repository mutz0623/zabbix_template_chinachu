# zabbix_template_chinachu


# ファイルについて

* zabbix_Template_App_Chinachu.xml
zabbixの監視テンプレート

** chinachu-operator
** chinachu-wui
```service chinachu-{operator,wui} status```を実行した後に戻り値で状態を参照出来るように起動スクリプトを変更
/etc/init.d/に配置

** userparameter_chinachu.conf
Chinachu用監視テンプレートの為のユーザパラメータ設定ファイル。
zabbixの設定ファイルのインクルードディレクトリ(/etc/zabbix/zabbix_agentd.d/等)に配置

