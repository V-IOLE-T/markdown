## Zotero使用

[知乎学习](https://zhuanlan.zhihu.com/p/674602898)
[zotero学习](https://sspai.com/post/56724#!)
[官方介绍](https://zotero-chinese.com/user-guide/take-notes.html)

### 插件 

#### [scholaread](https://www.scholaread.cn/list?ref=zhihu&utm_campaign=TR_VrKZGoFo&utm_content=&utm_medium=CPC&utm_source=CH_lzy6Abs7&utm_term=)

* 手机电脑文献库实时同步
* 逐段对照全文翻译
* 引用文献可以直接点开，引用文献加入文献列表
* 高亮标注，目标跳转，图标提取等

#### [Scihub plugin for Zotero——抓取英文文献](https://link.zhihu.com/?target=https%3A//github.com/ethanwillis/zotero-scihub/releases)

#### [Zotero style——标签分栏论文进度可视化管理](https://github.com/MuiseDestiny/zotero-style)

#### [green frog——解决影响因子不显示问题](https://github.com/redleafnew/zotero-updateifsE/releases/tag/0.16.02)

安装小绿蛙插件→编辑→首选项→绿青蛙→复制密钥→ok→选择论文→右键→从easyscholar更新期刊信息

#### [zotero-reference——一键抓取参考文献](https://github.com/MuiseDestiny/zotero-reference)

插件安装好后→编辑→首选项→参考文献（配置见后图）→打开一篇论文→点击右上角→点击参考文献→刷新→点击加好将文献加入阅读列表

* 在旁边显示参考文献栏
* 单击所需参考文献显示摘要，可以添加到zetero，并自动与正在阅读的文献关联

#### [Zotcard ——使用卡片笔记模板记录文献笔记](https://github.com/018/zotcard/releases)

#### [pdf translater(https://zhuanlan.zhihu.com/p/674602898)

#### [zotfile](https://zhuanlan.zhihu.com/p/674602898)

自动重命名，移动PDF（或其他文件）并将其附加到Zotero项目，将Zotero库中的PDF同步到（移动）PDF阅读器（例如iPad，Android平板电脑等）并从PDF文件中提取注释
[Zotero Better Bibtex(插件)](https://retorque.re/zotero-better-bibtex/)
[Zotero DOI Manager(插件)] (https://github.com/bwiernik/zotero-shortdoi)

### 如何导入文献？

* 网页识别
  安装**Zotero Connector**浏览器插件，用于Google scholar，中国知网，豆瓣，Wikipedia（维基百科），web of science，YouTube
* 抓取pdf元数据
  拖动pdf到某个分组中，右击文件，选择"Retrieve metadata for PDF"(Zoterp只能抓取英文文献，中文文献自行导入)
* 手动输入
* 通过标识符DOI，ISBN增加

### 文献和笔记管理

#### 集合和标签

可以建立文件夹，为每个文献添加若干个标签，设置颜色

#### 搜索

高级搜索（放大镜图标）

#### 排序和关联

#### 笔记

每一篇文献支持插入多个笔记，笔记还可与多篇文献进行关联，可以[安装插件](https://github.com/fei0810/markdownhere4zotero)来支持markdown语法

#### 生成引文和报告

##### 快速复制

在设置中可以设置复制时需要的引文格式，然后只需要拖拽即可

##### 多篇文献右键多种导出

当你同时选择多篇文献时，也可以通过鼠标右键选择你需要导出的形式。也可以选择直接复制然后一步粘贴到位。

##### 在 Microsoft Word 中使用插件

##### 生成报告

报告是简单的 HTML 页面，概述了所选项目的项目元数据，注释和附件。可以打印它们，也可以将它们发布到网上并通过电子邮件发送。
创建报告可以右键单击中心窗格中的项目或选项，然后选择「由所选条目生成报告…」，也可以右键单击左列中的集合，然后选择「从集合生成报告」
[第三方工具插件](https://github.com/retorquere/zotero-report-customizer/releases) 可以帮助你更好地过滤报告内容，例如对报告进行排序或者增删条目等。

### 备份和协作

#### 同步

Zotero 本身支持 300M 免费的存储空间。这对很多人都是不够的，如果你不想购买官方的存储空间可以使用 WebDAV 服务。这里就不做展开介绍了，以国内使用比较方便的「坚果云」为例，[如何在zotero中设置webdav连接到坚果云](https://help.jianguoyun.com/?p=3168)

#### 协作

如果你想和实验室或者几个好用共享协作一个文献库，那么就可以创建一个私有库，需要去官网创建，

### 小技巧

* 当选择了一个项目时，可以通过按住 Option(Ctrl) 键突出显示包含此项目的所有集合，也就是知道这篇文献所在的分组
* 若使用快速复制功能，在将项目拖放到文本文档时按住 Shift 键能实现插入引文而不是完整引用
* 可以单击详细信息中的 DOI 和 URL 字段标签直接打开链接