# Light Year Admin Using Iframe v4 光年后台模板基于Bootstrap 4.4.1的iframe版本

#### 演示网址
[http://lyear.itshubao.com/iframe/v4](http://lyear.itshubao.com/iframe/v4)

[猛戳这里去Light Year Admin项目](https://gitee.com/yinqi/Light-Year-Admin-Template)

[猛戳这里去Light Year Admin Using Iframe项目](https://gitee.com/yinqi/Light-Year-Admin-Using-Iframe)

[猛戳这里去插件整合项目（含v3和v4两个版本示例）](https://gitee.com/yinqi/Light-Year-Example)

#### 介绍
该项目是光年后台管理模板(Light Year Admin Iframe)基于bootstrap 4.4.1版本。

这里就不弄非iframe版本的了，该项目会进行一段时间，基于bootstrap 4.4.1版本。
因4.*的版本，一些class的命名已经改变，并且布局由float改成了flex，所以项目不支持从3.7版本升级到4.4.1版本。

#### 3.*和4.*的一些区别
- 3中的pull-left和pull-right已改成float-left和float-right，hidden改为d-none
- 删除了原有的label类，统一成badge
- 原有的nav下面的li和a标签，新增了class，li上的nav-item，a上的nav-link
- 下拉选项中需要dropdown-item，分割线类名改为dropdown-divider，并且向下的那个图标不需要在新增span元素了
- 输入框组中的input-group-addon已改为input-group-prepend和input-group-append以及input-group-text搭配
- card在3中是没有的，4因为有了默认的一些样式，这里在4的上面做了些调整，并处理成之前差不多的样子
- 栅格布局由原来的float:left改成了flex布局的方式
- carousel幻灯片，原有的item改为carousel-item，left carousel-control和right carousel-control改成carousel-control-prev和carousel-control-next
- 分页中新增了page-item和page-link
- 4中原有响应式样式table-responsive不显示边框，这里调整为跟3版本一样的效果
- 4中新增了不少内容，像复选框、单选框和滑块都有自定义的样式，另外还有新增spinners和toasts等

#### 交流群
![输入图片说明](https://images.gitee.com/uploads/images/2021/0419/100848_c8cf9210_82992.png "光年后台模板交流群群聊二维码.png")

#### Class搜索小工具
[此网址可以方便找到v3和v4中自己想要的class](http://libs.itshubao.com/lyear-search-class/)

#### 特别感谢
- Bootstrap v4.4.1
- JQuery
- Chart.js
- perfect-scrollbar
- Bootstrap-Multitabs
- bootstrap-clockpicker
- bootstrap-colorpicker
- bootstrap-datepicker
- bootstrap-datetimepicker
- bootstrap-table
- jquery-confirm
- jquery-tagsinput
- jquery-treegrid
- moment.js
- bootstrap-notify
- chosen.jquery
- jquery.cookie
- lyear-loading
- perfect-scrollbar
- popper
- bootstrap.wizard
- fullcalendar
- bootstrap-maxlength
- bootstrap-select
- ...

#### 更新记录
2020.08.*
更改侧边栏导航绑定click事件的方式，调整样式，增加说明，调整图库，增加一些样式（并给出示例），tab新增双击刷新（初始化时候配置dbclickRefresh:true），

2020.07.*
更改遗漏的图标，修改loading插件在safari下的bug

2020.06.30
调整js

2020.06.19
调整tags插件

2020.06.01
修改页面bug，增加标注演示

2020.05.30
修改bug，增加js绑定子页面打开tab

2020.05.23
增加日程插件和表单箱单页面，调整表单向导html结构，新增时光轴

2020.05.20
增加两个插件页面，文档页面增加通用ajax请求方法

2020.05.19
修改bug & 增加演示页面

2020.05.17
增加文档页和添加文档页 & 增加对话框和标签页面

2020.05.15
新增加个插件演示页面&调整tab插件布局样式

2020.05.13
完成bootstrap的基础组件

#### 截图
![登录页面一](https://images.gitee.com/uploads/images/2020/0519/221358_55b9d666_82992.png "首页 - 光年(Light Year Admin V4)后台管理系统模板8.png")

![登录页面2](https://images.gitee.com/uploads/images/2020/0519/221535_3f2cd076_82992.png "登录页面 - 光年(Light Year Admin V4)后台管理系统模板7.png")

![首页](https://images.gitee.com/uploads/images/2020/0519/221618_b00cc789_82992.png "首页.png")

![下拉菜单](https://images.gitee.com/uploads/images/2020/0519/221640_c55f42a1_82992.png "下拉菜单.png")

![卡片](https://images.gitee.com/uploads/images/2020/0519/221652_e9edebc4_82992.png "卡片.png")

![按钮](https://images.gitee.com/uploads/images/2020/0519/221702_d2494de4_82992.png "按钮.png")

![警告框](https://images.gitee.com/uploads/images/2020/0519/221722_e57b00a2_82992.png "警告框.png")

![表格插件](https://images.gitee.com/uploads/images/2020/0519/221558_932a3722_82992.png "表格插件.png")
