# BxTextField

The putting Text.

## Features

- [x] The putting Text


## Requirements

- iOS 8.0+
- Swift 3.0+


## Installation

### CocoaPods

[CocoaPods](http://cocoapods.org) is a dependency manager for Cocoa projects. You can install it with the following command:

```bash
$ gem install cocoapods
```

To integrate BxTextField into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '8.0'
use_frameworks!

target '<Your Target Name>' do
pod 'BxTextField', '~> 0.9'
end
```

Then, run the following command:

```bash
$ pod install
```


### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code and is integrated into the `swift` compiler. It is in early development, but BxTextField does support its use on supported platforms. 

Once you have your Swift package set up, adding BxTextField as a dependency is as easy as adding it to the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .Package(url: "https://github.com/ByteriX/BxTextField.git", majorVersion: 1)
]
```

### Manually

If you prefer not to use either of the aforementioned dependency managers, you can integrate `BxTextField` into your project manually.

#### Embedded Framework

- Open up Terminal, `cd` into your top-level project directory, and run the following command "if" your project is not initialized as a git repository:

```bash
$ git init
```

- Add `BxTextField` as a git [submodule](http://git-scm.com/docs/git-submodule) by running the following command:

```bash
$ git submodule add https://github.com/ByteriX/BxTextField.git
```

- Add all sources and resources from local copy of `BxTextField` to the build phase of the project.

- And that's it!


## Usage

### Example

```swift

class SimpleController: UIViewController {

    
    override func viewDidLoad() {
        super.viewDidLoad()
        
        // BxTextField
    }
    
}

```

## License

BxInputController is released under the MIT license. See LICENSE for details.
