SCPopUpView
===========

Animated Popup View. Swift

##Easy to use !
```swift
SCPopUpView().showTitle(self, title: kSuccessTitle, subTitle: kSubtitle, duration: kDefaultAnimationDuration, style: SCPopUpViewStyle.SCPopUpViewSuccess)
```

Main methods :

```swift
//initialisation with a Title and a Subtitle message
SCPopUpView().showTitle(self, title: kSuccessTitle, subTitle: kSubtitle, duration: kDefaultAnimationDuration, style: SCPopUpViewStyle.SCPopUpViewSuccess)
```

Four types of popup views (for now)

```swift
enum SCPopUpViewStyle: Int {
    case SCPopUpViewSuccess
    case SCPopUpViewError
    case SCPopUpViewNotice
    case SCPopUpViewWarning
    case SCPopUpViewInfo
}
```

Has been developted initialy for [Scroll Feed](https://itunes.apple.com/us/app/scroll-feed/id842422195?ls=1&mt=8) app

[hackua](https://twitter.com/hackua)
