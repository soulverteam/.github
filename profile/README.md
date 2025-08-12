## Swift APIs

### [SoulverCore](https://github.com/soulverteam/SoulverCore)
-  Use Soulver's natural language math engine in your Swift apps.
```swift
import SoulverCore
let calculator = Calculator(customization: .standard)
let result = calculator.calculate("45 is what % of 120")
```

### [Date Parsing](https://github.com/soulverteam/DateFromString) (with SoulverCore)
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
## Soulver in the Command Line

-  [Soulver CLI](https://github.com/soulverteam/Soulver-CLI) (for macOS)
-  [Soulver CLI](https://github.com/soulverteam/Soulver-CLI-Windows) (for Windows)
