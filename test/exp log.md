# experiment log

## experiment 1：基于设计组件生成

- 规范：[arco.design](https://arco.design/)
- 设计组件：figma components -> pencil components （组件化快捷键：ctrl + alt + k）

### experiment 1.1 D2C(HTML)生成
直接指令，大模型默认会用HTML生成
- 提示词: `Design a 云服务监控看板控制台页面 using components in@arcoui/components ，refer to styule @design style.pen 采用“顶部导航栏+左侧侧边栏+中间主内容区+底部状态栏”自适应布局，包含横向联动页签、三类圆角卡片（总览/指标详情/告警）、带排序筛选分页的标准表格、线性/环形进度条及四类差异化tag标签，遵循指定样式规格与交互逻辑，适配运维场景，实现监控指标直观展示、异常快速定位，支持后续扩展。`

![D2C HTML](image.png)

- 提示词：`@arcoui/components  @design style.pen 保持风格和字体符合规范 ，使用arcoui组件，继续补充Detailed Metrics、Log Analysis、Topology页面的结果 @cloud_monitor_dashboard.html`
- 提示词：`继续，基于场景模拟生成Detailed Metrics、Log Analysis、Topology页签和侧边导航菜单内的内容，组件仍然得从这里选择 @arcoui/components `




### experiment 1.2 D2C(Pencil)生成
要求模型通过Pencil绘制
- 提示词: `Design a 云服务监控看板控制台页面 in Pencil (给到.pen文件) using components in@arcoui/components ，refer to styule @design style.pen 采用“顶部导航栏+左侧侧边栏+中间主内容区+底部状态栏”自适应布局，包含横向联动页签、三类圆角卡片（总览/指标详情/告警）、带排序筛选分页的标准表格、线性/环形进度条及四类差异化tag标签，遵循指定样式规格与交互逻辑，适配运维场景，实现监控指标直观展示、异常快速定位，支持后续扩展。`

### experiment 1.2 D2C(React)生成

## experiment 2

### experiment 2.1

### experiment 2.2