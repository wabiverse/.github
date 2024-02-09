### What's New

**`import OpenColorIO`**            |  **`import OpenImageIO`** 
:-------------------------:|:-------------------------:
![](https://github.com/wabiverse/MetaverseKit/assets/18516968/34041f2b-44a8-4814-b2ae-075716a7ebad)  |  ![](https://github.com/wabiverse/MetaverseKit/assets/18516968/649e43f4-c821-4ffe-b0db-5efa0877a281)


- You may now successfully import **OpenColorIO** and **OpenImageIO** directly into the Swift programming language and begin to consume these APIs directly, made possible by Swift **5.9**'s C++ interoperability feature.

### Usage

Add **MetaverseKit** as a package dependency to your own Swift project's **`Package.swift`** file:
```swift
// swift-tools-version: 5.9

dependencies: [
  .package(url: "https://github.com/wabiverse/MetaverseKit", from: "1.4.4")
]
```

#### Linux
For Linux, these are the only dependencies required, as **MetaverseKit** provides everything else:
| Dependency  | CentOS             | Ubuntu |
| ------------- | --------------- | ------- |
| **Boost**      | boost-devel      | libboost-all-dev  |
| **Python**    | python3-devel | python3-dev        |
| **BZ2**         | bzip2-devel      | libbz2-dev           |
| **ZLib**        | zlib-devel          | zlib1g-dev           |
