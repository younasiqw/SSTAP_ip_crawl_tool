# SSTAP_ip_crawl_tool
一个自动获取游戏远程ip，并自动写成SSTAP规则文件的脚本。

此脚本由python3编写，版本为3.7，其他版本未验证。

依赖的第三方库为psutil。

使用方法：

启动程序后输入需要抓取IP的程序名，然后根据提示输入游戏英文名、中文名随即进入抓取状态。

进入抓取状态后开启SSTAP全局进入游戏即可自动抓取ip并填写入规则文件。

获取到ip后按下Ctrl+C即可推出程序。

规则文件在程序当前目录中。
