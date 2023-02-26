# run_async_on_playground_xcode

```swift
import PlaygroundSupport

PlaygroundPage.current.needsIndefiniteExecution = true

DispatchQueue.main.asyncAfter(deadline: .now() + 3) {
    let greeting = "Hello after 3 seconds"
    print(greeting)
}
```
