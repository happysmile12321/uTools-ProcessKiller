# ProcessKiller V0.0.5

### 简介

之所以做这个插件一方面是为了熟悉`uTools`的插件开发，另一方面对标`alfred`,实现类似的功能

### 更新日志

**v0.0.5**

- 更新了对`macOS`的支持,`macOS`相比`window`多了显示`CPU`,`内存`百分比及`用户`的功能,以及默认按照内存占用率进行排序
- 增加插件更新检测的功能
- 修复了`windows`下可能导致无法显示进程列表的`bug`,强烈建议`windows`用户也进行升级
- `windows`下一些`UI`微调
- 优化重写了部分程序逻辑和代码

![Snipaste_2019-04-24_16-47-35.png](https://i.loli.net/2019/04/24/5cc022bc59bc7.png)

**v0.0.4**

- 进入插件后列出所有进程
- 通过方向键进行列表选择，`enter`关闭进程，`shift+enter`重启进程
- 更改插件描述
- 重新进行`upx`打包

**v0.0.3**

- 增加右键重启进程的功能

**v0.0.2**

- 对界面重新排版，和`uTools`统一风格，增加进程图标，同时根据进程条目调整下拉框长度
- 获取进程命令由tasklist更换为powershell的get-process，可以获取到进程的绝对地址和描述（含中文，相对直接显示进程名更加友好），通过搜索进程名称和描述皆可以搜索到相应进程

### 功能

- 根据输入框内容列出相应的进程
- 点击相应进程进行关闭
- 直接回车关闭列表中的第一个进程
- 暂不支持 macOS

### 预览

![0.0.2.gif](https://i.loli.net/2019/03/27/5c9ae3d193b1d.gif)



### 下载

[百度网盘](https://pan.baidu.com/s/1nfBnFLMdXisWATVYBKqONw) 提取码: `fmc6`

[项目地址](https://github.com/fofolee/uTools-ProcessKiller/)

[插件发布页](https://yuanliao.info/d/296)

### 安装方法

将`upx`文件拖入`uTools`输入框中安装即可

### 关键字

`kill` `关闭进程`

### ~~Todo~~ (Maydo)

- ~~UI改善~~
  - ~~增加进程图标~~
  - ~~列出进程详细信息~~
- ~~重启进程功能~~
- ~~进入插件后列出所有进程~~
- ~~方向键进行列表选择~~
- ~~按内存排序~~
- ~~添加对 macOS 的支持~~

### 鸣谢

感谢大佬[@lanyuanxiaoyao](https://yuanliao.info/u/1737)，为开荒阶段奉献了许多值得借鉴的资料