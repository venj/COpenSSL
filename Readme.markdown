COpenSSL
========

OpenSSL module for Swift. 

Note: Currently only `md4.h`, `md5.h`, `sha.h`, `hmac.h`, `evp.h` is included. If you want to add more header files, please fork this project for your needs. Or you can send a pull request.

Usage
-----

1. Install libssl-dev:

    ```
    sudo apt-get install libssl-dev
    ```

2. Add dependency in your `Package.swift` file: 

    ```swift
    dependencies: [
        .Package(url: "https://github.com/venj/COpenSSL.git", versions: Version(0,0,2) ..< Version(1,0,0)),
    ]
    ```

3. In your code:

    ```swift
    import COpenSSL
    ```

4. Build your code:

    ```
    swift build
    ```


Versioning
----------

Version for this module has no relationship to OpenSSL version number. The version number for this module is only used for Swift Package Manager.
