`zFused Outsource` 外包插件安装与更新

## 安装需求
- 需要链接互联网
- 如果开翻墙软件可能会导致插件运行效率降低
- 如果限制上网行为，可以单独开通IP地址 `47.103.77.93`

## 插件信息
+ 插件名称：zFused_outsource
+ 插件完整地址 ：P:\zfused\pipeline  (本路径需开通读取和修改权限)
+ 插件完整路径：P:\zfused\pipeline\zfused_outsource

![](sources/image/install/install_path.jpg)

## 插件更新
__1. 从我们的github地址下载最新的pipeline代码 [`仓库地址`](https://github.com/zhoulh0322/zfused_outsource)__

![](sources/image/install/githubpath.jpg ':size=60%')

__2. 插件内部的更新按钮__

![](sources/image/install/mayaupdate.jpg)

__3. 插件内部的更新命令__
```python
from zwidgets.updatewidget import updatewidget
ui = updatewidget.UpdateWidget()
ui.show()
```

__4. 更新插件后，`reload` 重新加载插件__
- `zfused_outsource` > `init` > ` refresh and reload`

![](sources/image/install/refresh.png)

## DCC插件安装
__Maya 插件安装__
+ 将useSetup.py 文件 拷贝至 我的文档\maya\版本\scripts\目录下
+ P:\zfused\pipeline\zfused_outsource\scripts\maya\userSetup.py

__Houdini 插件安装__
+ 将123.py 文件拷贝至 我的文档 \houdini版本 \scripts\目录下
+ P:\zfused\pipeline\zfused_outsource\scripts\houdini\123.py

__Katana 插件安装__
+ 将 init.py 文件拷贝至 C:\Users\用户名\.katana\Startup\ 目录下
+ P:\zfused\pipeline\zfused_outsource\scripts\katana\init.py

## 公司登陆
插件需要设置公司名称，点击设置切换公司

![](sources/image/install/company_change.jpg)

插件初次启动，会提示输入公司名称，可填写公司简称，系统自动匹配

![](sources/image/install/company_name.jpg)

## 项目选择
插件设置公司后可切换至具体项目

![](sources/image/install/project_set.jpg)

## 项目文件夹权限检查
外包没有`zfused transfer`服务中转传输协议，所以需要所有项目文件夹`读取` `写入`权限

?> 如果报错的，需联系 `IT` 予以解决，不然`zfused`发布或者领取会失败！

- 菜单启动文件夹权限检查
`zfused` 提供权限检查插件 `zfused_outsource` > `init` > `project path permission`
- 代码启动文件夹去权限检查
    ```python
    from zfused_maya.tool.init import permission_widget
    window = permission_widget.PermissionWidget()
    window.show()
    ```

![](sources/image/install/project_path_permission.png)