nodejs开发微信公众号笔记<br/>
=======
###配置、接入微信公众号<br/> 
测试公众号入口：http://mp.weixin.qq.com/debug/cgi-bin/sandboxinfo?action=showinfo&t=sandbox/index<br/>
入口文件模块：koa框架 path Generator中间键 util中间键<br/>
Generator中间键模块：sh1加密 raw-body<br/> 
util中间键模块：bluebird fs<br/>
服务器代理:ngrok/花生壳/localtunnel/utralhook <br/>

###票据access_token<br/>
规则:7200s失效 需每隔2小时启动刷新一次票据 为方便频繁使用,需要把票据存储在一个唯一的地方
