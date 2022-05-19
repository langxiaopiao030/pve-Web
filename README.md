超融合虚拟化实训平台部署方式

一、	修改“index.html”文件中第81～84行配置。

二、	修改“deleteAll.html”文件中第10～13行配置。

三、	将修改好的“index.html”、“deleteAll.html”和“jquery.cookie.js”、“jquery-3.5.0.min.js”上传至PVE虚拟机“/usr/share/pve-docs/api-viewer”下。

四、	访问https://PVE的IP地址:8006/pve-docs/api-viewer/index.html?studentId=121&QuestId=100
地址中sutentId为用户ID，即虚拟机ID，QuestId为模版ID，可根据模版为用户创建虚拟机。
填入未创建的虚拟机ID和已有的模版ID可将模版克隆为虚拟机

五、	批量关闭并删除所有虚拟机：访问https://PVE的IP地址:8006/pve-docs/api-viewer/deleteAll.html?studentIdList=110,111,112,113,114
地址中studentIdList为需要被关闭并删除的虚拟机ID。

妙啊
