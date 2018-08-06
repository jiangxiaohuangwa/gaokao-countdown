# 高考倒计时

## 功能

* 窗口可缩放自适应
* 可更换背景图片
* 背景遮罩从背景图片取色（使用[node-vibrant](https://github.com/akfish/node-vibrant/)）
* 支持macOS全屏幕显示
* 支持窗口无边框显示

## 构建
````
yarn
yarn dist
````

二进制文件未来可能会随tag发布。

## 使用指南

如需更换背景图片，将图文件拖拽进界面内即可。

在界面内任意区域右键点击打开上下文菜单。

如果需要还原默认图片，选择“还原背景”。

如果需要展示无标题栏的窗口，选择“无边框”。

窗口可以任意缩放，当尺寸过小时，会自动缩放内容，保证展示正常。