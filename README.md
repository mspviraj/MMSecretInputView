# MMSecretInputView

[![CI Status](http://img.shields.io/travis/Millman/MMSecretInputView.svg?style=flat)](https://travis-ci.org/Millman/MMSecretInputView)
[![Version](https://img.shields.io/cocoapods/v/MMSecretInputView.svg?style=flat)](http://cocoapods.org/pods/MMSecretInputView)
[![License](https://img.shields.io/cocoapods/l/MMSecretInputView.svg?style=flat)](http://cocoapods.org/pods/MMSecretInputView)
[![Platform](https://img.shields.io/cocoapods/p/MMSecretInputView.svg?style=flat)](http://cocoapods.org/pods/MMSecretInputView)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Requirements

Its a custom view to design a secret view

![circledemo](https://github.com/MillmanY/MMSecretInputView/blob/master/demo1.gif)
![circledemo](https://github.com/MillmanY/MMSecretInputView/blob/master/demo2.gif)

1.Use CompletedBlock to check when input its equal your setting digits

    secretView.completedBlock = { (value) in
            
    }
2.Setting your custom secret view on xib dashboard 
![circledemo](https://github.com/MillmanY/MMSecretInputView/blob/master/demoimage.png)

## Installation

MMSecretInputView is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod ‘MMSecretInputView’ , ‘~> 0.1.3’

```

## Author

Millman, millmanyang@gmail.com

## License

MMSecretInputView is available under the MIT license. See the LICENSE file for more info.
