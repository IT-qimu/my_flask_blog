# Pycharm中将py文件转化为exe文件- -安装pyinstaller
- -打开：View-Tool Windows-Terminal
- 输入：pip install pyinstaller


- 生成exe文件
- Terminal中输入：`“pyinstaller -F -w *.py” `就可以制作出exe。
- 注：星号用相应的文件名进行替换即可。
- 　　生成的文件放在同目录dist下。
- 　　-F（注意大写）是所有库文件打包成一个exe；
- 　　-w是不出黑色控制台窗口。2020/2/16