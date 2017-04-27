# mark

1.在运行intellij idea的时候，提示Low disk space on a IntelliJ IDEA system directory partition。
2.解决办法是：找到idea的安装目录，找到文件idea.properties
3.在文件中，增加配置 -Didea.no.system.path.space.monitoring=true
4.源出处：https://youtrack.jetbrains.com/issue/IDEA-118718
