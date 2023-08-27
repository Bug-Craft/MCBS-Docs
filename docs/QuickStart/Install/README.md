# Minecraft 服务器的安装

在使用 MCBS 之前，你应该已有或者准备安装一台 Minecraft Java Edition 1.20.1 的服务器。这是至关重要的。我们推荐使用 Fabric 服务器内核，因为这样便可以安装专用的加速模组，可以让屏幕的显示和表现更加流畅。

如果你目前已有了一台 1.20.1 服务器（不论其是否为 Fabric 服务器），便可以跳过这篇文章了。如果你目前没有一台 Fabric 或者其它类型的 Minecraft 服务器，请继续阅读并安装一个。

## 下载服务器核心

下载服务器核心是至关重要的一步。

1. 原版服务器核心

https://piston-data.mojang.com/v1/objects/84194a2f286ef7c14ed7ce0090dba59902951553/server.jar

点击上面的链接即可完成这个步骤。

2. Paper 服务器核心

https://api.papermc.io/v2/projects/paper/versions/1.20.1/builds/163/downloads/paper-1.20.1-163.jar

点击上面的链接即可完成这个步骤。

3. Fabric 服务器核心

https://meta.fabricmc.net/v2/versions/loader/1.20.1/0.14.22/0.11.2/server/jar

点击上面的链接即可完成这个步骤。

## 启动服务器

> java -Xmx1024M -Xms1024M -jar server.jar nogui

使用上面的命令即可启动服务器。`server.jar` 应该被修改为实际的服务器核心文件名称。

请等待服务器结束运行后打开 `eula.txt` 并将 `eula=` 后方的 `false` 改成 `true`，以代表你同意了《Minecraft EULA》。

完整的简体中文版本《Minecraft EULA》可以在[这里](https://www.minecraft.net/zh-hans/eula)找到。

!> 注意：如果你不认可或者不同意《Minecraft EULA》中的所有或者部分内容，请不要继续操作并删除服务器核心。

## 完成

太好啦！至此你已完成 Minecraft 服务器的安装。
