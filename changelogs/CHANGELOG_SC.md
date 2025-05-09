## 2.3.8 beta 1 - 2025-04-15

### Fixed
- [日历布局问题](https://github.com/ZzzM/CalendarX/issues/27)
- 关于页面图标显示问题

### Changed
- 日历页面周数显示
---

## 2.3.7 - 2025-03-31

### Added
- 快捷键(esc)，用于返回以及关闭窗口
- 更新设置页面
- 显示周数

### Fixed
- [无法设置开启启动](https://github.com/ZzzM/CalendarX/issues/24)
- [无法设置自动检查更新](https://github.com/ZzzM/CalendarX/issues/20)
- [菜单栏日期无法更新](https://github.com/ZzzM/CalendarX/issues/22)
- [小组件不显示](https://github.com/ZzzM/CalendarX/issues/19)

### Changed
- 快捷键提示框
- 菜单栏图标尺寸、字体大小
- 重新设计外观设置页面
- 重新设计菜单栏设置页面
- 白色字体默认色值 `#EEEEEE`
- 设置`开机启动`，最低系统要求 *macOS 13.0*

### Security
- 避免在 SwiftUI 中使用 `Group`

### Remove
- [WrappingHStack](https://github.com/dkk/WrappingHStack)
- [LaunchAtLogin](https://github.com/sindresorhus/LaunchAtLogin)

---
## 2.3.6 - 2024-12-31

### Added
- 2025 年中国法定节假日

### Fixed
- 适配 macOS 15.0
- [开机启动弹窗](https://github.com/ZzzM/CalendarX/issues/16)
- 日历事件访问权限问题

### Changed
- 隐藏日历弹窗箭头
- 简化版本号显示逻辑
- 重构提醒窗、路由
- 部分页面布局调整
- 小组件日期更新逻辑

### Security
- Complete Concurrency Checking
- Swift 6 
- [swift-format](https://github.com/swiftlang/swift-format)

---

## 2.3.5 - 2024-05-31

### Fixed
- [日历界面显示与日期不同步](https://github.com/ZzzM/CalendarX/issues/11)
- 部分页面按钮显示异常
- 小组件背景色不随主题切换而变化

### Changed
- 外观设置重构，支持设置不同主题下的强调色、背景色
- 菜单栏设置重构，新增多种样式的图标
- 调整英文菜单栏日期样式
- 获取日历事件逻辑优化
- 部分页面配色调整
- 小组件日期更新逻辑优化
- 小组件设置重构，支持设置不同主题下的强调色、背景色

### Removed
- 菜单栏文字样式


---
## 2.3.4 - 2024-01-10

### Added
- 可交互小组件 ( **macOS 14.0 +** )
    - `<`: 上一月
    - `>`: 下一月
    - `Month & Year`: 今天

- 支持键盘快捷键的切换

### Fixed
- 二级界面的显示问题
- 日历界面显示与日期不同步

### Changed
- App 推荐

---
## 2.3.3 - 2024-01-05

### Added
- 日历界面可通过键盘快捷键切换年月
    - ⬅️：上一月
    - ➡️：下一月
    - ⬆️：上一年
    - ⬇️：下一年
    - 空格：今天

### Fixed
- **macOS 14** 日历事件权限问题
- **macOS 14** 小组件显示问题

### Changed
- 过渡动画

---

## 2.3.2 - 2023-12-19

### Added
- 日历小组件
- 2024 年中国法定节假日

### Fixed
- 菜单栏日期样式拖拽编辑问题

### Changed
- 过渡动画
- 提醒窗

---

## 2.3.1 - 2023-03-09

### Fixed
- 无法设置自动检查更新
- 无法设置开机启动

---
## 2.3.0 - 2023-03-08

### Added
- 自动检查更新
- 外观设置
- 日历设置
- 语言设置
- 提示弹窗
- 关于

### Fixed
- [日历时间标识显示问题](https://github.com/ZzzM/CalendarX/issues/6)
- [菜单栏文字显示问题](https://github.com/ZzzM/CalendarX/issues/4)
- 计时器问题

### Changed
- 日期详情
- 设置
- 菜单栏样式设置
- App 推荐

---
## 2.2.2 - 2022-12-09

### Added
- 2023 年中国法定节假日
- App 推荐

### Changed

- 设置界面
- 过渡动画

---

## 2.2.1 - 2022-11-03

### Added
- 自定义菜单栏样式（默认、文本、日期和时间）

### Changed
- 设置界面

### Fixed
- 适配 macOS 13.0

---

## 2.2.0 - 2022-04-29

### Added
- 支持开机启动
  

### Changed
- 全新设计
- 更新应用名称为 **CalenderX**
- 更新应用图标
- 更新 2022 年中国法定节假日


### Removed
- 小组件

---

## 2.1.4 - 2021-02-08

### Changed
- 优化一些动画

### Fixed
- 时间不同步

---

## 2.1.3 - 2021-01-12

### Changed
- 更新设置界面

### Fixed
- 时间不同步
- 日历显示错误
- 小组件显示错误

---

## 2.1.2 - 2020-12-21

### Changed
- 优化暗黑模式

---

## 2.1.1 - 2020-12-21

### Changed
- 调整界面
- 优化交互

---

## 2.1.0 - 2020-12-18

### Changed
- 调整界面
- 优化交互

---

## 2.0.0 - 2020-12-17

### Changed
- 全新设计
- 更新 2021 年中国法定节假日

### Added
- 支持 macOS Big Sur 小组件

---

## 1.2.7 - 2020-11-04

### Changed
- 更新应用图标

### Fixed
- 日历事件时间错误 bug

---

## 1.2.6 - 2020-10-12

### Changed
- 打开日历时，重置为今天

---

## 1.2.5 - 2020-07-05
### Added
- 本地化支持

---

## 注意

- `Added` 新添加的功能
- `Changed` 对现有功能的变更
- `Deprecated` 已经不建议使用，准备很快移除的功能
- `Removed` 已经移除的功能
- `Fixed` 对bug的修复
- `Security` 对安全的改进 