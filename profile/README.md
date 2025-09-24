## Mac Apps

### [The Soulver X series](https://github.com/soulverteam/X-Series)
An experimental series of advanced Soulvers for testing out new ideas & workflows
- X1 (2024) introduced multiple tabs per sheet, the header sheet for defining new entities & connecting sheets to JSON APIs, and custom natural language functions
- X2 (2025) introduced inline subsheets, dividers & slider tokens

### [Simple Soulver](https://github.com/soulverteam/SimpleSoulver)
- Demonstrates how to build a simple Soulver-like Mac app in Swift & AppKit using [SoulverCore](https://github.com/soulverteam/SoulverCore)
- Supports variable & syntax coloring

## Frameworks

### [SoulverCore](https://github.com/soulverteam/SoulverCore)
-  Use Soulver's natural language math engine in your Swift apps.
```swift
import SoulverCore
let calculator = Calculator(customization: .standard)
let result = calculator.calculate("45 is what % of 120")
```
SoulverCore is available as a closed-source xcframework for Apple platforms, and as a dynamic library on [Windows & Linux](https://github.com/soulverteam/SoulverCore-Multiplatform).

### [Date Parsing](https://github.com/soulverteam/DateParsing) (with SoulverCore)
-  Quickly parse dates from strings in any common format, and power natural language date entry features in your Swift apps.
```swift
import SoulverCore
let date = "two weeks ago".dateValue
```

### [String Parsing](https://github.com/soulverteam/StringParsing) (with SoulverCore)
-  A new declarative and type-safe approach to parsing data points from strings (an alternative to regex).
```swift
import SoulverCore
let duckCount = "There are 3 ducks in the pond".find(.number)
```
## Command line tools

Standalone versions of Soulver for use from the Terminal

-  [Soulver CLI](https://github.com/soulverteam/Soulver-CLI) (for macOS)
-  [Soulver CLI](https://github.com/soulverteam/Soulver-CLI-Windows) (for Windows)
