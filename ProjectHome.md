<font color='red'>本程序仅供自娱自乐，请勿用于正式场合！！！(Lemon does not have any Sandbox under both Linux and Windows!)</font>

//v1.2版本正在开发，大家有什么意见或需要的功能可以在Issues或右侧My blog中留言。

Windows用户请到Downloads里下载lemon\_v1.1\_release\_mingw.7z。

Ubuntu用户请用git clone源代码，如果git无法连接到Google服务器，请使用http协议（默认为https）。
或者直接在Downloads中下载source。
然后安装Qt编译环境：
```
sudo apt-get install qt4-dev-tools
```
进入源代码目录编译：<br>
<pre><code>qmake lemon.pro<br>
make<br>
</code></pre>

Fedora16下的安装注意事项（By litimetal）：<br>
1、安装 qt-devel<br>
2、不要输入qmake, 而是qmake-qt4<br>
<br>
Special Judge参数传送说明：<br>
<code>argv[1]</code>: 标准输入文件<br>
<code>argv[2]</code>: 选手输出文件<br>
<code>argv[3]</code>: 标准输出文件<br>
<code>argv[4]</code>: 本测试点满分<br>
<code>argv[5]</code>: 分数输出文件（必须创建），仅一行，包含一个非负整数，表示得分。<br>
<code>argv[6]</code>: 额外信息文件（可以不创建）<br>