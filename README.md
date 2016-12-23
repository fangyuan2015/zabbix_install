# zabbix_install

[安装](doc/install.md)

[说明](doc/info.md)


其他相关项目

> * zabbix管理工具---------------------------------------------[zabbix_manager](https://github.com/BillWang139967/zabbix_manager)
> * zabbix报警工具---------------------------------------------[zabbix_alert](https://github.com/BillWang139967/zabbix_alert)
> * zabbix常用模板---------------------------------------------[zabbix_templates](https://github.com/BillWang139967/zabbix_templates)


## 参加步骤

* 在 GitHub 上 `fork` 到自己的仓库，然后 `clone` 到本地，并设置用户信息。
```
$ git clone https://github.com/BillWang139967/zabbix_install.git
$ cd zabbix_install
$ git config user.name "yourname"
$ git config user.email "your email"
```
* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```
* 在 GitHub 网站上提交 pull request。
* 定期使用项目仓库内容更新自己仓库内容。
```
$ git remote add upstream https://github.com/BillWang139967/zabbix_install.git
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```
