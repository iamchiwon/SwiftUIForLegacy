# SwiftUI for legacy
Duck Programming to clone SwiftUI for under iOS13


## Cool SwiftUI but..

SwiftUI introduced in WWDC 2019 that supports declarative ui programming with swift 5.1 on XCode11 and iOS13.
It was cool! Every iOS programmers love that.
But it works on iOS13 above only.

So, Trying clone SwiftUI for under iOS13 by duck Programming.
Just trying for fun and study. (Don't be serious)

Not fully implemented.
Contribution always be welcomed.

## SwiftUILegacy should be worked

### [ ] 1. Start with UIHostingController

```swift
let window = UIWindow(frame: UIScreen.main.bounds)
window.rootViewController = UIHostingController(rootView: ContentView())
self.window = window
window.makeKeyAndVisible()
```

### [ ] 2. View struct providing UIView

```swift
struct ContentView : View {
    var body: some View {
    }
}
```

### [ ] 3. Text to UILabel

```swift
struct ContentView : View {
    var body: some View {
        Text("Hello World")  // <--
    }
}
```

# Installation (will be)

```ruby
pod 'SwiftUILegacy'
```


# License

MIT License.
