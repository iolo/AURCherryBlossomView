# AURCherryBlossomView

![language](https://img.shields.io/badge/Language-%20Swift%20-orange.svg)
[![Version](https://img.shields.io/cocoapods/v/AURCherryBlossomView.svg?style=flat)](http://cocoapods.org/pods/AURCherryBlossomView)
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
[![Platform](https://img.shields.io/cocoapods/p/AURCherryBlossomView.svg?style=flat)](http://cocoapods.org/pods/AURCherryBlossomView)

<p align="left">
  <img src="Example/Demo.gif" alt="CherryBlossom" width="350" height="444">
</p>

## Requirements

- iOS 9.0+
- Xcode 8.0+
- Swift 3.0+

## Usage

### Import
```swift
import "AURCherryBlossomView"
```
Create AURCherryBlossomView and add the subView

```swift
let cherryBlossomView = AURCherryBlossomView(frame: self.view.bounds)

self.view.addSubview(cherryBlossomView)
```

### Change Property
```swift
cherryBlossomView.birthRate = 4.0

cherryBlossomView.type = .CherryBlossom
```

### Start 
```swift
cherryBlossomView.startBlossom()
```

## Installation

Available in [CocoaPods](https://cocoapods.org/?q=AUR)

```ruby
pod "AURCherryBlossomView"
```


## License

```
Copyright (c) 2016 aminaura

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
