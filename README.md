# php-standard-demo
PHP 规范示例工程

## 介绍

团队协作中，规范显得尤其重要。我们可以通过一些现有的自动化工具来进行规范。
本工程结合了当前社区的工具，只选出了必要的工具，所谓小而精，大概也说的就是
这件事情。

**php-cs-fixer**

地址：[friendsofphp/php-cs-fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer)

安装：`composer require friendsofphp/php-cs-fixer --dev -vvv`

一句话介绍：自动格式化校正代码风格

**phpmd**

地址：[phpmd/phpmd](https://github.com/phpmd/phpmd)

安装：`composer require phpmd/phpmd --dev -vvv`

一句话介绍：检测 PHP 的命名、代码复杂度规范等

**phpcpd**

地址：[sebastianbergmann/phpcp](https://github.com/sebastianbergmann/phpcpd)

安装：`composer require sebastian/phpcpd --dev -vvv`

一句话介绍：检测项目是否存在代码到处复制粘贴

## 使用

我们结合 composer script 进行使用。

- `**composer check-copy-src**` 检测代码是否存在复制情况
