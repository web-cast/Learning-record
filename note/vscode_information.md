# vscode信息

## 相关信息
如果能不开代理上github网站，那么不开代理也可以上传git
github代理有两种：http,https
## vscode快捷键
文件切换 ctrl+tab
同时选中已选中内容：ctrl+shift+L
光标快速移动 ctrl+左右
单行注释 ctrl+/
多行注释 Alt+shift+A
## Markdowm语法
1、超链接 [超链接名称](链接地址)
2、分割线 ---
3、加粗 **重点** (ctrl + b)
4、斜体 *文字* (ctrl+i)
5、高亮 ==高亮==
6、引用 >我说的
7、代码 ```  代码  ```（当然可以表示关键字了）
8、行内代码    ` 代码 `

## Github代理设置
git config --global https.proxy http://127.0.0.1:1080

git config --global https.proxy https://127.0.0.1:1080

git config --global --unset http.proxy

git config --global --unset https.proxy


npm config delete proxy

只对github.com
git config --global http.https://github.com.proxy socks5://127.0.0.1:1080
git config --global --unset http.https://github.com.proxy

查看已有配置：git config --global -l


