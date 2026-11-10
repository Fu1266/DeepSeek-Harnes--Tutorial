###新手下载教程

####第一步：安装 Node.js（运行必备）

DSH 依赖 Node.js 环境，必须安装 LTS 长期稳定版

1.官网地址：Node.js — Run JavaScript Everywhere

2.找到页面上 LTS 版本，Windows 下载 .msi，Mac 下载 .pkg
双击安装包，一路下一步，一定要勾选 Add to PATH（添加到系统环境变量），不勾选终端识别不到 node 命令！

3.打开终端

#####【Windows 系统】打开终端的方式
方式 1：快捷键 Win + X，弹出菜单选择 Windows PowerShell / 终端 (Windows Terminal)

方式 2：左下角搜索框，直接输入 cmd 打开命令提示符 ；输入 powershell 打开 PowerShell

方式 3：文件地址栏，清空地址，输入 cmd 回车，直接在当前文件夹打开终端

#####Mac 系统

方式 1：启动台 → 其他 → 终端（Terminal）

方式 2：快捷键 Command + 空格 调出聚焦搜索，输入 Terminal 回车打开

####第二步：获取 DeepSeek API Key

1.打开 DeepSeek 开放平台：DeepSeek

2.登录你的账号，左侧找到【API Keys】

3.点击【创建新密钥】，备注随便写，创建后立刻复制密钥保存好

####第三步：终端命令启动 DSH WebUI

已经打开终端，打开 DeepSeek Harness 官网找到一键使用，复制一行命令：

回车执行。

1.第一次运行会自动下载 DSH 包和依赖，耐心等待；出现 Proceed? (y)，输入 y 回车确认
启动成功后终端会打印本地访问链接，默认：http://127.0.0.1:3080

2.复制这个链接，Chrome / Edge 浏览器打开

####第四步：WebUI 填入 API Key，开始使用

1.在浏览器打开 http://127.0.0.1:3080，进入 DeepSeek Harness 界面

2.在设置页找到 API Key 输入框，粘贴刚才复制好的 DeepSeek Key

3.选择模型（DeepSeek-V3 / DeepSeek-Coder 等），保存配置

4.配置完成，就可以体验插件、Agent、Creator Mode 等全部功能了。

###新手使用教程

1.页面上方点击【选择工作区】→【添加工作区】

2.选一个你提前建好的文件夹（比如新建 DSH_Workspace，放代码、文档）
选中文件夹，工作区加载完成，输入框解锁，就可以对话了

####新手常用功能介绍

1.插件管理：设置 → 插件，可以安装社区插件，扩展能力（网页搜索、PPT 生成、数据分析等）
创造模式（Creator Mode）：可以直接用对话，让 AI 帮你编写新插件，自定义 Agent 能力

2.轨迹 Trajectory：每一轮任务的完整执行日志，看 AI 调用了哪些工具、读取了哪些文件，排查报错非常好用

3.新建会话：左上角新建会话，不同任务分开，避免上下文混乱

4.切换深色 / 浅色模式：右上角设置里切换
