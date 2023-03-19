# 阶段性工作管理器
目前本工具仅适配Matlab 2021a

## 1 介绍
本工具是一个管理阶段性工作的Matlab脚本，方便你使用Matlab记录、统计工作开展情况。

### 1.1 本工程支持如下功能
1 - 更新功能

（1）更新日报

（2）更新任务

（3）切换数据库

（4）更新人员职位

2 - 展示功能

（1）展示周报

（2）展示月报

（3）展示日报

（4）展示指定时间段的日报合集

3 - 分析功能

（1）展示工作量分布情况

（2）以绩效协议形式展示全部工作目标

（3）以绩效协议形式展示个人工作目标

### 1.2 本工程引用了如下工程
（1）XMind文件接口工程 - [XMindInterface](https://github.com/IDS-zhangxr/XMind_interface_release)

（2）SQLite数据库接口工程 - [SQLiteInterface](https://github.com/IDS-zhangxr/SQLite_interface_release)

（3）网盘管理器工程 - [NetworkDiskManager](https://github.com/IDS-zhangxr/Network_disk_manager_release)

## 2 系统环境配置工作

### 2.1 部署XMindInterface工程
将[XMindInterface](https://github.com/IDS-zhangxr/XMind_interface_release)工程下载到本地，与本工程放在同一根目录之下。

### 2.2 部署SQLiteInterface工程
将[SQLiteInterface](https://github.com/IDS-zhangxr/SQLite_interface_release)工程下载到本地，与本工程放在同一根目录之下。

### 2.3 部署NetworkDiskManager工程
将[NetworkDiskManager](https://github.com/IDS-zhangxr/Network_disk_manager_release)工程下载到本地，与本工程放在同一根目录之下。

最终应该形成如下目录结构：
``` shell
root_path
    ├───Network_disk_manager_release
    ├───SQLite_interface_release
    ├───Staged_work_manager_release
    └───XMind_interface_release
```

## 3 使用方法
在Matlab中打开本工程，在Matlab命令行中运行如下指令之一，或者在快捷方式面板中点击同名的图标按钮，按照提示选择、输入信息，等待本工具完成处理，展示结果。
``` matlab
Script_update_staged_work
Script_display_staged_work
Script_analyze_staged_work
```
