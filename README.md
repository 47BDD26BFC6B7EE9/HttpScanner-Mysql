# python-HttpScanner-Mysql
文件说明：<br>
database.config 配置数据库连接信息<br>
ip-http-scanner.py 扫描程序<br>
ip-build-mysql.py  建库<br>
python ip-http-scanner.py -p 80 -l 0 -t 1000 -n 1024<br>
-p --port=端口，默认80<br>
-l --level=级别，默认0<br>
-t --timeout=超时，默认10秒<br>
-n --threads=线程数，默认255<br>

-l --level<br>
检查
0 插入数据，如果记录存在则覆盖<br>
1 插入数据，如果记录存在则追加<br>


python ip-build-mysql.py <br>
-i --ip-list-file=ip地址列表<br>



-----Mysql-----
-IPAddress    -
-WEB          -
---------------
