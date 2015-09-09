

### polymer 和 sui 的对应关系


| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |


| paper-element | Description | demo | github | screnshot | sui |
| ------------- | ---- | ------ | --------- | --- |
| paper-behaviors | 所有paper-elements的公用behaviors | 无 | [github](https://github.com/PolymerElements/paper-behaviors) || 没有 |
|paper-badge|消息数量气泡|[demo](https://elements.polymer-project.org/elements/paper-badge?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-toast)|![](https://img.alicdn.com/tps/TB1cl13JpXXXXa4aXXXXXXXXXXX-501-357.png)|只在sui[列表](http://sui3.taobao.org/components/#list-group)里有|
|paper-button|按钮|[demo](https://elements.polymer-project.org/elements/paper-button?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-button)|![](https://img.alicdn.com/tps/TB1ODzkJpXXXXadXpXXXXXXXXXX-802-478.png)|[按钮](http://sui3.taobao.org/css/#buttons)|
|paper-card|卡片|[demo](https://elements.polymer-project.org/elements/paper-card?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-card)|![](https://img.alicdn.com/tps/TB1ZhLFJpXXXXazXXXXXXXXXXXX-515-471.png)|没有|
|paper-checkbox|复选框|[demo](https://elements.polymer-project.org/elements/paper-checkbox?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-checkbox)|![](https://img.alicdn.com/tps/TB1t7vpJpXXXXXLXFXXXXXXXXXX-870-419.png)|表单里没有做特别的样式化|
|paper-dialog|弹层|[demo](https://elements.polymer-project.org/elements/paper-dialog?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-dialog)|![](https://img.alicdn.com/tps/TB1c2HbJpXXXXaLaXXXXXXXXXXX-1351-824.png)|[modals](http://sui3.taobao.org/javascript/#modals)， 但是没有paper里的弹层样式和内容多|
|paper-dialog-behavior|为paper-dialog实现行为|[demo](https://elements.polymer-project.org/elements/paper-dialog-behavior?active=Polymer.PaperDialogBehavior)|[github](https://github.com/PolymerElements/paper-dialog-behavior)|||
|paper-dialog-scrollable|在paper-dialog中可以滚动的区域|[demo](https://elements.polymer-project.org/elements/paper-dialog-scrollable)|[github](https://github.com/PolymerElements/paper-dialog-scrollable)||在dialog中提供滚动区域|
|paper-drawer-panel|响应式的pannel|[demo](https://elements.polymer-project.org/elements/paper-drawer-panel)|[github](https://github.com/PolymerElements/paper-drawer-panel)|![](https://img.alicdn.com/tps/TB1PGzpJpXXXXbyXFXXXXXXXXXX-758-489.png)|没有|
|paper-icon-button|图标按钮|[demo](https://elements.polymer-project.org/elements/paper-icon-button?view=demo:demo/index.html)|[github](https://elements.polymer-project.org/elements/paper-icon-button?view=demo:demo/index.html)|![](https://img.alicdn.com/tps/TB1vv2pJpXXXXbpXFXXXXXXXXXX-718-405.png)|没有|
|paper-input|输入框|[demo](https://elements.polymer-project.org/elements/paper-input?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-input)|![](https://img.alicdn.com/tps/TB1nvnBJpXXXXXsXpXXXXXXXXXX-650-305.png)|sui的[form](http://sui3.taobao.org/css/#forms)里有较简短的样式，[表单验证](http://sui3.taobao.org/javascript/#validate)独立成js组件|
|paper-dropdown-menu|下拉菜单|[demo](https://elements.polymer-project.org/elements/paper-dropdown-menu?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-dropdown-menu)|![](https://img.alicdn.com/tps/TB1w5DKJpXXXXbnXXXXXXXXXXXX-610-513.png)|对应到sui里的[下拉菜单](http://sui3.taobao.org/javascript/#dropdowns)|
|paper-fab|floating action button|[demo](https://elements.polymer-project.org/elements/paper-fab?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-fab)|![](https://img.alicdn.com/tps/TB1j.bfJpXXXXcTaXXXXXXXXXXX-829-475.png)|都是自己实现的，应该也不怎么常用|
|paper-header-panel|A header and content wrapper for layout with headers|[demo](https://elements.polymer-project.org/elements/paper-header-panel?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-header-panel)|![](https://img.alicdn.com/tps/TB1sUDGJpXXXXX7XpXXXXXXXXXX-805-544.png)|业务中很少会用到|
|paper-item|material风格的列表|[deme](https://elements.polymer-project.org/elements/paper-item?view=demo:demo/index.html&active=paper-item)|[github](https://github.com/PolymerElements/paper-item)|![](https://img.alicdn.com/tps/TB1dHjMJpXXXXXjXXXXXXXXXXXX-795-606.png)|对应到sui的[列表组](http://sui3.taobao.org/components/#list-group)|
|paper-material|material风格的容器|[demo](https://elements.polymer-project.org/elements/paper-material)|[github](https://github.com/PolymerElements/paper-material)|||
|paper-menu|菜单|[demo](https://elements.polymer-project.org/elements/paper-menu?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-menu)|![](https://img.alicdn.com/tps/TB1rH_uJpXXXXXhXVXXXXXXXXXX-915-379.png)|sui里没有，但是好像可以用列表组直接代替|
|paper-menu-button|点击菜单按钮弹出菜单|[demo](https://elements.polymer-project.org/elements/paper-menu-button?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-menu-button)|![](https://img.alicdn.com/tps/TB1CFvyJpXXXXbrXFXXXXXXXXXX-448-401.png)|一般在手机或者响应式设计里见得多|
|paper-progress|进度条|[demo](https://elements.polymer-project.org/elements/paper-progress?view=demo:demo/index.html&active=paper-progress)|[github](https://github.com/PolymerElements/paper-progress)|![](https://img.alicdn.com/tps/TB1sNToJpXXXXbAXVXXXXXXXXXX-935-431.png)|sui里也有[进度条](http://sui3.taobao.org/components/#progress)但是貌似更粗,而且是不是动态的|
|paper-radio-button|单选框|[demo](https://elements.polymer-project.org/elements/paper-radio-button?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-radio-button)|![](https://img.alicdn.com/tps/TB1HyvrJpXXXXXUXVXXXXXXXXXX-828-406.png)|存在于sui from里|
|paper-radio-group|单选框组|[demo](https://elements.polymer-project.org/elements/paper-radio-group?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-radio-group)|![](https://img.alicdn.com/tps/TB14qLrJpXXXXaSXVXXXXXXXXXX-892-329.png)|当我有多个radio时，都是用name,属性来组成一组的|
|paper-ripple|material 风格的波纹动画效果|[demo](https://elements.polymer-project.org/elements/paper-ripple?view=demo:demo/index.html)|[github](https://elements.polymer-project.org/elements/paper-ripple?view=demo:demo/index.html)|![]()|点击到按钮上的点击效果|
|paper-scroll-header-panel|可以滚动的带头的pannel|[demo](https://elements.polymer-project.org/elements/paper-scroll-header-panel?view=demo:demo/index.html&active=paper-scroll-header-panel)|[github](https://github.com/PolymerElements/paper-scroll-header-panel)|![](https://img.alicdn.com/tps/TB1e1PqJpXXXXa4XVXXXXXXXXXX-1382-644.png)|滚动下去的头部自动变成浮动的|
|paper-silder|slider|[demo](https://elements.polymer-project.org/elements/paper-slider?view=demo:demo/index.html)|[github]()|![](https://img.alicdn.com/tps/TB136LCJpXXXXXcXFXXXXXXXXXX-1314-380.png)|比较常用但是sui没有，h5原生的比较丑|
|paper-spinner|菊花|[demo](https://elements.polymer-project.org/elements/paper-spinner?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-spinner)|![](https://img.alicdn.com/tps/TB11qvBJpXXXXasXFXXXXXXXXXX-574-378.png)|可以动，而且不抖|
|paper-style|全局的样式||[github](https://github.com/PolymerElements/paper-styles)||sui 的normalize.css 算是吧|
|paper-tab|tab|[demo](https://elements.polymer-project.org/elements/paper-tabs?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-tabs)|![](https://img.alicdn.com/tps/TB1r.zHJpXXXXauXpXXXXXXXXXX-886-278.png)|对应到sui的[标签页](http://sui3.taobao.org/components/#nav)|
|paper-toast|浮动提示|[demo](https://elements.polymer-project.org/elements/paper-toast?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-toast)|![](https://img.alicdn.com/tps/TB1c6vpJpXXXXbqXVXXXXXXXXXX-501-138.png)|sui的js组件[toast](http://sui3.taobao.org/javascript/#toast)|
|paper-toggle-button|开关button|[demo](https://elements.polymer-project.org/elements/paper-toggle-button?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-toggle-button)|![](https://img.alicdn.com/tps/TB1w0LjJpXXXXaUaXXXXXXXXXXX-831-409.png)|sui 好像也没有，但是满常用的|
|paper-toolbar|比较容易自定义的toolbar|[demo](https://elements.polymer-project.org/elements/paper-toolbar?view=demo:demo/index.html)|[github](https://github.com/PolymerElements/paper-toolbar)|![](https://img.alicdn.com/tps/TB16JYGJpXXXXbRXpXXXXXXXXXX-909-579.png)||
|paper-tooltip|tooltip|[demo](https://elements.polymer-project.org/elements/paper-tooltip)|[github](https://github.com/PolymerElements/paper-tooltip)|![](https://img.alicdn.com/tps/TB15VPDJpXXXXXOXFXXXXXXXXXX-539-389.png)|对应到sui的[tooltip](http://sui3.taobao.org/javascript/#tooltips)|

### iron-elemnet 可以加进行编写的
