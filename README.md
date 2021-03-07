# chrome-repeat
chrome扩展，减少重复操作的小玩意
```
快捷键：
alt+T     开始记录
alt+R     开始执行某条记录（默认取最新一条，可通过list修改）
alt+S     停止记录并保存或停止执行
alt+A     打开记录列表，可通过点击记录详情修改单个行为的时间间隔等属性
alt+左键  记录时开启index自增（常用于循环执行时，根据特征自增操作行为，可通过list修改）
ctrl+左键 记录时开启忽略文本（常用语执行时，操作行为忽略文本来匹配，可通过list修改）
ctl+alt+R 循环执行

说明：
暂时可以处理一般的重复性点击行为，记录会存在localStorage中，清除缓存会造成记录丢失
并非所有网页都生效，有时会因为页面内的逻辑干扰造成无法使用
