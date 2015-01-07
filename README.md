####鲁东大学教务系统快速评教代码
#使用之前将pingjiao.js上传至服务器
var s= document.createElement('script');s.src="http://www.ldxdxx.com/pingjiao.js";s.charset = 'utf-8';document.body.appendChild(s)
在教师评价页面把上面代码复制到浏览器地址栏，覆盖原来的网址，并且在网址最前面加"javascript:"    。"javascript:"   需要手动打，引号里面的，不带引号。反正最后效果，地址栏内容是   
javascript:var s = document.createElement('script');s.src="http://www.domain.com/pingjiao.js";s.charset = 'utf-8';document.body.appendChild(s)
