# NotesApp

1. Delete Main.storyboard
2. Remove Info.plist [Main storyboard file base name]


- ViewController.swift

** viewDidLoad() ** method:  
```swift
view.backgroundColor = .yellow
```

- AppDelegate.swift
** application(:didFinishLaunchingWithOptions) **
```swift
window = UIWindow()
window?.makeKeyAndVisible()
window?.rootViewController = ViewController()
```

## Rename ViewController to FolderController



