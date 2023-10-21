# 阶段性工作管理器
目前本工具仅适配Matlab 2021a

## 1 介绍
本工具是一个管理阶段性工作的Matlab脚本，方便你使用Matlab记录、统计工作开展情况。

### 1.1 本工程支持如下功能
1 - 更新功能

（1）更新日报

（2）更新任务

（3）切换数据库

（4）更新人员信息

（5）更新项目信息

2 - 展示功能

（1）展示周报

（2）展示月报

（3）展示日报

（4）展示指定时间段的日报合集

（5）展示外部立项/非立项任务统计表

3 - 分析功能

（1）展示工作量分布情况

（2）以绩效协议形式展示全部工作目标（包含已完成、撤销的任务）

（3）以绩效协议形式展示个人工作目标（不包含已完成、撤销的任务）

（4）以甘特图数据源表格形式展示项目计划及进度

4 - 合成功能

（1）合成XMind形式的会议纪要

（2）合成周报/月报

（3）合成外部立项/非立项任务统计表

### 1.2 本工程引用了如下工程
（1）XMind文件接口工程 - [XMindInterface](https://github.com/IDS-zhangxr/XMind_interface_release)

（2）网盘管理器工程 - [NetworkDiskManager](https://github.com/IDS-zhangxr/Network_disk_manager_release)

## 2 使用方法
在Matlab中打开本工程，在Matlab命令行中运行如下指令之一，或者在快捷方式面板中点击同名的图标按钮，按照提示选择、输入信息，等待本工具完成处理，展示结果。
``` matlab
Script_update_staged_work
Script_display_staged_work
Script_analyze_staged_work
Script_synthesize_staged_work
```
