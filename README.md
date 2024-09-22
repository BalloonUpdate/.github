## 各个系列的说明

更新助手系列共发布了4个软件作品，下面是按从旧到新的顺序排列

### 1.初代更新助手（ClientUpdater和FileSA）

发布于2016年，服务端基于Bukkit插件制作，有专门的规则编辑器，使用私有更新协议，后从ClientUpdater改名为FileSA

归档链接：[食用方法](https://github.com/BalloonUpdate/updater/blob/master/%E7%89%88%E6%9C%AC%E5%8F%91%E5%B8%83%E5%BD%92%E6%A1%A3/2020%E5%B9%B41%E6%9C%8828%E6%97%A5%E6%9B%B4%E6%96%B0/updater%E8%AF%A6%E7%BB%86%E7%9A%84%E9%A3%9F%E7%94%A8%E6%96%B9%E6%B3%951.2.2.docx)、[全部文件](https://github.com/BalloonUpdate/updater/tree/master/%E7%89%88%E6%9C%AC%E5%8F%91%E5%B8%83%E5%BD%92%E6%A1%A3)（已过时不推荐使用）

### 2.PythonUpdate

发布于2020年，改为使用Python加qt/webview的方式制作界面，开始支持http协议和对象存储，后因误报率高停止维护

归档链接：[教程文档](https://github.com/BalloonUpdate/Docs/tree/v2.8.4)、[PHP服务端](https://github.com/BalloonUpdate/PhpServer/releases/download/archive/php.server-2.8.zip)、[客户端](https://github.com/BalloonUpdate/Launcher/releases)、[热更新包](https://github.com/BalloonUpdate/Hotupdate/releases)、[小工具](https://github.com/BalloonUpdate/Tool/releases)（已过时不推荐使用）

### 3.JarClient/ExeClient

发布于2021年，支持Jar和Electron双版本客户端和支持正则和glob编写更新规则，同时还有一大堆周边配套工具，是我维护起来的最累的版本

归档链接：[教程文档 v3.x](https://github.com/BalloonUpdate/Docs/tree/v3.2)、[教程文档 v4.x(建议看离线版)](https://github.com/BalloonUpdate/Docs/tree/main)、[离线版教程文档 v4.x(推荐)](https://github.com/BalloonUpdate/Docs/releases)、[PHP服务端](https://github.com/BalloonUpdate/PhpServer/releases/download/archive/php.server-4.2.zip)、[单文件服务端](https://github.com/BalloonUpdate/LittleServer/releases)、[服务端单文件图形化增强](https://github.com/BalloonUpdate/BalloonServer/releases)、[静态服务端整合包](https://github.com/BalloonUpdate/StaticServerForPages/releases)、[规则编辑器](https://github.com/BalloonUpdate/RuleEditorServer/releases)、[Exe客户端](https://github.com/BalloonUpdate/ExeClient/releases)、[Forge模组版(加载器)](https://github.com/BalloonUpdate/ModClient/releases)、[Jar客户端](https://github.com/BalloonUpdate/JarClient/releases)（已过时不推荐使用）

### 4.McPatch v1

发布于2022年，采用差异式更新，所以无需编写更新规则，这降低了使用门槛，也方便做静态分发，是综合体验最好的版本

归档链接：[教程文档](https://balloonupdate.github.io/McPatchDocs/docs/v1-old/start)、[动态加载器](https://github.com/BalloonUpdate/DynamicLoader/releases)、[MiniHttpServer服务端](https://github.com/BalloonUpdate/MiniHttpServer/releases)、[管理端](https://github.com/BalloonUpdate/McPatchManage/releases)、[客户端](https://github.com/BalloonUpdate/McPatchClient/releases)

### 5.McPatch v2

发布于2024年，是对v1版本的重写，修复了网络限速和窗口无响应问题，同时大幅提升性能和简化使用流程，使用难度最低

链接：[教程文档](https://balloonupdate.github.io/McPatchDocs/docs/v2)、[加载器](https://github.com/BalloonUpdate/McPatch2Loader/releases)、[客户端&管理端](https://github.com/BalloonUpdate/McPatch2/releases)
