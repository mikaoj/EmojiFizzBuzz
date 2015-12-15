# EmojiFizzBuzz - just for fun
Fizz buzz in Swift with emojis
```swift
func 💤🐝(🅰: 🔢) -> 📝 {
    switch (🅰 % 👪 == 💩, 🅰 % 👋 == 💩) {
    case (👍, 👎):
        return 💤
    case (👎, 👍):
        return 🐝
    case (👍, 👍):
        return 💤+🐝
    default:
        return 📝(🅰)
    }
}
```
