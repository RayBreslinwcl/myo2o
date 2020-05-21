# 1.tomcat打印日志，中文是乱码

原因竟然是：idea和tomcat默认VM不是utf-8

具体解决参考：https://blog.csdn.net/u010886217/article/details/104320782?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522159003593019195162515546%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=159003593019195162515546&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v2~rank_v25-2-104320782.nonecase&utm_term=%E4%B9%B1%E7%A0%81

# 2.登录密码
xiangze/admin，数据库里是tb_local_auth表，并且做过md5加密的。