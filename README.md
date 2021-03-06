# ZuperForms
![Version](https://img.shields.io/cocoapods/v/ZuperForms.svg?style=flat)

`ZuperForms` is built for the purpose of ensuring safety against COVID-19 by maintaining the proper checklist. The `ZuperForms` makes it quick and easy to build an excellent checklist module in your iOS app. We provide powerful and customizable UI screens and elements that can be used out-of-the-box to make it according to your app’s theme.


## Requirements

- iOS 11.0+ 
- Xcode 10.2+
- Swift 5+

### CocoaPods

[CocoaPods](https://cocoapods.org) is a dependency manager for Cocoa projects. For usage and installation instructions, visit their website. To integrate ZuperForms into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
pod 'ZuperForms'
```
![ZuperForms](https://i.ibb.co/dkDk6qj/merge-from-ofoct.png)


## Examples
```ruby
import ZuperForms

let zuperFormObj = ZuperForms(companyName:"ZuperSoft Solutions")
zuperFormObj.delegate = self
zuperFormObj.modalPresentationStyle = .fullScreen
self.present(zuperFormObj, animated: true, completion: nil)


```

### Clear Data
```ruby
ZuperFormsData.clear()
```

### Themes
```ruby
ZuperFormsTheme.backgroundColor = .black
ZuperFormsTheme.primaryColor = .red
ZuperFormsTheme.labelTextColor = .white
ZuperFormsTheme.textFieldTextColor = .white
ZuperFormsTheme.cardViewBackgroundColor = .black
```
