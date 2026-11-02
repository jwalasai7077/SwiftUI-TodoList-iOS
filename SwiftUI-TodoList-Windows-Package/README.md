# Todo List project package — Windows + iOS source

This package contains two versions:

## 1. Run immediately on Windows
Open `Windows-Run-Version/` and double-click `START-WINDOWS.bat`. It launches a browser-based task manager with task creation, editing, deletion, completion, search, priority filters, sorting, local saving, and dark mode. No installation is required.

## 2. Original native iOS project
`Original-iOS-Xcode-Project/` contains the original SwiftUI/Xcode project from the supplied archive. Open `SwiftUIList.xcodeproj` using Xcode on macOS, select an iPhone simulator, and press Cmd+R. Windows cannot build or run this native SwiftUI project because Apple's iOS SDK and simulator are provided through Xcode for macOS.

## Attribution
The original iOS source archive identifies the project as “SwiftUI Todo List” by Fredrik Eilertsen and links to https://github.com/fredrik9000/TodoList_iOS. No LICENSE file was included in the supplied archive. Keep the original attribution and check the upstream repository's license/permissions before redistributing or presenting the original Swift code as your own. The Windows browser version in this package is a separate implementation for local demonstration.
