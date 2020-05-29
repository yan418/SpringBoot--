# SpringBoot--阿里云短信业务
阿里云短信业务实战 <br>
首先，我们注册阿里云账号，开启短信业务，充值1元即可。使用SpringBoot完成接口请求向手机发送验证码，把验证码保存到Redis中。

## 需要用到的技术

  1. 阿里云账号，开启短信业务服务 <br>
  2. SpringBoot基础 <br>
  3. 集成Redis，Redis基础 <br>

## 阿里云账号权限开通
``` bash
1 登录阿里云 ，有支付宝账号就能登录
2 点击控制台，点击头像，找到AccessKey管理
3 分部创建用户、用户组，授权后，得到账号和密钥
4 记住你的账号和密码，很重要，只有这个账号才能有权限操作阿里云里的业务功能
4 搜索框搜索短信服务，进行添加签名 和 模板管理
5 签名：就是短信发送的公司名或者业务 模板管理：短信内容，模板样式

# swiper的安装
cnpm install vue-awesome-swiper --save

# element 安装
cnpm i element-ui -S

# 配置完，启动项目
cnpm r
