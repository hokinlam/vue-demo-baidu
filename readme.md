#功能介绍
1. 在输入框输入搜索词，和百度一样显示下拉菜单。
2. 按下键盘上下键，选择搜索词。
3. 按下enter键，打开相关搜索页。

#原理介绍
1. 使用了vue。
2. 先获取百度搜索的接口，使用jsonp，获取返回的数据，遍历到li上面。
3. 根据keycode的值判断用户按了什么按钮。

