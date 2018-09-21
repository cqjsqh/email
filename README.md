# email
h5邮箱地址汇总

```
var rules = [
  {
    match: /@(qq|foxmail)\.com$/,
    name: 'QQ邮箱',
    url: 'https://ui.ptlogin2.qq.com/cgi-bin/login?style=9&appid=522005705&daid=4&s_url=https%3A%2F%2Fw.mail.qq.com%2Fcgi-bin%2Flogin%3Fvt%3Dpassport%26vm%3Dwsk%26delegate_url%3D%26f%3Dxhtml%26target%3D&hln_css=http%3A%2F%2Fmail.qq.com%2Fzh_CN%2Fhtmledition%2Fimages%2Flogo%2Fqqmail%2Fqqmail_logo_default_200h.png&low_login=1&hln_autologin=%E8%AE%B0%E4%BD%8F%E7%99%BB%E5%BD%95%E7%8A%B6%E6%80%81&pt_no_onekey=1'
  },
  {
    match: /@163\.com$/,
    name: '163邮箱(网易)',
    url: 'https://dl.reg.163.com/ydzj/maildl?product=mail163&pdconf=yddl_mail163_conf&mc=0F6099&curl=https%3A%2F%2Fmail.163.com%2Fentry%2Fcgi%2Fntesdoor%3Ffrom%3Dsmart%26language%3D0%26style%3D11%26allssl%3Dfalse%26destip%3D192.168.193.48%26df%3Dsmart_ios'
  },
  {
    match: /@126\.com$/,
    name: '126邮箱(网易)',
    url: 'https://passport.126.com/ydzj/maildl?product=mail126&pdconf=yddl_mail126_conf&mc=146E1F&curl=https%3A%2F%2Fmail.126.com%2Fentry%2Fcgi%2Fntesdoor%3Ffrom%3Dsmart%26language%3D0%26style%3D11%26destip%3D192.168.202.48%26allssl%3Dfalse%26df%3Dsmart_ios'
  },
  {
    match: /@yeah\.net$/,
    name: 'Yeah邮箱(网易)',
    url: 'https://passport.yeah.net/ydzj/maildl?product=mailyeah&pdconf=yddl_mailyeah_conf&mc=00789A&curl=https%3A%2F%2Fmail.yeah.net%2Fentry%2Fcgi%2Fntesdoor%3Flightweight%3D1%26verifycookie%3D1%26language%3D0%26style%3D11%26destip%3D172.16.85.55%26allssl%3Dfalse%26from%3Dsmart%26df%3Dsmart_ios'
  },
  {
    match: /@sina\.(com|cn)$/,
    name: '新浪邮箱',
    url: 'https://mail.sina.cn/?vt=4'
  },
  {
    match: /@sohu\.com$/,
    name: '搜狐邮箱',
    url: 'https://m.mail.sohu.com/fe/#/login'
  },
  {
    match: /@(tom\.com)$/,
    name: 'Tom邮箱',
    url: 'http://mail.tom.com/'
  },
  {
    match: /@139\.com$/,
    name: '139邮箱(移动)',
    url: 'http://html5.mail.10086.cn/'
  },
  {
    match: /@aliyun\.com$/,
    name: '阿里云邮箱',
    url: 'https://mail.aliyun.com/'
  },
  
  // 国外邮箱
  {
    match: /@yahoo\.com$/,
    name: '雅虎邮箱',
    url: 'https://login.yahoo.com/'
  },
  {
    match: /@(outlook|hotmail)\.com$/,
    name: '微软邮箱',
    url: 'https://login.live.com/login.srf'
  },
  
  // 企业邮箱
  
  // VIP邮箱
  {
    match: /@vip\.163\.com$/,
    name: '163 VIP邮箱(网易)',
    url: 'http://vip.163.com/webapp/login163.html'
  },
  {
    match: /@vip\.126\.com$/,
    name: '126 VIP邮箱(网易)',
    url: 'http://vip.126.com/webapp/login126.html'
  },
  {
    match: /@vip\.sina\.com$/,
    name: '新浪VIP邮箱',
    url: 'https://mail.sina.cn/?page=vipmail&vt=4'
  },
  {
    match: /@vip\.sohu\.com$/,
    name: '搜狐VIP邮箱',
    url: 'https://vip.sohu.com/#/login'
  },
  {
    match: /@(163\.net|vip\.tom\.com)$/,
    name: 'Tom VIP邮箱',
    url: 'http://mail1.tom.com/?tab=1'
  },
];

```
