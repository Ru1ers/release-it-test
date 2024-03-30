<!-- 该模板格式最终将用于文档的changedlog.md文件及插件市场的change -->

# 更新日志

### 介绍

该项目的所有显着更改都将记录在该文件中。

格式基于[Keep a Changelog](https://keepachangelog.com/en/1.1.0/)，
并且该项目遵循[语义版本控制](https://semver.org/spec/v2.0.0.html)。

## 更新内容

### 1.0.0

`2024-02-25`

#### 新功能 🎉

- feat(组件名称): 新增 `crossorigin` 和 `referrerpolicy` 属性 by [@Jungzl](https://github.com/Jungzl) in [#12641](https://github.com/youzan/vant/pull/12641)

#### Bug 修复 🐞

- fix(NumberKeyboard): 当主题为自定义时正确渲染删除插槽 by [@TPORL](https://github.com/TPORL) in [#12624](https://github.com/youzan/vant/pull/12624)

#### 文档 📖

- docs: 更新与 Picker 事件相关的参数文档 by [@wjw-gavin](https://github.com/wjw-gavin) in [#12619](https://github.com/youzan/vant/pull/12619)
- docs(DatePicker): 修复英文文档错误 by [@wjw-gavin](https://github.com/wjw-gavin) in [#12620](https://github.com/youzan/vant/pull/12620)
- docs(Uploader): 修复丢失双引号问题 by [@nemo-shen](https://github.com/nemo-shen) in [#12627](https://github.com/youzan/vant/pull/12627)
- docs: 新增完整注册指南 by [@chenjiahan](https://github.com/chenjiahan) in [#12628](https://github.com/youzan/vant/pull/12628)
- docs: 新增 Rsbuild 按需引入指南 by [@chenjiahan](https://github.com/chenjiahan) in [#12629](https://github.com/youzan/vant/pull/12629)

#### 其他更改

- Revert "fix(DropdownMenu): 当传递对象字面量给 title-class 时修复递归更新问题 (#12614)" by [@inottn](https://github.com/inottn) in [#12617](https://github.com/youzan/vant/pull/12617)
- chore(deps): 提升 Rsbuild 至 v0.4 版本 by [@chenjiahan](https://github.com/chenjiahan) in [#12625](https://github.com/youzan/vant/pull/12625)
- chore(workflow): 设置 renovate 配置 by [@chenjiahan](https://github.com/chenjiahan) in [#12626](https://github.com/youzan/vant/pull/12626)
- test: 跳过图像 SSR 测试案例 by [@chenjiahan](https://github.com/chenjiahan) in [#12644](https://github.com/youzan/vant/pull/12644)

#### 新贡献者

- [@TPORL](https://github.com/TPORL) 在 [#12624](https://github.com/youzan/vant/pull/12624) 中首次贡献

### v4.8.4

`2024-02-03`

#### 新功能 🎉

- feat(Picker): 允许隐藏工具栏按钮 by [@chenjiahan](https://github.com/chenjiahan) in [#12599](https://github.com/youzan/vant/pull/12599)

#### 问题修复 🐞

- fix(Sticky): 初始黏贴位置 by [@nemo-shen](https://github.com/nemo-shen) in [#12601](https://github.com/youzan/vant/pull/12601)
- fix(DropdownMenu): 修复传递对象字面量到 title-class 时的递归更新问题 by [@inottn](https://github.com/inottn) in [#12614](https://github.com/youzan/vant/pull/12614)

#### 文档 📖

- docs: 改进快速启动提示 by [@inottn](https://github.com/inottn) in [#12606](https://github.com/youzan/vant/pull/12606)

#### 其他改变

- chore(deps): 升级 Rsbuild 至 0.3.9 by [@chenjiahan](https://github.com/chenjiahan) in [#12600](https://github.com/youzan/vant/pull/12600)
- chore: 避免工作流在 forked repo 上运行 by [@tolking](https://github.com/tolking) in [#12607](https://github.com/youzan/vant/pull/12607)
- chore(workflow): 使用新的 M1 macOS 运行器 by [@chenjiahan](https://github.com/chenjiahan) in [#12615](https://github.com/youzan/vant/pull/12615)

### v4.8.3

`2024-01-20`

#### 新功能 🎉

- feat(Notify): 添加 teleport 属性，由 [@inottn](https://github.com/inottn) 贡献于 [#12556](https://github.com/youzan/vant/pull/12556)
- feat(TextEllipsis): 添加 `action` 插槽，由 [@nemo-shen](https://github.com/nemo-shen) 贡献于 [#12560](https://github.com/youzan/vant/pull/12560)
- feat(ImagePreview): 添加 close-on-click-image 属性，由 [@inottn](https://github.com/inottn) 贡献于 [#12566](https://github.com/youzan/vant/pull/12566)
- feat(icons): 添加图标 `arrow-double-left` 和 `arrow-double-right`，由 [@nemo-shen](https://github.com/nemo-shen) 贡献于 [#12579](https://github.com/youzan/vant/pull/12579)
- feat(Toast): 添加 z-index 属性，由 [@inottn](https://github.com/inottn) 贡献于 [#12587](https://github.com/youzan/vant/pull/12587)

#### 问题修复 🐞

- fix(Tab): 带 sticky 属性的标签页在切换后丢失 'fixed' 类名，由 [@nemo-shen](https://github.com/nemo-shen) 贡献于 [#12547](https://github.com/youzan/vant/pull/12547)
- fix(Image): 之前未导出 ImagePosition 类型，由 [@Jungzl](https://github.com/Jungzl) 贡献于 [#12549](https://github.com/youzan/vant/pull/12549)
- fix(Tabs): 将 van-border-radius-sm 更改为 van-radius-sm，由 [@edram](https://github.com/edram) 贡献于 [#12576](https://github.com/youzan/vant/pull/12576)

#### 文档更新 📖

- docs(Lazyload): 修复 preLoad 类型错误和拼写错误，由 [@RSS1102](https://github.com/RSS1102) 贡献于 [#12554](https://github.com/youzan/vant/pull/12554)
- docs(home): 更新标题层级，由 [@inottn](https://github.com/inottn) 贡献于 [#12577](https://github.com/youzan/vant/pull/12577)

#### 其他变更

- test: 将 vitest 升级到 v1.1.3，由 [@inottn](https://github.com/inottn) 贡献于 [#12546](https://github.com/youzan/vant/pull/12546)
- chore(deps): 将 Rsbuild 升级到 v0.3.2，由 [@chenjiahan](https://github.com/chenjiahan) 贡献于 [#12565](https://github.com/youzan/vant/pull/12565)
- chore(deps): 将 vue 升级到 v3.4.13，由 [@inottn](https://github.com/inottn) 贡献于 [#12567](https://github.com/youzan/vant/pull/12567)
- chore(deps): 将 vite 从 5.0.11 升级到 5.0.12，由 [@dependabot](https://github.com/dependabot) 贡献于 [#12588](https://github.com/youzan/vant/pull/12588)

#### 新贡献者

- [@edram](https://github.com/edram) 在 [#12576](https://github.com/youzan/vant/pull/12576) 中首次贡献
