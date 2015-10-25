# KGNAutoLayout

`KGNAutoLayout` makes `AutoLayout` easy!

[![iOS 8.0+](http://img.shields.io/badge/iOS-8.0%2B-blue.svg)]()
[![Xcode 7.1](http://img.shields.io/badge/Xcode-7.1-blue.svg)]()
[![Swift 2.0](http://img.shields.io/badge/Swift-2.0-blue.svg)]()
[![Release](https://img.shields.io/github/release/kgn/KGNAutoLayout.svg)](/releases)
[![Build Status](http://img.shields.io/badge/License-MIT-lightgrey.svg)](/LICENSE)

[![Build Status](https://travis-ci.org/kgn/KGNAutoLayout.svg)](https://travis-ci.org/kgn/KGNAutoLayout)
[![Carthage Compatible](https://img.shields.io/badge/Carthage-Compatible-4BC51D.svg)](https://github.com/Carthage/Carthage)
[![CocoaPods Version](https://img.shields.io/cocoapods/v/KGNAutoLayout.svg)](https://cocoapods.org/pods/KGNAutoLayout)
[![CocoaPods Platforms](https://img.shields.io/cocoapods/p/KGNAutoLayout.svg)](https://cocoapods.org/pods/KGNAutoLayout)

[![Twitter](https://img.shields.io/badge/Twitter-@iamkgn-55ACEE.svg)](http://twitter.com/iamkgn)
[![Star](https://img.shields.io/github/followers/kgn.svg?style=social&label=Follow%20%40kgn)](https://github.com/kgn)
[![Star](https://img.shields.io/github/stars/kgn/KGNAutoLayout.svg?style=social&label=Star)](https://github.com/kgn/KGNAutoLayout)

## Installing

### Carthage
```
github "kgn/KGNAutoLayout"
```

### CocoaPods
```
pod 'KGNAutoLayout'
```

## Examples

### Example App

![Example App](/KGNAutoLayoutExample.gif)

### Pin: Superview

``` Swift
view.pinToEdgesOfSuperview(offset: 20)
```
![pinToEdgesOfSuperview_offset20](Example/Snapshots/pinToEdgesOfSuperview_offset20.png)
--


``` Swift
view.pinToTopEdgeOfSuperview(offset: 20)
```
![pinToTopEdgeOfSuperview_offset20](Example/Snapshots/pinToTopEdgeOfSuperview_offset20.png)
--


``` Swift
view.pinToRightEdgeOfSuperview(offset: 20)
```
![pinToRightEdgeOfSuperview_offset20](Example/Snapshots/pinToRightEdgeOfSuperview_offset20.png)
--


``` Swift
view.pinToBottomEdgeOfSuperview(offset: 20)
```
![pinToBottomEdgeOfSuperview_offset20](Example/Snapshots/pinToBottomEdgeOfSuperview_offset20.png)
--


``` Swift
view.pinToLeftEdgeOfSuperview(offset: 20)
```
![pinToLeftEdgeOfSuperview_offset20](Example/Snapshots/pinToLeftEdgeOfSuperview_offset20.png)
--


``` Swift
view.pinToSideEdgesOfSuperview(offset: 20)
```
![pinToSideEdgesOfSuperview_offset20](Example/Snapshots/pinToSideEdgesOfSuperview_offset20.png)
--


``` Swift
view.pinToTopAndBottomEdgesOfSuperview(offset: 20)
```
![pinToTopAndBottomEdgesOfSuperview_offset20](Example/Snapshots/pinToTopAndBottomEdgesOfSuperview_offset20.png)
--

### Pin: Edges

``` Swift
view.pinTopEdgeToTopEdgeOfItem(itemView, offset: 20)
```
![pinTopEdgeToTopEdgeOfItem_offset20](Example/Snapshots/pinTopEdgeToTopEdgeOfItem_offset20.png)
--


``` Swift
view.pinRightEdgeToRightEdgeOfItem(itemView, offset: 20)
```
![pinRightEdgeToRightEdgeOfItem_offset20](Example/Snapshots/pinRightEdgeToRightEdgeOfItem_offset20.png)
--


``` Swift
view.pinBottomEdgeToBottomEdgeOfItem(itemView, offset: 20)
```
![pinBottomEdgeToBottomEdgeOfItem_offset20](Example/Snapshots/pinBottomEdgeToBottomEdgeOfItem_offset20.png)
--


``` Swift
view.pinLeftEdgeToLeftEdgeOfItem(itemView, offset: 20)
```
![pinLeftEdgeToLeftEdgeOfItem_offset20](Example/Snapshots/pinLeftEdgeToLeftEdgeOfItem_offset20.png)
--

### Center

``` Swift
view.centerInSuperview()
```
![centerInSuperview](Example/Snapshots/centerInSuperview.png)
--


``` Swift
view.centerHorizontallyInSuperview()
```
![centerHorizontallyInSuperview](Example/Snapshots/centerHorizontallyInSuperview.png)
--


``` Swift
view.centerVerticallyInSuperview()
```
![centerVerticallyInSuperview](Example/Snapshots/centerVerticallyInSuperview.png)
--


``` Swift
parentView.centerViewsHorizontally([view1, view2, view3])
```
![centerViewsHorizontally](Example/Snapshots/centerViewsHorizontally.png)
--


``` Swift
parentView.centerViewsVertically([view1, view2, view3])
```
![centerViewsVertically](Example/Snapshots/centerViewsVertically.png)
--

### Size

``` Swift
view.sizeToWidth(80)
```
![sizeToWidth80](Example/Snapshots/sizeToWidth80.png)
--


``` Swift
view.sizeToHeight(80)
```
![sizeToHeight80](Example/Snapshots/sizeToHeight80.png)
--


``` Swift
view.sizeToWidthAndHeight(80)
```
![sizeToWidthAndHeight80](Example/Snapshots/sizeToWidthAndHeight80.png)
--


``` Swift
view.sizeHeightToWidthAspectRatio(16/9)
```
![sizeHeightToWidthAspectRatio16by9](Example/Snapshots/sizeHeightToWidthAspectRatio16by9.png)
--


``` Swift
view.sizeWidthToHeightAspectRatio(16/9)
```
![sizeWidthToHeightAspectRatio16by9](Example/Snapshots/sizeWidthToHeightAspectRatio16by9.png)
--

### Position
### Between

``` Swift
view.fitBetween(topView, bottomItem: bottomView, offset: 20)
```
![fitBetweenTopAndBottomItems_offset20](Example/Snapshots/fitBetweenTopAndBottomItems_offset20.png)
--


``` Swift
view.fitBetween(leftView, rightItem: rightView, offset: 20)
```
![fitBetweenLeftAndRightItems_offset20](Example/Snapshots/fitBetweenLeftAndRightItems_offset20.png)
--

### Fill

``` Swift
parentView.fillHorizontally([view1, view2, view3], separation: 20)
```
![fillHorizontally_separation20](Example/Snapshots/fillHorizontally_separation20.png)
--


``` Swift
parentView.fillVertically([view1, view2, view3], separation: 20)
```
![fillVertically_separation20](Example/Snapshots/fillVertically_separation20.png)
--

### Bound

## TODO:
- [X] Travis
- [X] Badges
- [X] Tests
- [X] Carthage
- [ ] CocoaPods (Just need to release)
- [ ] Description (Give examples)
- [X] Documentation
- [X] Example App
