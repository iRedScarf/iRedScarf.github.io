---
layout: post
title: "自助注册美国AppleID完全教程"
tagline: 
date: 2018-04-10
author: A Red Scarf
comments: true
categories:
- Tech
tags:
image:
meta:
---

　　教你在无需美国银行账户或Paypal等支付方式的情况下注册一个美国区的AppleID。

　　美国区AppleID有啥用你会来看这篇教程就不用我再多说了。（注册其他地区的AppleID同理）

* * *

## 1、准备工作

　　准备一个没注册AppleID的可用的电子邮箱。

　　最好有电脑操作，方便些。（当然用移动设备也可以，其实原理都差不多）

　　为了严肃点（当然是为了给苹果的服务器识别到我们“确实”是美国的用户），我们还是挂上美国IP吧，用全局的。（移动端申请的话最好也挂上美国IP）

![代理挂全局模式](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_001.png)

> 温馨链接：[《利用AWS搭建私有Shadowsocks服务器实现科学上网完全教程》]({{ post.url | relative_url }}/tech/2018/04/01/Ladder.html)

* * *

## 2、开始吧（PC端）

### 　　1. 登录AppleID网站

　　AppleID官网：[https://appleid.apple.com/](https://appleid.apple.com/)

　　点击“Create Your Apple ID”

![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_002.png)

### 　　2. 填写信息

　　填假的没问题，但不能假得太离谱咯（谁知道会不会被BAN）

　　都用英文填，完了输入验证码然后点“Continue”

```
　　- 国家：United States
　　- 生日：格式是 月/日/年，为防止会不会有软件限制了年龄的，都填成成年的吧
　　- 邮箱：必须是可用的，后面要收验证码的
　　- 密码：8位数，至少一个大写英文、一个小写英文、一个阿拉伯数字，如果不合格就会红色框框
　　（截图时想了个当然说没关系，其实有关系的，会让你重填的）
　　- 密保问题：3个都得填，用英文
```

![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_003.png)
![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_004.png)

### 　　3. 邮箱验证

　　然后会弹出这个对话框，把你刚刚填的邮箱里收到的验证码填上去，然后“Continue”

![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_005.png)

### 　　4. 进入帐户

　　验证通过后会自动进入到帐户的页面了

![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_006.png)

### 　　5. 添加付款信息

　　把网页往下拉，找到“Payment & Shipping”项，点击“Add Payment Method...”

![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_007.png)

　　接着填写付款信息

　　“PAYMENT METHOD”这项选到“None”（有些方法注册美国AppleID是必需选择有效的付款方式而没有“None”的选项）

　　“BILLING ADDRESS”和“SHIPPING ADDRESS”可以是一样的，填美国的地址、邮编和电话，自己网上找一个，不要太假就好（例如填苹果公司自己的地址就有点怪异了）

　　我用的是转运公司的地址和电话，随便找个美国转运注册个帐号就有了，地址、邮编和电话都是匹配的，“确实”是美国用户。

![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_008.png)

　　填完点“Save”，PC端的操作就完成了。

* * *

## 3、没完，继续 ==> 打开移动端的 App Store

### 　　1. 点击右上角的人头

　　![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_009.png)

### 　　2. 退出登录已登录的帐户

　　![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_010.png)

### 　　3. 登录刚注册的美国帐户

　　![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_011.png)

### 　　4. 检查帐户信息

　　会弹出一个“此AppleID尚未在iTunes商店使用过”的提示框，点“检查”

　　![点“检查”](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_012.png)

### 　　5. 完成创建 Apple ID

#### 　　5.1 可能会弹出一个“需要AppleID”的提示框，不要点“设置”，点“以后”

　　![点“以后”](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_013.png)

#### 　　5.2 点亮“同意条款与条件”，点“下一页”

　　![同意条款与条件](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_014.png)

#### 　　5.3 把“称呼”选一下，点“下一页”

　　![需要选择“称呼”](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_015.png)

#### 　　5.4 这里我们在网页上已经填好了，直接点“下一页”

　　![付款方式可以是“None”哦！](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_016.png)

### 　　6. DONE!

　　![点“继续”](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_017.png)

### 　　7. 自动跳转进入美国商店

　　在从中国商店切换到美国商店时会有下面的提示，会自动把你设备上苹果自带的“Videos app”换成“TV app”，商店语言也会变成英文

　　![ ](https://raw.githubusercontent.com/iRedScarf/images/master/AppleID_US_018.png)

* * *

#### 　　*OK，去浪吧！*