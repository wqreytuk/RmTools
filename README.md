# RmTools
蓝队应急工具

### 工具列表
1. yara scanner
这个是应急用的给朋友定制的,他们说一个公司发现了一个病毒基本上其他的机器都有同样的文件只不过位置不一样要一个东西能全扫出来.功能列表:
```
1. 全盘文件扫描,寻找指定的hash、文件名
2. yara扫描,可自定义yara文件进行扫描查找
3. ntfs stream流扫描,检测文件是否携带了ntfs stream数据
4. 导出报告
```

2. door scanner
这个是应急用的给朋友定制的,主要用途扫描持久化后门,功能列表:
```
1. 扫描计划任务、注册表自启动、开始菜单自启动、服务的项目
2. 对这些项目对接云API进行hash检查(可以关闭),标注可疑项目
...其他功能在制作中
```
