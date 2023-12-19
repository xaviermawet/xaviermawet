### Hi there 👋

```swift
class About: Me {
    func getCurrentWorkplace() -> [String: (String, String)] {
        return ["workplace": (
            company: "EVS Broadcast Equipment",
            position: "Software & Cloud Engineer 👨‍💻"
        )]
    }
    
    func getDailyKnowledge() -> [Knowledge] {
        return [
            .NET(CSharp: 8),
            .Cpp(2020),
            .Qt(5, 6), .QML,
            .Swift("& SwiftUI"),
            .Cloud(providers: [.AWS, .Azure]),
        ]
    }
    
    func getFutureGoal() -> String {
        return "To contribute to open source."
    }
}
```
