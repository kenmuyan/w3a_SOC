

w3a SOC
==========

	Web日志审计与网络监控集合一身的平台


最新log
==========

	1、诸位发现问题请直接提交issue，我会看,在空余时间会解决问题。
	2、关于开发、或者使用的问题，请翻看之前的issue，这个平台目前大部分针对有一定开发能力的人推广使用的。
	3、马上进行改版，老旧的问题会先放放，之前的一些bug在新版本将fix.


功能介绍
==========================

    --1)Web日志审计监控
       支持的日志类型有：
        -- (1)APACHE
	     -- (2)Nginx

    --2)图形报表
			出色的报表数据提高用户感知，从曲线图以及展现的数据中能够体现出年、月、日的数据量。
		根据个人需求，还可自定义操作日志数据。

	 --3)网络监控
			基于Web是否能够请求成功，是否可到达。
		基于网络设备是否能ping通，是否可以到达。

	 --4)Web监控规则优势
			添加触发量统计，并能通过触发量改良规则。
		利用专属的REGEX工具能够快速编写正则规则，不需要受到各种约束。
		从本质上与别的SOC无区别，但是使用起来比其它的方便。
		且该平台全部中文，可进行二次开发。

	 --5)采用轻量级框架
			后端使用的是PHP进行开发，使用了CI框架提高开发效率。
		目前CI框架比较轻量，而且MVC的模式比较简洁。使用该框架非常方便后续添加新的模块等等。


平台截图
===========================

新版本程序主界面:

<img style="max-width:100%;" title="Run example" alt="Run example" src="https://raw.githubusercontent.com/smarttang/w3a_SOC/master/newpic/EC31ED5A-D3FE-4581-A222-715D4C5A6239.png">

规则页面:

<img style="max-width:100%;" title="Run example" alt="Run example" src="https://raw.github.com/smarttang/w3a_System/master/image-folter/2001.png">

代码编写原则
===========================
	-- 1)每个程序块开头必须写明该模块的意义。
	-- 2)发现BUG模块统一注释掉（并在前面写明发现的情况，方便调整）


已知的BUG
==========================
	-- 1)首页当天数据有BUG，语句可能有错误。
	-- 2)网络监控模块报告数据还在构思，需要时间(欢迎提建议)
	-- 3)普通用户登录接口没有开发完成
	-- 4)预警模块和消息管理模块还没开始写。。
	-- 5)日志监控报告中的攻击行为分析模块，需要一些时间完善，由于涉及到一个亮点问题，后续会改一段时间。


