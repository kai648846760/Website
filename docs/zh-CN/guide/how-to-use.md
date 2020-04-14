# 快速入门
`自冻FreezeYou`的功能非常之多，这里对一部分内容做些简短的介绍，方便快速入门。

## 授予权限
`自冻FreezeYou`中的一些功能，需要一些特殊权限，就比如`冻结与解冻`就需要特殊授权才能正常使用（若不使用相关功能，可不授予权限），目前，如要使用`冻结与解冻`功能，需要保证以下至少一个权限已授予`自冻FreezeYou`，并在`更多设置`-`冻结与解冻` - `选择冻结解冻模式`中选中相应的模式：
* Device Policy Manager (DPM) (常称为免ROOT) → 如何[启用](./enable-mroot.html)
* Root

## 冻结与解冻 <Badge text="格外谨慎" type="warning"/>
启动`自冻FreezeYou`，待主界面列表载入完成后，点击相应的应用，选择`冻结/解冻/启动`即可进行冻结与解冻操作。

## 分类查看 <Badge text="1.13+" type="tip"/>
默认情况下，启动`自冻FreezeYou`后首页会直接展示全部的应用，这时，如果想要寻找一些应用，有时会比较麻烦，那么，可以点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，点击`查看模式(分类查看)`，即可根据需要分类查看。

## 快速搜索 <Badge text="2.13+" type="tip"/>
启动`自冻FreezeYou`后，在显示的主界面中，点击顶端附近的`搜索`，即可进行快速搜索。  
如，输入`A`即会立即筛选并列出该分类中所有名称中包含`A`或`a`的应用（不区分大小写）。

## 计划任务 <Badge text="6.0+" type="tip"/>
计划任务的功能比较多，也较为复杂，这里我们单独进行 → [介绍](./schedules.html)。

## 更换界面风格 <Badge text="4.0+" type="tip"/>
启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`更多设置`，选择`常规`，点击`界面风格`即可修改。

## 备份与还原 <Badge text="8.8+" type="tip"/>
启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`更多设置`，再选择`备份与还原`，点击`导出`即可将当前的设置、计划任务等数据导出，点击`导入`，会读入下方输入框中的数据，整理后供选择需要导入的数据项。

## 通知栏瓷块
通过通知栏瓷块，可点击瓷块快速执行操作。下拉通知栏，点击`编辑`，将相应的瓷块设为显示，然后完成编辑后即可使用（需要 Android 系统支持）。  
__可用瓷块：__  
* 一键冻结
* 一键解冻
* 一键锁屏

## 一键冻结
`一键冻结`会对每一个存在于`一键冻结列表`中的应用执行`冻结`操作，使用前，需要先将需要被执行的应用添加到`一键冻结列表`中（点击主界面列表中的相应应用，选择`加入/移出`，即可添加）。  
**使用途径：**  
* 启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`立即执行`，最后选择`一键冻结`即可。
* 启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`快捷方式`，再选择`一键冻结`，即可在桌面上通过快捷方式进行`一键冻结`。
* 唤出桌面的`添加小部件`或是`添加微件`或是`添加小工具`菜单，选择`自冻FreezeYou`，再选择`一键冻结`，即可在桌面上通过快捷方式进行`一键冻结`。

## 一键解冻
`一键解冻`会对每一个存在于`一键解冻列表`中的应用执行`解冻`操作，使用前，需要先将需要被执行的应用添加到`一键解冻列表`中（点击主界面列表中的相应应用，选择`加入/移出`，即可添加）。  
__使用途径：__  
* 启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`立即执行`，最后选择`一键解冻`即可。
* 启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`快捷方式`，再选择`一键解冻`，即可在桌面上通过快捷方式进行`一键解冻`。
* 唤出桌面的`添加小部件`或是`添加微件`或是`添加小工具`菜单，选择`自冻FreezeYou`，再选择`一键解冻`，即可在桌面上通过快捷方式进行`一键解冻`。

## 离开冻结
_建议使用`计划任务`替代_  
启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`更多设置`，选择`自动化`，再勾选`离开冻结`即可，离开在`离开冻结列表`（点击主界面列表中的相应应用，选择`加入/移出`，即可添加）里的相应应用时对应的应用会被冻结。

## 锁屏后一键冻结
_建议使用`计划任务`替代_  
启动`自冻FreezeYou`，点击右上角的`⋮`或是右下角的`+`或是设备上的`≡`，唤出菜单，选择`更多设置`，选择`自动化`，再勾选`锁屏后一键冻结`即可，锁屏后会执行`一键冻结`。

## 使用中遇到问题
可以访问 [疑难解答](../faq/) 尝试寻找解决方案。
