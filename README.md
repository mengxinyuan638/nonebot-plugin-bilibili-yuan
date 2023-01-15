<p align="center">
  <a href="https://v2.nonebot.dev/"><img src="https://zsy.juncikeji.xyz/i/img/mxy.png" width="150" height="150" alt="API管理系统"></a>
</p>
<div align="center">
    <h1 align="center">✨哔哩哔哩登录</h1>
</div>
<p align="center">
<!-- 插件名称 -->
<img src="https://img.shields.io/badge/插件名称-哔哩哔哩登录-blue" alt="python">
<!-- 插件名称 -->
<img src="https://img.shields.io/badge/Python-3.8+-blue" alt="python">
<a style="margin-inline:5px" target="_blank" href="http://blog.juncikeji.xyz/">
	<img src="https://img.shields.io/badge/Blog-个人博客-FDE6E0?style=flat&logo=Blogger" title="萌新源的小窝">
</a>
<a style="margin-inline:5px" target="_blank" href="https://github.com/mengxinyuan638/mxy-api-system">
	<img src="https://img.shields.io/badge/github-萌新源API管理系统-FDE6E0?style=flat&logo=github" title="萌新源API管理系统">
</a>
<a style="margin-inline:5px" target="_blank" href="https://gitee.com/meng-xinyuan-mxy/mxy-api">
	<img src="https://img.shields.io/badge/gitee-萌新源API管理系统-FDE6E0?style=flat&logo=gitee" title="萌新源API管理系统">
</a>
<!-- 萌新源API -->
<a style="margin-inline:5px" target="_blank" href="https://api.juncikeji.xyz/">
	<img src="https://img.shields.io/badge/API-萌新源-blue?style=flat&logo=PHP" title="萌新源API">
</a>
<!-- CSDN博客 -->
<a style="margin-inline:5px" target="_blank" href="https://blog.csdn.net/m0_66648798">
	<img src="https://img.shields.io/badge/CSDN-博客-c32136?style=flat&logo=C" title="CSDN博客主页">
</a>
<!-- QQ群 -->
<a style="margin-inline:5px" target="_blank" href="https://jq.qq.com/?_wv=1027&k=5Ot4AUXh">
	<img src="https://img.shields.io/badge/QQ群-934541995-0cedbe?style=flat&logo=Tencent QQ" title="QQ">
</a>
<img src="https://img.shields.io/badge/license-MIT-blue" alt="MIT">
</p>



# 依赖

本插件依赖httpx库以及nonebot2,qrcode,pillow



# 安装

```bash
pip install nonebot-plugin-bilibili-yuan
```



# 配置

在`bot.py`中添加
```python
nonebot.load_plugin("nonebot_plugin_bilibili_yuan")
```

## 特别注意！

由于pip无法发行大资源包，所以请将项目根目录下的bilibili_login文件夹移动到各位机器人项目的根目录，这是本插件所需要的外部资源，务必执行这一操作

# 使用教程

## 命令1：哔哩菜单

## 返回：菜单列表

![](https://zsy.juncikeji.xyz/i/img/bili_menu.png)

## 命令2：申请哔哩登录

## 返回：

![](https://zsy.juncikeji.xyz/i/img/bili_login_qrcode.png)



## 扫描成功and登录成功提示

![](https://zsy.juncikeji.xyz/i/img/bili_check.png)

## 二维码失效提示

![](https://zsy.juncikeji.xyz/i/img/bili_no.png)

## 命令3：哔哩个人信息

返回：

![](https://zsy.juncikeji.xyz/i/img/bili_data_person.png)



# 注意

本插件功能并不完善，仅作为学习参考作用，大佬们可以基于本插件升级修改，谢谢