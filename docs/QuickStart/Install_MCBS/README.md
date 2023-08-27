# 下载 MCBS

我们将 MCBS 本体的下载托管在蓝奏云上。

https://bugcraft.lanzoum.com/ifKjY16eoa1c

点击上方的链接以下载 MCBS 本体。在下载完成后，请解压 `MCBS.zip` 并将获得的 MCBS 文件夹置入之前的 Minecraft 服务器文件夹中。

随后创建一份这样的批处理文件：

> @echo off && cd MCBS && start MCBS.ConsoleTerminal.exe

保存起来。双击启动它。

默认的情况下，MCBS 应该被放在服务器文件夹下面（这是可以配置的），且它会自动读取 Minecraft 服务器的配置。

随后它将自动根据服务器的配置来以特定的参数启动它自己。
