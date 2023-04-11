## Ts3AudioBotImportPlaylists

### 项目介绍

基于 TS3AudioBot 和 NeteaseCloudMusicApi 实现的，将网易云歌单导入 Ts3Bot 的脚本。
因为Ts3Bot并不提供除批量导入YouTube歌单以外的相关功能，需要手动添加，且寻找直链较为麻烦

### 依赖项目

机器人本体

[TS3AudioBot](https://github.com/Splamy/TS3AudioBot)

可以自建或用三方的

[NeteaseCloudMusicApi](https://github.com/Binaryify/NeteaseCloudMusicApi)

### 使用方法

运行环境：`JDK 17+`

运行命令：`java -jar ./Ts3AudioBotImportPlaylists-1.0-SNAPSHOT-jar-with-dependencies.jar`

自行构建或下载release的jar包，首次运行后退出，修改同目录下`config.json`内的两个api为你的地址，
请注意：两个都只需url部分 如`http://127.0.0.1:8080`，最后不要带`/`

### 使用截图

![1.png](https://cdn2.feczine.cn/2023/04/11/6434e37c85f30.png)

![2.png](https://cdn2.feczine.cn/2023/04/11/6434e37c88301.png)

### 版权声明
使用 GPLv3 协议开源
