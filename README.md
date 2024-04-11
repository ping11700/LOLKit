# 此项目涉及账号密码安全问题，故而没有开源. 不开源的原因:开源后账户安全的不可控性;

# 核心功能:
*	一键登录, 自动输入账号密码, 选择大区;
*	高速下载纯净lol, 100+M/s跑满带宽;
*	精简客户端删除无用文件, 缓存等, 删除内置wegame, 电视台, qt, 无用加速器等;
*	自动修复;(绕开wegame, 强制wegame弹窗, 安全中心图形码校验卡死, 无法自动键入等)
*	屏蔽主页广告, 提高客户端流畅性;
*	安全模式, 适用于网吧;
*	LOLKit和lolClient相互独立, 互不影响;
#
*	自动ban位;
*	自动秒选;
*	大乱斗秒选;
*	自动配置胜率最高的符文,装备;
*	自动接受对局;
*	自动重连游戏;
*	自动跳过结算;
*	根据游戏模式, 展示队友信息;(段位, 最近对局胜率等)
*	重置窗体;(修复DirectX导致客户端界面异化)
*	皮肤预览;(设置为桌面, 软件背景, 生涯背景)
*	强制退出对局;
*	战绩查询;(包含隐藏战绩)
*	召唤师查询;
*	设置展示段位, 在线状态, 个性签名;
#
* 额外功能: SMS接码
* 🐧:875492749
#
*	介绍: https://sway.office.com/PXfDJFguLtibyWsu?play
*	视频演示:【合集·one gift for all lol gamers-哔哩哔哩】https://www.bilibili.com/video/BV1Pe411u7YJ
#
![alt text](https://github.com/ping11700/LOLKit/blob/main/Gui2024-1-31.png)
![alt text](https://github.com/ping11700/LOLKit/blob/main/Download.png)
![alt text](https://github.com/ping11700/LOLKit/blob/main/summoner.png)
![alt text](https://github.com/ping11700/LOLKit/blob/main/record.png)
![alt text](https://github.com/ping11700/LOLKit/blob/main/func.png)
![alt text](https://github.com/ping11700/LOLKit/blob/main/ARAM.png)

# Release Note
## version2.3.0
 * 根据游戏模式, 展示队友信息; 
 * 新增功能设置召唤师段位,在线状态,个性签名;
 * 新增功能手动跳过结算页面;
 * UI优化;
 * 备注: 此版本之前, 服务器被墙, 无法自动更新, 需要手动下载.
## version2.2.0
* 优化自动化逻辑; 
* 新增功能删除log等无用文件;
* 新增功能召唤师搜索(可查隐藏战绩)等;
* 展示段位, 最近对局信息;
* UI优化;
## version2.1.1
* 修复自动配置符文bug; 
* 修复大乱斗循环选择英雄bug;
* 优化自动重连和强制退出对局冲突逻辑;
* 新增safe模式, 可用于网吧, 此模式禁止使用自动登录(保护账户安全);
* 新增清理客户端主页广告页功能;
 
## version2.1.0
* 皮肤预览; 
* 修复窗体异化;
* 自动重连游戏;
* 跳过结算页面;
* 自动配置符文;
* 排位秒禁英雄;
* 排位秒选英雄;
* 匹配秒选英雄;
* 大乱斗选英雄;
* 优化UI;
* 优化webSocket;

## version2.0.2
* 自动接收对局;
* 接码;

## version1.9.0
* 战绩查询;

## version1.8.0
* 重启高速下载服务,  自愿付费;
* LOLkit在线升级;
* 滚动记录本地Log, 保留一天;
* 弃用TraceWindow, 改用Toast;
  
## version1.7.0
* 新增LOLkit使用介绍web;
* 扫码登陆;
  
## version1.6.0
* 优化traceWindow;
* 添加自动修复功能(a. 卡qq安全中心, b. 无法自动键入);
* 优化下载逻辑;
* 优化登陆成功后CPU占用7% ->0%;

## version1.5.0
* 新增LOL下载安装功能;
* 新增TraceWindow;

## version1.4.0
* 深度清理LOL内部无用tx插件;
* 新增手动输入密码功能, 此功能开启本机不在记录用户密码;
  
## version1.3.0
* 感谢B站小伙伴"橘橘月"提出的优化建议. 启动时关闭音乐"(已优化);
* 感谢B站小伙伴"甘雨烟"提出的问题. 部分win7运行问题(已修复);
* 感谢B站小伙伴"ze7ZED"提出的优化建议. 添加多个账号管理"(已优化);
* 系统浏览器打开项目GitHub更新网址;
  
## version1.2.0
* 感谢B站小伙伴"人所具有的摩尔"提出的优化建议. 密码栏可视切换(已优化);
* 感谢B站小伙伴"98531949"提出"启动时提示更新wegame问题"(已修复);
* 感谢B站小伙伴"橘橘月"提出的优化建议. 启动时关闭音乐"(未优化);
* 添加自动检测游戏路径功能;
* 添加强制退出游戏对局功能, 无需等待倒计时;
* 新增托盘系统;
* 优化UI;

## version1.1.0
* 添加游戏的选区功能;
* 感谢B站小伙伴 "小卖部管理员" 提出的Bug, 无法删除wegame.(已修复);

## version1.0.0
* 绕开wegame, 一键登录;
* 瘦身lol, 删除lol中嵌入的wegame, cross(tx游戏直播等);
