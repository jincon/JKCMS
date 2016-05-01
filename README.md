# JKCMS手册
>JKCMS是本人做的一个简单的基于ThinkPHP的后台管理系统，注意只是后台管理系统，没有前台哦，前台需要自己写的

## index.php
* 定义系统的根路径：ROOT_PATH
<code>define("ROOT_PATH", dirname(__FILE__));</code>

## Html静态页面
* $this->buildHtml("index",ROOT_PATH."/");

## 常见函数
* get_ip()  获取IP函数
* array_iconv($fContents, $from='gbk', $to='utf-8')   //自动转换字符集 支持数组转换
