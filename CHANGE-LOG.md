Vx.x.x(TPL)
-   Breaking Changes
-   Feature
-   Bug Fixes
-   Performance Improvements
-   Style changes
-   Dependencies Changes

V1.0.1
### Bug Fixes
- 修复调整位置时滚动位置错位
### Feature
- 添加footer可固定导表头下方

---

V1.0.2
### Bug Fixes
- 修复搜索过滤后无法选中复制粘贴
- 修复多选滚动后点击表头选中会错选问题

---

V1.0.3
### Bug Fixes
- 修复边框溢出及滚动条偏移问题
---

V1.0.4
### Bug Fixes
- 添加合并单元格数据关联及内置合并单元格工具类
- 拓展editorType可为none
- 拓展设置选择器之前的回调
- 拓展设置选中和填充之前的回调
---

V1.0.5
### Bug Fixes
- 修复移动端滚动条无法移动
- 修复滚动条iframe场景下抬起事件不触发导致的bug
- 修复选择器添加背景色样式不生效
- 修复editorType为none时选择器不会触发选中
- 修复配置svg不生效
- 文档更新
---

V1.0.6
### Bug Fixes
- 修复loadData后立刻scrollto性能问题
- 修复loadData后立刻scrollto没有效果
- 添加编辑器批量设置值方法
- 修复容器宽高发生变化，表格没有触发更新宽高
---

V1.0.7
### Bug Fixes
- 废弃
---

V1.0.8
### Bug Fixes
- 废弃
---

V1.0.9
### Bug Fixes
- 更改enter变成下一个，而不会是进入编辑状态
- 剔除isTrsut及文档
- 修复点击容器外选中不失去焦点
- 修复修复loadData后立刻scrollto性能问题
- 修复V1.0.8版本
---

V1.1.0
### Bug Fixes
- fix:调整按下esc键取消编辑
- fix:修复插槽情况下点击编辑需要点击两次
- fix:添加shift+enter向上移动并提交操作
- fix:更改enter向下移动并提交操作，而不是进入编辑
---

V1.1.1
### Bug Fixes
- fix:调整isTarget逻辑
- fix:修复文本编辑器点击外层不会清除选中
- feat:添加部分校验方法
- feat:change事件添加旧值
- feat:添加主动清除编辑器和选择器
---

V1.1.2
### Bug Fixes
- fix:修复文本编辑器点击外层,没有选中一直回调
---

V1.1.3
### Bug Fixes
- fix:修复滚动条hover失效问题
- fix:修复Tooltip移到内容也会hide
- docs:更新文档
- 解决iframe下点击容器外不失焦
- fix:移动表头宽度和移动行高到滚动条的边界处理
- fix:单选ENABLE_SELECTOR_SINGLE下shift快捷选中也能多选
---

V1.1.4
### Bug Fixes
- fix:修复右fixed阴影1px问题
- fix:更改选择器和填充器的绘画逻辑修复线条存在点问题
- feat:添加selection跨页选
- feat:添加数字类型type

---


V1.1.5
### Bug Fixes
- fix:添加selection缓存提升渲染速度
- fix:修复虚拟cell传row出错
- 更新文档

---

V1.1.6
### Bug Fixes
- fix:解决selection性能问题
- fix:优化编辑提示图标，合并单元格场景
- feat:添加placeholder
- fix:editType为none时阻止hoverIconClick进入编辑
- 更新文档

---

V1.1.7
### Bug Fixes
- fix:合并单元格不能有placeholder
- fix:修复offHeight的位置错位
- fix:同给个页面两个table键盘输入会错乱
- fix:默认选择器为启用
  
---

V1.1.8
### Bug Fixes
- fix:解决type为number时change方法中触发全局校验会递归

---

V1.1.9
### Bug Fixes
- fix:聚焦滚动问题
- fix:修复hover图标
---

V1.2.0
### Bug Fixes
- fix:BODY_CELL_STYLE_METHOD 无法作用在index列
---

V1.2.1
### Bug Fixes
- fix: 优化空数据处理逻辑，调整高度计算并重新触发空状态事件
- fix:优化svg图片加载性能
- fix:添加passive去除阻止滚动警告
- fix:过滤数据方法没刷新数据
---

V1.2.2
### Bug Fixes
- fix:beforePasteDataMethod中添加textArr参数
- feat:添加onPastedDataOverflow方法回调
---

V1.2.3
### Bug Fixes
feat: 支持使用 Shift + Tab 键向左移动焦点
feat: 支持使用 Tab 键在编辑状态下移动焦点
---

V1.2.4(废弃)
### Bug Fixes
feat: 添加css全局变量及暗黑主题切换
docs: 更新主题文档
---

V1.2.5
### Bug Fixes
fix: 修复css全局变量比config优先级
---

V1.2.6
### Bug Fixes
fix: 去除复制粘贴剪切阻止默认行为
---