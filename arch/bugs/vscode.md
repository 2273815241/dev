# vs code 相关问题
1. 无法输入中文
 - 解决方法：设置环境变量
    ```
    export GTK_IM_MODULE=fcitx5
    export QT_IM_MODULE=fcitx5
    export XMODIFIERS="@im=fcitx5"
    ```
    [参考连接：[关于ArchLinux系统中某些软件无法输入中文的问题](https://blog.csdn.net/huyi0911/article/details/128364186)]
