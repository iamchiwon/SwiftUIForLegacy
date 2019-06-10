# SwiftUI for legacy
Duck programming to clone SwiftUI for under iOS13

<br/>

## SwiftUI is cool, but..

SwiftUI introduced in WWDC 2019 that supports declarative ui programming with swift 5.1 on XCode11 and iOS13.<br/>
It was cool! Every iOS developers love that.<br/>
But it works on **iOS13 above only**.

So, trying clone SwiftUI for under iOS13 by *duck programming*.<br/>
Just trying for fun and study.

> **Duck programming** <br/>
> Developing to satisfy the present situation without perfect design.

<br/>

#### Don't be serious

Not intended to fully implementation.<br/>
Contribution always be welcomed.

<br/>

## Walking like a duck

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

### [ ] 4. Image to UIImageView

### [ ] 5. Button to UIButton

### [ ] 6. HStack, VStack to UIStackView

### [ ] 7. ZStack to UIView


<br/>

# Installation (will be)

<strike>pod 'SwiftUILegacy'</strike>

<br/>

# License

MIT License.
