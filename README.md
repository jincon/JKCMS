# JKCMS手册
>JKCMS是本人做的一个简单的基于ThinkPHP的后台管理系统，注意只是后台管理系统，没有前台哦，前台需要自己写的

### index.php
* 定义系统的根路径：ROOT_PATH

`define("ROOT_PATH", dirname(__FILE__));`

### Html静态页面
`$this->buildHtml("index",ROOT_PATH."/");`

### 常见函数
* get_ip()     //获取IP函数
* array_iconv($fContents, $from='gbk', $to='utf-8')   //自动转换字符集 支持数组转换
* block($k,$cache=true)     //碎片获取函数
* adv($k,$cache=true)      //广告获取函数
* password($password,$salt='')         //系统文本加密函数
* sendemail($to,$subject,$content)      //系统邮件发送函数
* rand_string($len=6,$type='',$addChars=''         //产生随机字串
* remove_xss($val)         //系统过滤xss函数
