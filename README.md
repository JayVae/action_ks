# action_ks

使用代码中直接写cooikes的方法会显示ck过期？
解决：在action中加入环境变量；KS_COOKIE，格式是去掉引号。

运行时间是30 1,8,12,17 * * *  //在action中要减去8小时。