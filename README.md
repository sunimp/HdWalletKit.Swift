# HDWalletKit.Swift

HD Wallet library that makes possible generating and validating mnemonic phrases. Also it can generates public / private keys for HD keychain.

## Requirements

* Xcode 15.4+
* Swift 5.10+
* iOS 14.0+

## Installation

### Swift Package Manager

The [Swift Package Manager](https://swift.org/package-manager/) is a tool for automating the distribution of Swift code
and is integrated into the `swift` compiler. It is in early development, but HDWalletKit does support its use on
supported platforms.

Once you have your Swift package set up, adding HDWalletKit as a dependency is as easy as adding it to
the `dependencies` value of your `Package.swift`.

```swift
dependencies: [
    .package(url: "https://github.com/sunimp/HDWalletKit.Swift.git", .upToNextMajor(from: "1.4.0"))
]
```

## License

HDWalletKit is available under the MIT license. See the LICENSE file for more info.
