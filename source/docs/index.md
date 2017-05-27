title: 概述
---

欢迎使用 Awheel，本文档将帮助您快速上手。如果您在使用过程中遇到问题，您可以在 [GitHub](https://github.com/awheel/awheel/issues) 上提问。

## 什么是 Awheel？

Awheel 是一个轻量级的遵循 RESTful、PSR 规范的 PHP 开发框架，帮助您快速开发 Api 类型的支撑系统，借助组件扩展能力同样能完美支撑各种业务类型。

## 使用前提

安装 Awheel 是很轻松容易的，Awheel 构建在 Composer 之上，所以安装也推荐使用 Composer 的方式。
因此在安装前，您必须确认电脑中是否已安装下列应用程序：

- [Composer](https://getcomposer.org/)
- [Git](http://git-scm.com/)

如果您的电脑中已经安装上述必备程序，那么恭喜您！接下来只需要执行一条命令即可完成 Awheel 的安装。

``` bash
$ composer create awheel/awheel
```

{% note warn 重要 %}
进入下一步前，Awheel 要求您有一定的理论基础储备，包括但不局限于：MVC、RESTful、PSR、IoC。
如果您有过 Laravel、Symfony 使用经验更佳，Awheel 大量借鉴或使用了 Symfony 和 Laravel 的组件、代码和思想。
{% endnote %}

## 参考

- [Representational State Transfer](https://zh.wikipedia.org/wiki/REST)
- [Model–view–controller](https://zh.wikipedia.org/wiki/MVC)
- [PHP Standards Recommendations](http://www.php-fig.org/psr/)
- [Inversion of Control](https://zh.wikipedia.org/wiki/Inversion_of_control)