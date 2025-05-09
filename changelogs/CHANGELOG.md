## 2.3.8 beta 1 - 2025-04-15

### Fixed
- [Calendar layout issue](https://github.com/ZzzM/CalendarX/issues/27)
- About screen icon display issue

### Changed
- Calendar screen week number display
---
## 2.3.7 - 2025-03-31
### Added
- ESC key shortcut (back/close window)
- Updated settings screen
- Show week number

### Fixed
- [Unable to set launch at login](https://github.com/ZzzM/CalendarX/issues/24)
- [Unable to set automatic check for updates](https://github.com/ZzzM/CalendarX/issues/20)
- [Menu bar date not updating](https://github.com/ZzzM/CalendarX/issues/22)
- [Widgets not displaying](https://github.com/ZzzM/CalendarX/issues/19)

### Changed
- Shortcut key hint UI
- Menu bar icon size & font size
- Redesigned appearance settings screen
- Redesigned menu bar settings screen
- Default white font color set to `#EEEEEE`
- Set up `Launch at login`, requires *macOS 13.0 +*

### Security
- Avoided using `Group` in SwiftUI

### Removed
- [WrappingHStack](https://github.com/dkk/WrappingHStack)
- [LaunchAtLogin](https://github.com/sindresorhus/LaunchAtLogin)

---
## 2.3.6 - 2024-12-31

### Added
- Chinese statutory holidays in 2025

### Fixed
- macOS 15.0 compatibility
- [Startup launch dialog](https://github.com/ZzzM/CalendarX/issues/16)
- Calendar event access permission issues

### Changed
- Hidden calendar popup arrow
- Simplified version number 
- Refactored reminder window and routing
- Adjusted layout of some screens
- Updated date logic for widgets

### Security
- Complete Concurrency Checking
- Swift 6 
- [swift-format](https://github.com/swiftlang/swift-format)

---
## 2.3.5 - 2024-05-31

### Fixed
- [Calendar view display is not synchronized with the date](https://github.com/ZzzM/CalendarX/issues/11)
- Some page buttons display abnormally
- Widget background color does not change with theme switching

### Changed
- Appearance settings have been reconstructed to support setting accent colors and background colors under different themes.
- Menu bar settings have been restructured, added multiple style icons
- Adjust the date format in the English menu bar
- Get calendar event logic optimization
- Some page color adjustments
- Widget date update logic optimization
- Widget settings have been reconstructed to support setting accent colors and background colors under different themes.

### Removed
- Menu bar text style

---
## 2.3.4 - 2024-01-10

### Added
- Interactive Widget ( **macOS 14.0 +** )
    - `<`: Last month
    - `>`: Next month
    - `Month & Year`: Today

- Keyboard shortcut-enabled toggle

### Fixed
- Display issues on secondary level view
- Calendar view display is not synchronized with the date

### Changed
- Recommendations

---
## 2.3.3 - 2024-01-05

### Added
- Calendar view can be changed by keyboard shortcuts
    - ⬅️: Last month
    - ➡️: Next month
    - ⬆️: Last year
    - ⬇️: Next year
    - Space: Today
    
### Fixed
- **macOS 14** calendar event permission issues
- **macOS 14** widget display issues

### Changed
- Transition animations

---
## 2.3.2 - 2023-12-19

### Added
- Calendar Widget
- Chinese statutory holidays in 2024

### Fixed
- Menu bar date style drag and drop editing issue

### Changed
- Transition animations
- Alert View

---
## 2.3.1 - 2023-03-09

### Fixed
- Unable to set up automatic update check
- Unable to set up launch at login

---

## 2.3.0 - 2023-03-08

### Added
- Automatically checks for updates
- Appearance settings
- Calendar settings
- Language settings
- Prompt dialog
- About

### Fixed
- [Calendar event badge display issue](https://github.com/ZzzM/CalendarX/issues/6)
- [Menubar text display issue](https://github.com/ZzzM/CalendarX/issues/4)
- Timer issue

### Changed
- Date detail
- Settings
- Menubar style settings
- App Recommendations


---

## 2.2.2 - 2022-12-09

### Added
- Chinese statutory holidays in 2023
- App Recommendations

### Changed
- Settings
- Transition animation

---

## 2.2.1 - 2022-11-03

### Added
- Custom menubar style（default, text, date&time）

### Changed
- Settings

### Fixed
- Adaptation to macOS 13.0


---

## 2.2.0 - 2022-04-29

### Added
- Enable launch at login

### Changed
- New design
- App name
- App icon
- Chinese statutory holidays in 2022
  
### Removed
- Widget

---

## 2.1.4 - 2021-02-08

### Changed
- Optimized some animations

### Fixed
- Time not synchronized 

---

## 2.1.3 - 2021-01-12

### Changed
- Settings

### Fixed
- Time not synchronized 
- Calendar display error
- Widget display error

---

## 2.1.2 - 2020-12-21

### Changed
- Optimized dark mode

---

## 2.1.1 - 2020-12-21

### Changed
- Adjusted UI
- Optimized interaction

---

## 2.1.0 - 2020-12-18

### Changed
- Adjusted UI
- Optimized interaction

---

## 2.0.0 - 2020-12-17

### Changed
- New design
- Updated Chinese statutory holidays in 2021

### Added
- Support for macOS Big Sur widget

---

## 1.2.7 - 2020-11-04

### Changed
- App icon

### Fixed
- Calendar event time error bugs

---

## 1.2.6 - 2020-10-12

### Changed
- Reset to today when you open the calendar

---

## 1.2.5 - 2020-07-05
### Added
- Localization support

---

## Note

- `Added` for new features
- `Changed` for changes in existing functionality
- `Deprecated` for soon-to-be removed features
- `Removed` for now removed features
- `Fixed` for any bug fixes
- `Security` in case of vulnerabilities
