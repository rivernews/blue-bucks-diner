#  Setup Notes

### How to setup a new Xcode project

- Create project in Xcode **without creating git repo**
- Go to peojct root, `git init`
- `curl https://www.gitignore.io/api/xcode,swift > .gitignore`
- `git add . && git commit -m "initial commit" && git push`.

### How to install a MDC component

- Make sure you have this file `Podfile` first. If not, run `pod init`. Not installed [CocoaPods](https://cocoapods.org/) CocoaPods yet? `sudo gem install cocoapods`.
- To install a component: 
  - Add `pod <component name>` line in Podfile.
  - Run `pod inistall` in project folder. This will do an increment install. Do not do `pod update <component name>`, it's for installing the latest version.
- Make sure you use `.xcworkspace` to open Xcode project.
  

# Current Challenges

- How to do gitignore?
- Setup the basic navigations of blue bucks diner.
  - Try to create a MDC card.

# Reference

- [Creating a collection view (in swift 3, outdated)](https://medium.com/yay-its-erica/creating-a-collection-view-swift-3-77da2898bb7c)
- [Rich MDC Guide for card component, rich text. ](https://material.io/develop/ios/components/cards/#installation)
- [Add constraints programmatically, SO](https://stackoverflow.com/questions/26180822/how-to-add-constraints-programmatically-using-swift)
- [Apple Dev Doc](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/ProgrammaticallyCreatingConstraints.html)
- [MDC iOS Swift Tutorials](https://material.io/collections/developer-tutorials/#ios-swift)
- [Github guide for button component](https://github.com/rivernews/material-components-ios/tree/develop/components/Buttons)
- [theming / styling for button](https://github.com/material-components/material-components-ios/blob/stable/components/Buttons/docs/theming.md)




